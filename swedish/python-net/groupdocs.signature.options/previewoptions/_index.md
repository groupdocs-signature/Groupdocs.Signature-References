---
title: "PreviewOptions-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar förhandsgranskningsalternativ för dokument."
type: docs
url: /sv/python-net/groupdocs.signature.options/previewoptions/
is_root: false
weight: 430
---


## PreviewOptions class

Representerar förhandsgranskningsalternativ för dokument.

Typen PreviewOptions visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-resolution-page_numbers) |  |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-release_page_stream-resolution-page_numbers) |  |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/previewoptions/height/) | Höjden på förhandsgranskningsbilderna. |
| [hide_signatures](/signature/python-net/groupdocs.signature.options/previewoptions/hide_signatures/) | Flaggan som indikerar om signaturer är dolda i förhandsgranskningsbilder för sidan. |
| [page_numbers](/signature/python-net/groupdocs.signature.options/previewoptions/page_numbers/) | Sidnumren för förhandsgranskningsbilderna. |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewoptions/preview_format/) | Formatet för förhandsgranskningsbilderna. |
| [resolution](/signature/python-net/groupdocs.signature.options/previewoptions/resolution/) | Upplösningen för förhandsgranskningsbilderna i DPI (dots per inch). Standardupplösningen är 96 DPI. |
| [width](/signature/python-net/groupdocs.signature.options/previewoptions/width/) | Bredden på förhandsgranskningsbilden. |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

with Signature("sample.pdf") as signature:
    preview_options = PreviewOptions(create_page_stream)
    preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
    signature.generate_preview(preview_options)
```

### Guides
Uppgiftsguider som använder `PreviewOptions`:

* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
