---
title: "Zoek naar Barcode e-Handtekeningen"
linkTitle: "Barcodes"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Dit artikel legt uit hoe u barcode-elektronische handtekeningen binnen documentpagina's kunt zoeken met GroupDocs.Signature voor Python via .NET API"
type: docs
url: /nl/python-net/guides/search-for-barcode-e-signatures/
is_root: false
weight: 100
---


[GroupDocs.Signature](https://products.groupdocs.com/signature/python-net) provides the ability to search for barcode signatures in documents. Barcode signatures can be used to store various types of information in a compact format.

## What is a Barcode Signature?

Een barcodehandtekening is een visuele weergave van gegevens die door machines kan worden gescand en gelezen. Het bestaat doorgaans uit parallelle zwarte lijnen en witte ruimtes met verschillende breedtes. Barcodes worden meestal gebruikt voor:
- Product identification
- Inventory tracking
- Document verification
- Data encoding

## How to Search for Barcode Signatures

De [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) klasse biedt de [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) methode die u in staat stelt barcodehandtekeningen in documenten te zoeken. Hier leest u hoe u deze gebruikt:

1. Maak een nieuw exemplaar van de [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) klasse aan en geef het pad naar het brondocument als parameter door.
2. Instantieer het [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) object met de vereiste opties.
3. Roep de [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) methode van de [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) klasse‑instantie aan en geef een lijst met de [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) door.
4. Verwerk de zoekresultaten: de `signatures`‑eigenschap van het geretourneerde [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult/) bevat de gevonden [BarcodeSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodesignature/) objecten.

Hier is een voorbeeld van hoe u barcodehandtekeningen in een document kunt zoeken:

{{< tabs "search_barcodes" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes():
    with Signature("signed.pdf") as signature:
        # Zoek op alle pagina's van het document naar barcodehandtekeningen
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

`signed.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik op [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) om het te downloaden.

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

De [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) klasse biedt eigenschappen om de zoekopdracht te verfijnen:

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
        # Zoek alleen de eerste pagina
        options.all_pages = False
        options.page_number = 1
        # Geef alleen Code 128 barcodes terug waarvan de tekst begint met "1234"
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

`signed.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik op [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) om het te downloaden.

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

U kunt de bovenstaande code eenvoudig uitvoeren en de functie in actie zien in onze voorbeelden:

* [GroupDocs.Signature for Python via .NET Examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)
* [GroupDocs.Signature for Python via .NET Plugins](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Plugins)
* [GroupDocs.Signature for Python via .NET Showcase Apps](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Showcase)

### Free Online Apps

Samen met de volledige Python‑bibliotheek bieden we eenvoudige maar krachtige gratis apps.

U bent welkom om barcodehandtekeningen in documenten te zoeken met onze gratis online apps:

* [Search for Barcode Signatures Online](https://products.groupdocs.app/signature/family)
