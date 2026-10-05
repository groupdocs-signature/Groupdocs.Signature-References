---
title: PreviewOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents document preview options."
type: docs
url: /python-net/groupdocs.signature.options/previewoptions/
is_root: false
weight: 430
---


## PreviewOptions class

Represents document preview options.

The PreviewOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-resolution-page_numbers) |  |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-release_page_stream-resolution-page_numbers) |  |

### Properties
| Property | Description |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/previewoptions/height/) | The preview images height. |
| [hide_signatures](/signature/python-net/groupdocs.signature.options/previewoptions/hide_signatures/) | The flag indicating whether signatures are hidden from page preview images. |
| [page_numbers](/signature/python-net/groupdocs.signature.options/previewoptions/page_numbers/) | The preview images page numbers. |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewoptions/preview_format/) | The preview images format. |
| [resolution](/signature/python-net/groupdocs.signature.options/previewoptions/resolution/) | The resolution of the preview images in DPI (dots per inch). The default resolution is 96 DPI. |
| [width](/signature/python-net/groupdocs.signature.options/previewoptions/width/) | The preview image width. |

### Example

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

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
