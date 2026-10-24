---
title: "Zoeken naar Tekst‑e‑handtekeningen"
linkTitle: "Texts"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Dit onderwerp legt uit hoe u kunt zoeken naar tekst‑elektronische handtekeningen binnen documentpagina's met GroupDocs.Signature voor Python via .NET API."
type: docs
url: /nl/python-net/guides/search-for-text-e-signatures/
is_root: false
weight: 90
---


[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [TextSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsearchoptions) class to specify different options for searching Text electronic signatures within documents.

Hier zijn de stappen om te zoeken naar Tekst‑e‑handtekeningen met de GroupDocs.Signature API:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsearchoptions) object according to your requirements and specify additional search options (if needed).
* Call the [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass a list with the [TextSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsearchoptions) to it. The `signatures` property of the returned [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult) holds the found [TextSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/textsignature) objects.

Dit voorbeeld toont hoe u kunt zoeken naar Tekst‑e‑handtekeningen in een document met Python. De eigenschap `signature_implementation` van elke handtekening geeft aan hoe deze aan het document is toegevoegd: als paginainhoud (`NATIVE`), een annotatie, een formulierveld, enzovoort.

{{< tabs "search_text" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_text():
    with Signature("signed.pdf") as signature:
        result = signature.search([TextSearchOptions()])

        print(f"Found {len(result.signatures)} text signature(s)")
        for text_signature in result.signatures:
            print(f"{text_signature.signature_implementation.name} text signature '{text_signature.text}' "
                  f"on page {text_signature.page_number} at ({text_signature.left}, {text_signature.top}), "
                  f"size {text_signature.width}x{text_signature.height}")

if __name__ == "__main__":
    search_text()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/signed.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "search-text.txt" >}}
```text
Found 3 text signature(s)
ANNOTATION text signature 'Approved' on page 1 at (50, 480), size 90x22
FORM_FIELD text signature 'John Smith' on page 1 at (50, 530), size 190x22
NATIVE text signature 'John Smith' on page 1 at (50, 379), size 189x30
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/search_text/search-text.txt)
{{< /tab >}}
{{< /tabs >}}

### Advanced Search Options

Hier is een voorbeeld dat laat zien hoe u meer geavanceerde zoekopties kunt gebruiken: een te doorzoeken pagina, de tekst om te vergelijken met zijn [TextMatchType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/textmatchtype), en de [TextSignatureImplementation](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/textsignatureimplementation) om naar te zoeken.

{{< tabs "search_text_with_filters" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType, TextSignatureImplementation
from groupdocs.signature.options import TextSearchOptions

def search_text_with_filters():
    with Signature("signed.pdf") as signature:
        options = TextSearchOptions()
        # Zoek alleen de eerste pagina (paginanummers beginnen bij 1)
        options.all_pages = False
        options.page_number = 1
        # Geef alleen tekstoptekeningen terug die "John" bevatten...
        options.text = "John"
        options.match_type = TextMatchType.CONTAINS
        # ...en deel uitmaken van de paginainhoud
        options.signature_implementation = TextSignatureImplementation.NATIVE

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching text signature(s)")
        for text_signature in result.signatures:
            print(f"'{text_signature.text}' on page {text_signature.page_number} "
                  f"at ({text_signature.left}, {text_signature.top}), "
                  f"size {text_signature.width}x{text_signature.height}")

if __name__ == "__main__":
    search_text_with_filters()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/signed.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "search-text-with-filters.txt" >}}
```text
Found 1 matching text signature(s)
'John Smith' on page 1 at (50, 379), size 189x30
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/search_text_with_filters/search-text-with-filters.txt)
{{< /tab >}}
{{< /tabs >}}

## More Resources

### GitHub Examples

U kunt de bovenstaande code eenvoudig uitvoeren en de functie in actie zien in onze GitHub-voorbeelden:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Naast de volledig uitgeruste Python-bibliotheek bieden we eenvoudige maar krachtige gratis online apps.

Om PDF, Word, Excel, PowerPoint en andere documenten te ondertekenen, kun je de online apps van de **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** gebruiken.
