---
title: "Snabbstartsguide"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Skapa en virtuell miljö, installera groupdocs-signature-net och kör tre enkla exempel: signera en PDF med en textsignatur, sök efter signaturer i den och verifiera dem."
type: docs
url: /sv/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Den här guiden ger en snabb översikt över hur man sätter upp och börjar använda GroupDocs.Signature för Python via .NET. Biblioteket lägger till, hittar, verifierar, uppdaterar och tar bort elektroniska signaturer i PDF-, Word-, Excel-, PowerPoint-, OpenDocument- och bildfiler med några få kodrader.

## Prerequisites

För att fortsätta, se till att du har:

1. En konfigurerad miljö enligt beskrivningen i avsnittet [Systemkrav](https://docs.groupdocs.com/signature/python-net/system-requirements/). På Linux och macOS inkluderar detta några systempaket.
2. Eventuellt en [Tillfällig licens](https://purchase.groupdocs.com/temporary-license/) för att testa alla produktfunktioner. Utan licens fungerar biblioteket i utvärderingsläge: det bearbetar dokument upp till två sidor och lägger till en utvärderingsrad på varje sida det signerar. Se [Licensiering](https://docs.groupdocs.com/signature/python-net/licensing/).

## Set Up Your Development Environment

För bästa praxis, använd en virtuell miljö för att hantera beroenden. Läs mer i guiden [Skapa och använd virtuella miljöer](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Skapa en virtuell miljö:

{{< tabs \"create-venv\">}}
{{< tab \"Windows\" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

Aktivera den:

{{< tabs \"activate-venv\">}}
{{< tab \"Windows\" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install the `groupdocs-signature-net` Package

{{< tabs \"install-package\">}}
{{< tab \"Windows\" >}}
```ps
py -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< /tabs >}}

Se [Installation](/signature/python-net/guides/installation/) för att låsa en version och för att installera utan åtkomst till PyPI.

## Example 1: Sign a PDF with a Text Signature

Öppna ett dokument, beskriv signaturen med [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/), och spara den signerade kopian.

{{< tabs "sign_pdf_with_text_signature">}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Öppna dokumentet; with-blocket frigör filen när det avslutas
    with Signature("sample.pdf") as signature:
        # En textsignatur 100 pixlar från vänster- och överkanten på den första sidan.
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Signera och spara resultatet till en ny fil; källfilen förblir oförändrad.
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")

if __name__ == "__main__":
    sign_pdf_with_text_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab "signed_sample.pdf" >}}
```text
Binary file (PDF, 125 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/sign_pdf_with_text_signature/signed_sample.pdf)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Search a Document for Signatures

Hitta de signaturer som ett dokument redan innehåller. `search` tar en lista med sökalternativ, ett per signaturtyp att leta efter, och returnerar dem i `result.signatures`.

{{< tabs "search_document_for_signatures">}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Sök efter textsignaturer på varje sida.
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab "search-document-signatures.txt" >}}
```text
Text signature 'John Smith' on page 1
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/search_document_for_signatures/search-document-signatures.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Verify a Signature

Kontrollera att ett dokument har den signatur du förväntar dig. Verifieringen lyckas när en textsignatur med exakt denna text hittas.

{{< tabs "verify_text_signature">}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab "verify-text-signature.txt" >}}
```text
Document is signed by John Smith: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/verify_text_signature/verify-text-signature.txt)
{{< /tab >}}
{{< /tabs >}}

## Run the Examples

Spara varje exempel i sin egen `.py`-fil bredvid exempel‑filerna. Din mapp bör se ut ungefär så här:

```Directory
📂 demo-app
 ├──sign_pdf_with_text_signature.py
 ├──search_document_for_signatures.py
 ├──verify_text_signature.py
 ├──sample.pdf
 └──signed.pdf
```

Kör ett exempel från den mappen:

{{< tabs "run-the-app">}}
{{< tab \"Windows\" >}}
```ps
py sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< /tabs >}}

När du är klar, deaktivera den virtuella miljön genom att köra `deactivate` eller stänga ditt skal.

## Apply a License

Ställ in miljövariabeln `GROUPDOCS_LIC_PATH` till den fullständiga sökvägen för din licensfil, och licensen tillämpas automatiskt när `groupdocs.signature` importeras. Ingen kod behövs. Alternativt kan du tillämpa den i kod en gång, innan något annat anrop:

```python
from groupdocs.signature import License

License().set_license("/path/to/GroupDocs.Signature.lic")
```

Ämnet [Licensiering](https://docs.groupdocs.com/signature/python-net/licensing/) täcker båda metoderna och den mätbaserade licensen.

## Next Steps

Efter att ha slutfört grunderna, utforska ytterligare resurser:
- [Developer Guide](https://docs.groupdocs.com/signature/python-net/developer-guide/): runnable examples for every signature type and operation.
- [Supported File Formats](https://docs.groupdocs.com/signature/python-net/supported-file-formats/): review the full list of supported file types.
- [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/): details on licensing and evaluation.
- [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/): solutions to common errors.
- [Technical Support](https://docs.groupdocs.com/signature/python-net/technical-support/): contact support if you run into issues.
