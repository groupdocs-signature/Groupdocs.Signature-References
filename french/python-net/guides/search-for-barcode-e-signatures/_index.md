---
title: "Rechercher des e‑signatures de codes-barres"
linkTitle: "Barcodes"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Cet article explique comment rechercher des signatures électroniques de code-barres dans les pages de documents en utilisant GroupDocs.Signature pour Python via l'API .NET"
type: docs
url: /fr/python-net/guides/search-for-barcode-e-signatures/
is_root: false
weight: 100
---


[GroupDocs.Signature](https://products.groupdocs.com/signature/python-net) provides the ability to search for barcode signatures in documents. Barcode signatures can be used to store various types of information in a compact format.

## What is a Barcode Signature?

Une signature de code-barres est une représentation visuelle de données qui peut être scannée et lue par des machines. Elle se compose généralement de lignes noires parallèles et d'espaces blancs de largeurs variables. Les codes-barres sont couramment utilisés pour :
- Product identification
- Inventory tracking
- Document verification
- Data encoding

## How to Search for Barcode Signatures

La classe [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) fournit la méthode [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) qui vous permet de rechercher des signatures de code-barres dans les documents. Voici comment l’utiliser :

1. Créez une nouvelle instance de la classe [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) et transmettez le chemin du document source en paramètre.
2. Instanciez l’objet [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) avec les options requises.
3. Appelez la méthode [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) de l’instance de la classe [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) et transmettez‑lui une liste contenant les [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/).
4. Traitez les résultats de la recherche : la propriété `signatures` du [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult/) retourné contient les objets [BarcodeSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodesignature/) trouvés.

Voici un exemple de recherche de signatures de code-barres dans un document :

{{< tabs "search_barcodes" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes():
    with Signature("signed.pdf") as signature:
        # Rechercher les signatures de code-barres sur toutes les pages du document
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

`signed.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) pour le télécharger.

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

La classe [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) fournit des propriétés pour affiner la recherche :

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
        # Rechercher uniquement la première page
        options.all_pages = False
        options.page_number = 1
        # Ne retourner que les codes-barres Code 128 dont le texte commence par "1234"
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

`signed.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) pour le télécharger.

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

Vous pouvez facilement exécuter le code ci‑dessus et voir la fonctionnalité en action dans nos exemples :

* [GroupDocs.Signature for Python via .NET Examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)
* [GroupDocs.Signature for Python via .NET Plugins](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Plugins)
* [GroupDocs.Signature for Python via .NET Showcase Apps](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Showcase)

### Free Online Apps

Avec la bibliothèque Python complète, nous fournissons des applications gratuites simples mais puissantes.

Vous êtes invités à rechercher des signatures de code-barres dans les documents avec nos applications en ligne gratuites :

* [Search for Barcode Signatures Online](https://products.groupdocs.app/signature/family)
