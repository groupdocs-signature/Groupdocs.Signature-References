---
title: "ImageSearchOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Vertegenwoordigt zoekopties voor afbeeldingshandtekeningen."
type: docs
url: /nl/python-net/groupdocs.signature.options/imagesearchoptions/
is_root: false
weight: 240
---


## ImageSearchOptions class

Vertegenwoordigt zoekopties voor afbeeldingshandtekeningen.

Meer informatie:
- Basic usage of search for Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures
- Advanced usage of settings of search for Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures

Het ImageSearchOptions‑type bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesearchoptions/__init__/) | Initialiseert een nieuw exemplaar van de ImageSearchOptions‑klasse met standaardwaarden. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [max_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/max_content_size/) | De maximale grootte van afbeeldingen voor de zoekcriteria, in bytes. |
| [min_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/min_content_size/) | De minimale grootte van afbeeldingsgegevens, in bytes, die tijdens een zoekopdracht in aanmerking wordt genomen. Een niet‑nulwaarde geeft de minimale grootte aan; de standaard is nul, wat geen effect heeft op het zoekresultaat. |
| [return_content](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content/) | De vlag die bepaalt of de afbeeldingsinhoud van een handtekening wordt geretourneerd. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/) | Het bestandstype van de geretourneerde afbeeldingsinhoud wanneer de eigenschap `return_content` is ingeschakeld. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | De vlag die aangeeft of er op elke documentpagina moet worden gezocht. Standaard is deze waarde True. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Het paginanummer van het document voor zoeken (optioneel). (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | De opties om pagina's op te geven voor handtekeningzoeken. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | De vlag die aangeeft of de vormpositie in de documentlay-out moet worden geretourneerd. Alleen beschikbaar voor Word‑documenten. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | De vlag om alleen handtekeningen die gemarkeerd zijn als `IsSignature` te retourneren. Standaard is de waarde `False`, wat aangeeft dat alle handtekeningen die aan de opgegeven criteria voldoen, worden geretourneerd. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSearchOptions

def extract_image_signatures():
    with Signature("signed.pdf") as signature:
        options = ImageSearchOptions()
        options.all_pages = False          # search the first page only
        options.page_number = 1
        options.min_content_size = 1024   # skip images smaller than 1 KB
        options.return_content = True
        options.return_content_type = FileType.PNG

        result = signature.search([options])
        for i, image in enumerate(result.signatures, start=1):
            file_name = f"image_signature_{i}.png"
            with open(file_name, "wb") as out:
                out.write(image.content)
```

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
