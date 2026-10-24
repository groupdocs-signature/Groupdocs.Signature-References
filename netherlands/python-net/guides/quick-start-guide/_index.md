---
title: "Snelstartgids"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Stel een virtuele omgeving in, installeer groupdocs-signature-net, en voer drie minimale voorbeelden uit: onderteken een PDF met een teksthandtekening, zoek ernaar voor handtekeningen, en verifieer ze."
type: docs
url: /nl/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Deze gids geeft een snel overzicht van hoe je GroupDocs.Signature for Python via .NET instelt en gaat gebruiken. De bibliotheek voegt elektronische handtekeningen toe, vindt, verifieert, werkt bij en verwijdert ze in PDF-, Word-, Excel-, PowerPoint-, OpenDocument- en afbeeldingsbestanden met slechts een paar regels code.

## Prerequisites

Ga verder door ervoor te zorgen dat je het volgende hebt:

1. Een geconfigureerde omgeving zoals beschreven in het onderwerp [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/). Op Linux en macOS omvat dit een paar systeempakketten.
2. Optioneel een [Temporary License](https://purchase.groupdocs.com/temporary-license/) om alle productfuncties te testen. Zonder licentie werkt de bibliotheek in evaluatiemodus: hij verwerkt documenten van maximaal twee pagina's en voegt een evaluatielijn toe aan elke pagina die hij ondertekent. Zie [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/).

## Set Up Your Development Environment

Voor de beste praktijken, gebruik een virtuele omgeving om afhankelijkheden te beheren. Lees meer in de gids [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Maak een virtuele omgeving:

{{< tabs "create-venv">}}
{{< tab "Windows" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

Activeer deze:

{{< tabs "activate-venv">}}
{{< tab "Windows" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install the `groupdocs-signature-net` Package

{{< tabs "install-package">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< /tabs >}}

Zie [Installation](/signature/python-net/guides/installation/) voor het vastzetten van een versie en voor installatie zonder toegang tot PyPI.

## Example 1: Sign a PDF with a Text Signature

Open een document, beschrijf de handtekening met [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/), en sla de ondertekende kopie op.

{{< tabs "sign_pdf_with_text_signature">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Open het document; het with-blok geeft het bestand vrij wanneer het eindigt
    with Signature("sample.pdf") as signature:
        # Een teksthandtekening 100 pixels vanaf de linker- en bovenrand van de eerste pagina
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Onderteken en sla het resultaat op in een nieuw bestand; de bron blijft ongewijzigd
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")

if __name__ == "__main__":
    sign_pdf_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "signed_sample.pdf" >}}
```text
Binary file (PDF, 125 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/sign_pdf_with_text_signature/signed_sample.pdf)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Search a Document for Signatures

Zoek de handtekeningen die een document al bevat. `search` neemt een lijst met zoekopties, één per handtekeningtype om naar te zoeken, en retourneert ze in `result.signatures`.

{{< tabs "search_document_for_signatures">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Zoek naar teksthandtekeningen op elke pagina
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "search-document-signatures.txt" >}}
```text
Text signature 'John Smith' on page 1
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/search_document_for_signatures/search-document-signatures.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Verify a Signature

Controleer of een document de verwachte handtekening bevat. Verificatie slaagt wanneer een teksthandtekening met precies deze tekst wordt gevonden.

{{< tabs "verify_text_signature">}}
{{< tab "Python" >}}
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

`signed.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "verify-text-signature.txt" >}}
```text
Document is signed by John Smith: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/verify_text_signature/verify-text-signature.txt)
{{< /tab >}}
{{< /tabs >}}

## Run the Examples

Sla elk voorbeeld op in een eigen `.py`-bestand naast de voorbeeldbestanden. Uw map zou er ongeveer zo uit moeten zien:

```Directory
📂 demo-app
 ├──sign_pdf_with_text_signature.py
 ├──search_document_for_signatures.py
 ├──verify_text_signature.py
 ├──sample.pdf
 └──signed.pdf
```

Voer een voorbeeld uit die map:

{{< tabs "run-the-app">}}
{{< tab "Windows" >}}
```ps
py sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< /tabs >}}

Wanneer u klaar bent, deactiveer dan de virtuele omgeving door `deactivate` uit te voeren of uw shell te sluiten.

## Apply a License

Stel de omgevingsvariabele `GROUPDOCS_LIC_PATH` in op het volledige pad van uw licentiebestand, en de licentie wordt automatisch toegepast wanneer `groupdocs.signature` wordt geïmporteerd. Er is geen code nodig. U kunt het ook in code toepassen, één keer, vóór elke andere aanroep:

```python
from groupdocs.signature import License

License().set_license("/path/to/GroupDocs.Signature.lic")
```

Het onderwerp [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/) behandelt beide methoden en de meter‑licentie.

## Next Steps

Na het voltooien van de basis, verken aanvullende bronnen:
- [Developer Guide](https://docs.groupdocs.com/signature/python-net/developer-guide/): runnable examples for every signature type and operation.
- [Supported File Formats](https://docs.groupdocs.com/signature/python-net/supported-file-formats/): review the full list of supported file types.
- [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/): details on licensing and evaluation.
- [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/): solutions to common errors.
- [Technical Support](https://docs.groupdocs.com/signature/python-net/technical-support/): contact support if you run into issues.
