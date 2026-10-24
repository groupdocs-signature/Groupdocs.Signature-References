---
title: "PreviewOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Vertegenwoordigt documentvoorbeeldopties."
type: docs
url: /nl/python-net/groupdocs.signature.options/previewoptions/
is_root: false
weight: 430
---


## PreviewOptions class

Vertegenwoordigt documentvoorbeeldopties.

Het PreviewOptions type exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-resolution-page_numbers) |  |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-release_page_stream-resolution-page_numbers) |  |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/previewoptions/height/) | De hoogte van de voorbeeldafbeeldingen. |
| [hide_signatures](/signature/python-net/groupdocs.signature.options/previewoptions/hide_signatures/) | De vlag die aangeeft of handtekeningen verborgen zijn in voorbeeldafbeeldingen van pagina's. |
| [page_numbers](/signature/python-net/groupdocs.signature.options/previewoptions/page_numbers/) | De paginanummers van de voorbeeldafbeeldingen. |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewoptions/preview_format/) | Het formaat van de voorbeeldafbeeldingen. |
| [resolution](/signature/python-net/groupdocs.signature.options/previewoptions/resolution/) | De resolutie van de voorbeeldafbeeldingen in DPI (dots per inch). De standaardresolutie is 96 DPI. |
| [width](/signature/python-net/groupdocs.signature.options/previewoptions/width/) | De breedte van de voorbeeldafbeelding. |

### Voorbeeld

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
Taakgidsen die `PreviewOptions` gebruiken:

* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
