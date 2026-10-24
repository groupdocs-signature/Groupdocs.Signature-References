---
title: "ImageSearchOptions‑klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar sökalternativ för bildsignaturer."
type: docs
url: /sv/python-net/groupdocs.signature.options/imagesearchoptions/
is_root: false
weight: 240
---


## ImageSearchOptions class

Representerar sökalternativ för bildsignaturer.

Läs mer:
- Basic usage of search for Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures
- Advanced usage of settings of search for Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures

ImageSearchOptions‑typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesearchoptions/__init__/) | Initierar en ny instans av ImageSearchOptions‑klassen med standardvärden. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [max_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/max_content_size/) | Den maximala storleken på bilder för sökkriterierna, i byte. |
| [min_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/min_content_size/) | Den minsta storleken på bilddata, i byte, som ska beaktas under en sökning. Ett icke‑nollvärde anger den minsta storleken; standardvärdet är noll, vilket inte påverkar sökresultatet. |
| [return_content](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content/) | Flaggan som bestämmer om bildinnehållet för en signatur returneras. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/) | Filtypen för det returnerade bildinnehållet när egenskapen `return_content` är aktiverad. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Flaggan som anger om varje dokumentsida ska genomsökas. Standardvärdet är True. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Dokumentsidans nummer för sökning (valfritt). (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Alternativen för att ange sidor för signatursökning. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Flaggan som anger om formens position i dokumentlayouten ska returneras. Endast tillgänglig för Word‑dokument. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Flaggan för att endast returnera signaturer markerade som `IsSignature`. Standardvärdet är `False`, vilket innebär att alla signaturer som matchar de angivna kriterierna returneras. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Exempel

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

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
