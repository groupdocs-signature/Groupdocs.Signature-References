---
title: BarcodeSearchOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents search options for Barcode signatures."
type: docs
url: /python-net/groupdocs.signature.options/barcodesearchoptions/
is_root: false
weight: 10
---


## BarcodeSearchOptions class

Represents search options for Barcode signatures.

Learn more:
- Basic usage of search for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Barcode+e-signatures
- Advanced usage of settings of search for Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Barcode+signatures

The BarcodeSearchOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/) | Initializes a new instance of the BarcodeSearchOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type) | Initializes a new instance of the BarcodeSearchOptions class with encode type value. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type-text) | Initializes a new instance of the BarcodeSearchOptions class with encode type and text values. |

### Properties
| Property | Description |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/encode_type/) | The encode type used to filter barcode search; if not set, the search includes all supported barcode types. |
| [match_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/match_type/) | The barcode text match type used for searching. It is used only when the `text` property is set. |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content/) | The flag indicating whether to retrieve the barcode image content of a signature on a document page. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/) | The file type of the returned image content for a Barcode signature when the `return_content` property is enabled. |
| [text](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/text/) | The text of the barcode signature to search for and match. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | The flag indicating whether to search on each document page. By default this value is True. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | The document page number for searching (optional). (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | The options to specify pages for signature searching. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | The flag indicating whether to return the shape position in the document layout. Available only for Word documents. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | The flag to return only signatures marked as `IsSignature`. By default the value is `False`, which indicates that all signatures matching the specified criteria are returned. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

with Signature("signed.pdf") as signature:
    options = BarcodeSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.encode_type = BarcodeTypes.CODE128
    options.text = "1234"
    options.match_type = TextMatchType.STARTS_WITH

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching barcode signature(s)")
```

### Guides
Task guides that use `BarcodeSearchOptions`:

* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
