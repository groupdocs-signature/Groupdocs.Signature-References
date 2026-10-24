---
title: "Guida Rapida"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Configura un ambiente virtuale, installa groupdocs-signature-net e esegui tre esempi minimi: firma un PDF con una firma testuale, cercalo per firme e verificale."
type: docs
url: /it/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Questa guida fornisce una rapida panoramica su come configurare e iniziare a utilizzare GroupDocs.Signature per Python via .NET. La libreria aggiunge, trova, verifica, aggiorna e rimuove firme elettroniche in file PDF, Word, Excel, PowerPoint, OpenDocument e immagini con poche righe di codice.

## Prerequisites

Per procedere, assicurati di avere:

1. Un ambiente configurato come descritto nella sezione [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/). Su Linux e macOS ciò include alcuni pacchetti di sistema.
2. Facoltativamente, una [Temporary License](https://purchase.groupdocs.com/temporary-license/) per testare tutte le funzionalità del prodotto. Senza licenza la libreria funziona in modalità di valutazione: elabora documenti fino a due pagine e aggiunge una riga di valutazione a ogni pagina firmata. Vedi [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/).

## Set Up Your Development Environment

Per le migliori pratiche, utilizza un ambiente virtuale per gestire le dipendenze. Scopri di più nella guida [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Crea un ambiente virtuale:

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

Attivalo:

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

Vedi [Installation](/signature/python-net/guides/installation/) per fissare una versione e per installare senza accesso a PyPI.

## Example 1: Sign a PDF with a Text Signature

Apri un documento, descrivi la firma con [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/), e salva la copia firmata.

{{< tabs \"sign_pdf_with_text_signature\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Apri il documento; il with-block rilascia il file al termine
    with Signature("sample.pdf") as signature:
        # Una firma di testo a 100 pixel dal bordo sinistro e superiore della prima pagina
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Firma e salva il risultato in un nuovo file; l'origine rimane invariata
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")

if __name__ == "__main__":
    sign_pdf_with_text_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab \"signed_sample.pdf\" >}}
```text
Binary file (PDF, 125 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/sign_pdf_with_text_signature/signed_sample.pdf)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Search a Document for Signatures

Trova le firme che un documento contiene già. `search` accetta un elenco di opzioni di ricerca, una per tipo di firma da cercare, e le restituisce in `result.signatures`.

{{< tabs \"search_document_for_signatures\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Cerca firme di testo in ogni pagina
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) per scaricarlo.

{{< /tab >}}
{{< tab \"search-document-signatures.txt\" >}}
```text
Text signature 'John Smith' on page 1
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/search_document_for_signatures/search-document-signatures.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Verify a Signature

Verifica che un documento contenga la firma che ti aspetti. La verifica ha successo quando viene trovata una firma di testo con esattamente questo testo.

{{< tabs \"verify_text_signature\">}}
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
{{< tab \"signed.pdf\" >}}

`signed.pdf` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) per scaricarlo.

{{< /tab >}}
{{< tab \"verify-text-signature.txt\" >}}
```text
Document is signed by John Smith: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/verify_text_signature/verify-text-signature.txt)
{{< /tab >}}
{{< /tabs >}}

## Run the Examples

Salva ogni esempio nel proprio file `.py` accanto ai file di esempio. La tua cartella dovrebbe apparire simile a questa:

```Directory
📂 demo-app
 ├──sign_pdf_with_text_signature.py
 ├──search_document_for_signatures.py
 ├──verify_text_signature.py
 ├──sample.pdf
 └──signed.pdf
```

Esegui un esempio da quella cartella:

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

Quando hai finito, disattiva l'ambiente virtuale eseguendo `deactivate` o chiudendo il tuo terminale.

## Apply a License

Imposta la variabile d'ambiente `GROUPDOCS_LIC_PATH` al percorso completo del tuo file di licenza, e la licenza viene applicata automaticamente quando `groupdocs.signature` viene importato. Non è necessario alcun codice. In alternativa, applicala nel codice una volta, prima di qualsiasi altra chiamata:

```python
from groupdocs.signature import License

License().set_license("/path/to/GroupDocs.Signature.lic")
```

L'argomento [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/) copre entrambi i metodi e la licenza a consumo.

## Next Steps

Dopo aver completato le basi, esplora risorse aggiuntive:
- [Developer Guide](https://docs.groupdocs.com/signature/python-net/developer-guide/): runnable examples for every signature type and operation.
- [Supported File Formats](https://docs.groupdocs.com/signature/python-net/supported-file-formats/): review the full list of supported file types.
- [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/): details on licensing and evaluation.
- [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/): solutions to common errors.
- [Technical Support](https://docs.groupdocs.com/signature/python-net/technical-support/): contact support if you run into issues.
