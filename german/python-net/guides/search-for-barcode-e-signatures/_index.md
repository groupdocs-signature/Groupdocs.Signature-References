---
title: "Suche nach Barcode‑e‑Signaturen"
linkTitle: "Barcodes"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Dieser Artikel erklärt, wie man nach barcode‑elektronischen Signaturen in Dokumentseiten sucht, wobei GroupDocs.Signature für Python über die .NET‑API verwendet wird."
type: docs
url: /de/python-net/guides/search-for-barcode-e-signatures/
is_root: false
weight: 100
---


[GroupDocs.Signature](https://products.groupdocs.com/signature/python-net) provides the ability to search for barcode signatures in documents. Barcode signatures can be used to store various types of information in a compact format.

## What is a Barcode Signature?

Eine Barcode‑Signatur ist eine visuelle Darstellung von Daten, die von Maschinen gescannt und gelesen werden kann. Sie besteht typischerweise aus parallelen schwarzen Linien und weißen Zwischenräumen unterschiedlicher Breite. Barcodes werden häufig verwendet für:
- Product identification
- Inventory tracking
- Document verification
- Data encoding

## How to Search for Barcode Signatures

Die Klasse [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) stellt die Methode [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) bereit, mit der Sie nach Barcode‑Signaturen in Dokumenten suchen können. So verwenden Sie sie:

1. Erstellen Sie eine neue Instanz der Klasse [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/), und übergeben Sie den Pfad zur Quelldatei als Parameter.
2. Instanziieren Sie das Objekt [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) mit den erforderlichen Optionen.
3. Rufen Sie die Methode [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) der Instanz der Klasse [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) auf und übergeben Sie ihr eine Liste mit den [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/).
4. Verarbeiten Sie die Suchergebnisse: Die Eigenschaft `signatures` des zurückgegebenen [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult/) enthält die gefundenen [BarcodeSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodesignature/)-Objekte.

Hier ein Beispiel, wie man in einem Dokument nach Barcode‑Signaturen sucht:

{{< tabs "search_barcodes" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes():
    with Signature("signed.pdf") as signature:
        # Durchsuchen Sie alle Seiten des Dokuments nach Barcode‑Signaturen
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

`signed.pdf` ist die in diesem Beispiel verwendete Beispieldatei. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf), um sie herunterzuladen.

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

Die Klasse [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) stellt Eigenschaften bereit, um die Suche einzugrenzen:

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
        # Nur die erste Seite durchsuchen
        options.all_pages = False
        options.page_number = 1
        # Nur Code‑128‑Barcodes zurückgeben, deren Text mit \"1234\" beginnt
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

`signed.pdf` ist die in diesem Beispiel verwendete Beispieldatei. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf), um sie herunterzuladen.

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

Sie können den obigen Code ganz einfach ausführen und die Funktion in Aktion in unseren Beispielen sehen:

* [GroupDocs.Signature for Python via .NET Examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)
* [GroupDocs.Signature for Python via .NET Plugins](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Plugins)
* [GroupDocs.Signature for Python via .NET Showcase Apps](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Showcase)

### Free Online Apps

Zusammen mit der vollständigen Python-Bibliothek stellen wir einfache, aber leistungsstarke kostenlose Apps bereit.

Sie können nach Barcode-Signaturen in Dokumenten mit unseren kostenlosen Online-Apps suchen:

* [Search for Barcode Signatures Online](https://products.groupdocs.app/signature/family)
