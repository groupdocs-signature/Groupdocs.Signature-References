---
title: "Schnellstart‑Leitfaden"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Richten Sie eine virtuelle Umgebung ein, installieren Sie groupdocs-signature-net und führen Sie drei Minimalbeispiele aus: Signieren Sie ein PDF mit einer Textsignatur, durchsuchen Sie es nach Signaturen und verifizieren Sie diese."
type: docs
url: /de/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Dieses Handbuch gibt einen kurzen Überblick darüber, wie man GroupDocs.Signature für Python via .NET einrichtet und verwendet. Die Bibliothek fügt elektronische Signaturen in PDF-, Word-, Excel-, PowerPoint-, OpenDocument- und Bilddateien hinzu, findet, verifiziert, aktualisiert und entfernt sie mit wenigen Codezeilen.

## Prerequisites

Um fortzufahren, stellen Sie sicher, dass Sie Folgendes haben:

1. Eine konfigurierte Umgebung, wie im Thema [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/) beschrieben. Unter Linux und macOS umfasst dies einige Systempakete.
2. Optional eine [Temporary License](https://purchase.groupdocs.com/temporary-license/), um alle Produktfunktionen zu testen. Ohne Lizenz arbeitet die Bibliothek im Evaluierungsmodus: Sie verarbeitet Dokumente von bis zu zwei Seiten und fügt jeder signierten Seite eine Evaluierungszeile hinzu. Siehe [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/).

## Set Up Your Development Environment

Für bewährte Vorgehensweisen verwenden Sie eine virtuelle Umgebung, um Abhängigkeiten zu verwalten. Erfahren Sie mehr im Leitfaden [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Erstellen Sie eine virtuelle Umgebung:

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

Aktivieren Sie sie:

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

Siehe [Installation](/signature/python-net/guides/installation/) zum Festlegen einer Version und zum Installieren ohne Zugriff auf PyPI.

## Example 1: Sign a PDF with a Text Signature

Öffnen Sie ein Dokument, beschreiben Sie die Signatur mit [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/), und speichern Sie die signierte Kopie.

{{< tabs \"sign_pdf_with_text_signature\">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Öffnen Sie das Dokument; der with-Block gibt die Datei frei, wenn er endet.
    with Signature("sample.pdf") as signature:
        # Eine Textsignatur 100 Pixel von den linken und oberen Rändern der ersten Seite entfernt.
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Signieren Sie und speichern Sie das Ergebnis in einer neuen Datei; die Quelle bleibt unverändert.
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")

if __name__ == "__main__":
    sign_pdf_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/sample.pdf) zum Herunterladen.

{{< /tab >}}
{{< tab \"signed_sample.pdf\" >}}
```text
Binary file (PDF, 125 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/sign_pdf_with_text_signature/signed_sample.pdf)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Search a Document for Signatures

Finden Sie die Signaturen, die ein Dokument bereits enthält. `search` nimmt eine Liste von Suchoptionen, jeweils eine pro zu suchendem Signaturtyp, und gibt sie in `result.signatures` zurück.

{{< tabs \"search_document_for_signatures\">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Suchen Sie nach Textsignaturen auf jeder Seite.
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) zum Herunterladen.

{{< /tab >}}
{{< tab \"search-document-signatures.txt\" >}}
```text
Text signature 'John Smith' on page 1
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/search_document_for_signatures/search-document-signatures.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Verify a Signature

Überprüfen Sie, ob ein Dokument die erwartete Signatur enthält. Die Verifizierung ist erfolgreich, wenn eine Textsignatur mit genau diesem Text gefunden wird.

{{< tabs \"verify_text_signature\">}}
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

`signed.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) zum Herunterladen.

{{< /tab >}}
{{< tab \"verify-text-signature.txt\" >}}
```text
Document is signed by John Smith: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/verify_text_signature/verify-text-signature.txt)
{{< /tab >}}
{{< /tabs >}}

## Run the Examples

Speichern Sie jedes Beispiel in einer eigenen `.py`‑Datei neben den Beispieldateien. Ihr Ordner sollte etwa so aussehen:

```Directory
📂 demo-app
 ├──sign_pdf_with_text_signature.py
 ├──search_document_for_signatures.py
 ├──verify_text_signature.py
 ├──sample.pdf
 └──signed.pdf
```

Führen Sie ein Beispiel aus diesem Ordner aus:

{{< tabs \"run-the-app\">}}
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

Wenn Sie fertig sind, deaktivieren Sie die virtuelle Umgebung, indem Sie `deactivate` ausführen oder Ihre Shell schließen.

## Apply a License

Setzen Sie die Umgebungsvariable `GROUPDOCS_LIC_PATH` auf den vollständigen Pfad Ihrer Lizenzdatei, und die Lizenz wird automatisch angewendet, wenn `groupdocs.signature` importiert wird. Es ist kein Code erforderlich. Alternativ können Sie sie einmal im Code anwenden, bevor irgendein anderer Aufruf erfolgt:

```python
from groupdocs.signature import License

License().set_license("/path/to/GroupDocs.Signature.lic")
```

Das Thema [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/) behandelt beide Methoden und die nutzungsbasierte Lizenz.

## Next Steps

Nachdem Sie die Grundlagen abgeschlossen haben, erkunden Sie weitere Ressourcen:
- [Developer Guide](https://docs.groupdocs.com/signature/python-net/developer-guide/): runnable examples for every signature type and operation.
- [Supported File Formats](https://docs.groupdocs.com/signature/python-net/supported-file-formats/): review the full list of supported file types.
- [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/): details on licensing and evaluation.
- [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/): solutions to common errors.
- [Technical Support](https://docs.groupdocs.com/signature/python-net/technical-support/): contact support if you run into issues.
