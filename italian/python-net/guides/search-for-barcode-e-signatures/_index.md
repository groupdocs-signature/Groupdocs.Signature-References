---
title: "Cerca Barcode e-Signatures"
linkTitle: "Barcodes"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Questo articolo spiega come cercare firme elettroniche a barcode all'interno delle pagine dei documenti utilizzando GroupDocs.Signature per Python tramite API .NET"
type: docs
url: /it/python-net/guides/search-for-barcode-e-signatures/
is_root: false
weight: 100
---


[GroupDocs.Signature](https://products.groupdocs.com/signature/python-net) provides the ability to search for barcode signatures in documents. Barcode signatures can be used to store various types of information in a compact format.

## What is a Barcode Signature?

Una firma a barcode è una rappresentazione visiva dei dati che può essere scansionata e letta dalle macchine. Tipicamente consiste in linee nere parallele e spazi bianchi di larghezze variabili. I barcode sono comunemente usati per:
- Product identification
- Inventory tracking
- Document verification
- Data encoding

## How to Search for Barcode Signatures

La classe [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) fornisce il metodo [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) che consente di cercare firme a barcode nei documenti. Ecco come usarlo:

1. Crea una nuova istanza della classe [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) e passa il percorso del documento di origine come parametro.
2. Istanzia l'oggetto [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) con le opzioni richieste.
3. Chiama il metodo [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) dell'istanza della classe [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) e passa una lista con il [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) ad esso.
4. Elabora i risultati della ricerca: la proprietà `signatures` del [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult/) restituito contiene gli oggetti [BarcodeSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodesignature/) trovati.

Ecco un esempio di come cercare firme a barcode in un documento:

{{< tabs \"search_barcodes\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes():
    with Signature("signed.pdf") as signature:
        # Cerca tutte le pagine del documento per firme a barcode
        result = signature.search([BarcodeSearchOptions()])

        print(f"Found {len(result.signatures)} barcode signature(s)")
        for barcode in result.signatures:
            print(f"Page {barcode.page_number}: {barcode.encode_type.type_name} barcode '{barcode.text}' "
                  f"at ({barcode.left}, {barcode.top}), size {barcode.width}x{barcode.height}")

if __name__ == "__main__":
    search_barcodes()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) per scaricarlo.

{{< /tab >}}
{{< tab \"search-barcodes.txt\" >}}
```text
Found 2 barcode signature(s)
Page 1: Code128 barcode '123456789012' at (400, 375), size 170x45
Page 1: Code39 barcode 'JS-2026' at (400, 430), size 170x45
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/search_barcodes/search-barcodes.txt)
{{< /tab >}}
{{< /tabs >}}

## Advanced Search Options

La classe [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) fornisce proprietà per restringere la ricerca:

- `encode_type` returns only barcodes of the given type, for example `BarcodeTypes.CODE128`;
- `text` and `match_type` return only barcodes whose text matches;
- `all_pages` and `page_number` search a single page instead of the whole document (page numbers start at 1);
- `return_content` and `return_content_type` also return the barcode image.

{{< tabs \"search_barcodes_with_filters\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes_with_filters():
    with Signature("signed.pdf") as signature:
        options = BarcodeSearchOptions()
        # Cerca solo la prima pagina
        options.all_pages = False
        options.page_number = 1
        # Restituisci solo i barcode Code 128 il cui testo inizia con \"1234\"
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
{{< tab \"signed.pdf\" >}}

`signed.pdf` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) per scaricarlo.

{{< /tab >}}
{{< tab \"search-barcodes-with-filters.txt\" >}}
```text
Found 1 matching barcode signature(s)
Page 1: Code128 barcode '123456789012'
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/search_barcodes_with_filters/search-barcodes-with-filters.txt)
{{< /tab >}}
{{< /tabs >}}

## Additional Resources

### GitHub Examples

Puoi facilmente eseguire il codice sopra e vedere la funzionalità in azione nei nostri esempi:

* [GroupDocs.Signature for Python via .NET Examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)
* [GroupDocs.Signature for Python via .NET Plugins](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Plugins)
* [GroupDocs.Signature for Python via .NET Showcase Apps](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Showcase)

### Free Online Apps

Insieme alla libreria completa Python forniamo app gratuite semplici ma potenti.

Sei invitato a cercare firme a barcode nei documenti con le nostre app online gratuite:

* [Search for Barcode Signatures Online](https://products.groupdocs.app/signature/family)
