---
title: "Sök efter streckkod e‑signaturer"
linkTitle: "Barcodes"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Den här artikeln förklarar hur du söker efter streckkodselektroniska signaturer inom dokumentsidor med GroupDocs.Signature för Python via .NET API"
type: docs
url: /sv/python-net/guides/search-for-barcode-e-signatures/
is_root: false
weight: 100
---


[GroupDocs.Signature](https://products.groupdocs.com/signature/python-net) provides the ability to search for barcode signatures in documents. Barcode signatures can be used to store various types of information in a compact format.

## What is a Barcode Signature?

En streckkodssignatur är en visuell representation av data som kan skannas och läsas av maskiner. Den består vanligtvis av parallella svarta linjer och vita mellanrum med varierande bredd. Streckkoder används vanligtvis för:
- Product identification
- Inventory tracking
- Document verification
- Data encoding

## How to Search for Barcode Signatures

Klassen [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) tillhandahåller metoden [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) som låter dig söka efter streckkodssignaturer i dokument. Så här använder du den:

1. Skapa en ny instans av klassen [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) och skicka sökvägen till källdokumentet som en parameter.
2. Instansiera objektet [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) med de nödvändiga alternativen.
3. Anropa metoden [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) på instansen av klassen [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) och skicka en lista med [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) till den.
4. Bearbeta sökresultaten: egenskapen `signatures` i det returnerade [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult/) innehåller de hittade [BarcodeSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodesignature/)‑objekten.

Här är ett exempel på hur du söker efter streckkodssignaturer i ett dokument:

{{< tabs "search_barcodes" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes():
    with Signature("signed.pdf") as signature:
        # Sök igenom alla sidor i dokumentet efter streckkodssignaturer
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

`signed.pdf` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) för att ladda ner den.

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

Klassen [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) tillhandahåller egenskaper för att begränsa sökningen:

- `encode_type` returns only barcodes of the given type, for example `BarcodeTypes.CODE128`;
- `text` and `match_type` return only barcodes whose text matches;
- `all_pages` and `page_number` search a single page instead of the whole document (page numbers start at 1);
- `return_content` and `return_content_type` also return the barcode image.

{{< tabs "search_barcodes_with_filters" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes_with_filters():
    with Signature("signed.pdf") as signature:
        options = BarcodeSearchOptions()
        # Sök endast på den första sidan
        options.all_pages = False
        options.page_number = 1
        # Returnera endast Code 128-streckkoder vars text börjar med "1234"
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

`signed.pdf` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) för att ladda ner den.

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

Du kan enkelt köra koden ovan och se funktionen i praktiken i våra exempel:

* [GroupDocs.Signature for Python via .NET Examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)
* [GroupDocs.Signature for Python via .NET Plugins](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Plugins)
* [GroupDocs.Signature for Python via .NET Showcase Apps](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Showcase)

### Free Online Apps

Tillsammans med det fullständiga Python‑biblioteket erbjuder vi enkla men kraftfulla gratis‑appar.

Du är välkommen att söka efter streckkodssignaturer i dokument med våra gratis online‑appar:

* [Search for Barcode Signatures Online](https://products.groupdocs.app/signature/family)
