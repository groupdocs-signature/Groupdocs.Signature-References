---
title: "Guía de inicio rápido"
linkTitle: "Quick Start Guide"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Configure un entorno virtual, instale groupdocs-signature-net y ejecute tres ejemplos mínimos: firme un PDF con una firma de texto, búsquelo para encontrar firmas y verifíquelas."
type: docs
url: /es/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Esta guía ofrece una visión rápida de cómo configurar y comenzar a usar GroupDocs.Signature for Python via .NET. La biblioteca agrega, encuentra, verifica, actualiza y elimina firmas electrónicas en archivos PDF, Word, Excel, PowerPoint, OpenDocument e imágenes con unas pocas líneas de código.

## Prerequisites

Para continuar, asegúrese de que tiene:

1. Un entorno configurado como se describe en el tema de [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/). En Linux y macOS esto incluye algunos paquetes del sistema.
2. Opcionalmente, una [Temporary License](https://purchase.groupdocs.com/temporary-license/) para probar todas las funciones del producto. Sin una licencia, la biblioteca funciona en modo de evaluación: procesa documentos de hasta dos páginas y agrega una línea de evaluación a cada página que firma. Consulte [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/).

## Set Up Your Development Environment

Para obtener mejores prácticas, use un entorno virtual para gestionar dependencias. Obtenga más información en la guía [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Cree un entorno virtual:

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

Actívelo:

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

Consulte [Installation](/signature/python-net/guides/installation/) para fijar una versión y para instalar sin acceso a PyPI.

## Example 1: Sign a PDF with a Text Signature

Abra un documento, describa la firma con [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/), y guarde la copia firmada.

{{< tabs \"sign_pdf_with_text_signature\">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Abra el documento; el bloque with libera el archivo cuando termina
    with Signature("sample.pdf") as signature:
        # Una firma de texto a 100 píxeles de los bordes izquierdo y superior de la primera página
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Firme y guarde el resultado en un archivo nuevo; el documento original permanece sin cambios
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")

if __name__ == "__main__":
    sign_pdf_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` es el archivo de ejemplo usado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab "signed_sample.pdf" >}}
```text
Binary file (PDF, 125 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/sign_pdf_with_text_signature/signed_sample.pdf)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Search a Document for Signatures

Encuentre las firmas que ya contiene un documento. `search` toma una lista de opciones de búsqueda, una por tipo de firma a buscar, y las devuelve en `result.signatures`.

{{< tabs "search_document_for_signatures">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Busque firmas de texto en cada página
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` es el archivo de ejemplo usado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) para descargarlo.

{{< /tab >}}
{{< tab "search-document-signatures.txt" >}}
```text
Text signature 'John Smith' on page 1
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/search_document_for_signatures/search-document-signatures.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Verify a Signature

Verifique que un documento contiene la firma que espera. La verificación tiene éxito cuando se encuentra una firma de texto con exactamente este texto.

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

`signed.pdf` es el archivo de ejemplo usado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) para descargarlo.

{{< /tab >}}
{{< tab "verify-text-signature.txt" >}}
```text
Document is signed by John Smith: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/verify_text_signature/verify-text-signature.txt)
{{< /tab >}}
{{< /tabs >}}

## Run the Examples

Guarde cada ejemplo en su propio archivo `.py` junto a los archivos de ejemplo. Su carpeta debería verse similar a esta:

```Directory
📂 demo-app
 ├──sign_pdf_with_text_signature.py
 ├──search_document_for_signatures.py
 ├──verify_text_signature.py
 ├──sample.pdf
 └──signed.pdf
```

Ejecute un ejemplo desde esa carpeta:

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

Cuando haya terminado, desactive el entorno virtual ejecutando `deactivate` o cerrando su terminal.

## Apply a License

Establezca la variable de entorno `GROUPDOCS_LIC_PATH` con la ruta completa de su archivo de licencia, y la licencia se aplicará automáticamente cuando se importe `groupdocs.signature`. No se necesita código. Alternativamente, aplíquela en código una vez, antes de cualquier otra llamada:

```python
from groupdocs.signature import License

License().set_license("/path/to/GroupDocs.Signature.lic")
```

El tema [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/) cubre ambas formas y la licencia por consumo.

## Next Steps

Después de completar lo básico, explore recursos adicionales:
- [Developer Guide](https://docs.groupdocs.com/signature/python-net/developer-guide/): runnable examples for every signature type and operation.
- [Supported File Formats](https://docs.groupdocs.com/signature/python-net/supported-file-formats/): review the full list of supported file types.
- [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/): details on licensing and evaluation.
- [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/): solutions to common errors.
- [Technical Support](https://docs.groupdocs.com/signature/python-net/technical-support/): contact support if you run into issues.
