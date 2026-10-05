---
title: ImageSearchOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents search options for Image signatures."
type: docs
url: /python-net/groupdocs.signature.options/imagesearchoptions/
is_root: false
weight: 240
---


## ImageSearchOptions class

Represents search options for Image signatures.

Learn more:
- Basic usage of search for Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures
- Advanced usage of settings of search for Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures

The ImageSearchOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesearchoptions/__init__/) | Initializes a new instance of the ImageSearchOptions class with default values. |

### Properties
| Property | Description |
| :- | :- |
| [max_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/max_content_size/) | The maximum size of images for the search criteria, in bytes. |
| [min_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/min_content_size/) | The minimal size of image data, in bytes, to be considered during a search. A non‑zero value specifies the minimal size; the default is zero, which does not affect the search result. |
| [return_content](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content/) | The flag that determines whether the image content of a signature is returned. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/) | The file type of the returned image content when the `return_content` property is enabled. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | The flag indicating whether to search on each document page. By default this value is True. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | The document page number for searching (optional). (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | The options to specify pages for signature searching. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | The flag indicating whether to return the shape position in the document layout. Available only for Word documents. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | The flag to return only signatures marked as `IsSignature`. By default the value is `False`, which indicates that all signatures matching the specified criteria are returned. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Example

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

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
