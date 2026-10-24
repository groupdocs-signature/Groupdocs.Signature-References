---
title: "Buscar firmas electrónicas de códigos de barras"
linkTitle: "Barcodes"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Este artículo explica cómo buscar firmas electrónicas de códigos de barras dentro de las páginas de documentos usando GroupDocs.Signature para Python a través de la API .NET"
type: docs
url: /es/python-net/guides/search-for-barcode-e-signatures/
is_root: false
weight: 100
---


[GroupDocs.Signature](https://products.groupdocs.com/signature/python-net) provides the ability to search for barcode signatures in documents. Barcode signatures can be used to store various types of information in a compact format.

## What is a Barcode Signature?

Una firma de código de barras es una representación visual de datos que puede ser escaneada y leída por máquinas. Normalmente consiste en líneas negras paralelas y espacios blancos de diferentes anchuras. Los códigos de barras se utilizan comúnmente para:
- Product identification
- Inventory tracking
- Document verification
- Data encoding

## How to Search for Barcode Signatures

La clase [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) proporciona el método [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) que le permite buscar firmas de códigos de barras en documentos. He aquí cómo usarlo:

1. Cree una nueva instancia de la clase [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) y pase la ruta del documento fuente como parámetro.
2. Instancie el objeto [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) con las opciones requeridas.
3. Llame al método [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) de la instancia de la clase [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) y pase una lista con los [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) a ella.
4. Procese los resultados de la búsqueda: la propiedad `signatures` del [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult/) devuelto contiene los objetos [BarcodeSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodesignature/) encontrados.

He aquí un ejemplo de cómo buscar firmas de códigos de barras en un documento:

{{< tabs "search_barcodes" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes():
    with Signature("signed.pdf") as signature:
        # Buscar firmas de códigos de barras en todas las páginas del documento
        result = signature.search([BarcodeSearchOptions()])

        print(f"Found {len(result.signatures)} barcode signature(s)")
        for barcode in result.signatures:
            print(f"Page {barcode.page_number}: {barcode.encode_type.type_name} barcode '{barcode.text}' "
                  f"at ({barcode.left}, {barcode.top}), size {barcode.width}x{barcode.height}")

if __name__ == "__main__":
    search_barcodes()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` es el archivo de ejemplo usado en este caso. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) para descargarlo.

{{< /tab >}}
{{< tab "search-barcodes.txt" >}}
```text
Found 2 barcode signature(s)
Page 1: Code128 barcode '123456789012' at (400, 375), size 170x45
Page 1: Code39 barcode 'JS-2026' at (400, 430), size 170x45
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/search_barcodes/search-barcodes.txt)
{{< /tab >}}
{{< /tabs >}}

## Advanced Search Options

La clase [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) proporciona propiedades para acotar la búsqueda:

- `encode_type` returns only barcodes of the given type, for example `BarcodeTypes.CODE128`;
- `text` and `match_type` return only barcodes whose text matches;
- `all_pages` and `page_number` search a single page instead of the whole document (page numbers start at 1);
- `return_content` and `return_content_type` also return the barcode image.

{{< tabs "search_barcodes_with_filters" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes_with_filters():
    with Signature("signed.pdf") as signature:
        options = BarcodeSearchOptions()
        # Buscar solo en la primera página
        options.all_pages = False
        options.page_number = 1
        # Devolver solo códigos de barras Code 128 cuyo texto comience con "1234"
        options.encode_type = BarcodeTypes.CODE128
        options.text = "1234"
        options.match_type = TextMatchType.STARTS_WITH

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching barcode signature(s)")
        for barcode in result.signatures:
            print(f"Page {barcode.page_number}: {barcode.encode_type.type_name} barcode '{barcode.text}'")

if __name__ == "__main__":
    search_barcodes_with_filters()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` es el archivo de ejemplo usado en este caso. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) para descargarlo.

{{< /tab >}}
{{< tab "search-barcodes-with-filters.txt" >}}
```text
Found 1 matching barcode signature(s)
Page 1: Code128 barcode '123456789012'
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/search_barcodes_with_filters/search-barcodes-with-filters.txt)
{{< /tab >}}
{{< /tabs >}}

## Additional Resources

### GitHub Examples

Puede ejecutar fácilmente el código anterior y ver la función en acción en nuestros ejemplos:

* [GroupDocs.Signature for Python via .NET Examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)
* [GroupDocs.Signature for Python via .NET Plugins](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Plugins)
* [GroupDocs.Signature for Python via .NET Showcase Apps](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Showcase)

### Free Online Apps

Junto con la biblioteca completa de Python, ofrecemos aplicaciones gratuitas simples pero potentes.

Le invitamos a buscar firmas de códigos de barras en documentos con nuestras aplicaciones en línea gratuitas:

* [Search for Barcode Signatures Online](https://products.groupdocs.app/signature/family)
