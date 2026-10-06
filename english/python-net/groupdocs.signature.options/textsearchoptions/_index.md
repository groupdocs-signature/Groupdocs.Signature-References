---
title: TextSearchOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents search options for Text signatures."
type: docs
url: /python-net/groupdocs.signature.options/textsearchoptions/
is_root: false
weight: 580
---


## TextSearchOptions class

Represents search options for Text signatures.

Learn more:
- Basic usage of search for Text electronic signature by GroupDocs.Signature: [How to eSearch Text signatures in a document](https://docs.groupdocs.com/display/signaturenet/Search+for+Text+e-signatures)
- Advanced usage of settings of search for Text electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Text signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Text+signatures)

The TextSearchOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/) | Initializes a new instance of the TextSearchOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/#text) | Initializes a new instance of the TextSearchOptions class with a text value. |

### Properties
| Property | Description |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/textsearchoptions/match_type/) | The text match type used for searching. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsearchoptions/signature_implementation/) | The text signature implementation to search. |
| [text](/signature/python-net/groupdocs.signature.options/textsearchoptions/text/) | The signature text to match when searching. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | The flag indicating whether to search on each document page. By default this value is True. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | The document page number for searching (optional). (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | The options to specify pages for signature searching. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | The flag indicating whether to return the shape position in the document layout. Available only for Word documents. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | The flag to return only signatures marked as `IsSignature`. By default the value is `False`, which indicates that all signatures matching the specified criteria are returned. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType, TextSignatureImplementation
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    options = TextSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.text = "John"
    options.match_type = TextMatchType.CONTAINS
    options.signature_implementation = TextSignatureImplementation.NATIVE

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching text signature(s)")
    for ts in result.signatures:
        print(f"'{ts.text}' on page {ts.page_number} at ({ts.left}, {ts.top}), size {ts.width}x{ts.height}")
```

### Guides
Task guides that use `TextSearchOptions`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
