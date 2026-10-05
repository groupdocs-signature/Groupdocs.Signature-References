---
title: SearchResult class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents the result of searching for signatures in a specified document."
type: docs
url: /python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 590
---


## SearchResult class

Represents the result of searching for signatures in a specified document.

The SearchResult type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [get_enumerator](/signature/python-net/groupdocs.signature.domain/searchresult/get_enumerator/) | Returns an iterator over the search results. |
| [to_list](/signature/python-net/groupdocs.signature.domain/searchresult/to_list/) |  |

### Properties
| Property | Description |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size/) | The destination document size, which is always 0 for the Search method. |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed/) | The list of signatures [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) that failed the search process by search criteria. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time/) | The execution time of the search process in milliseconds. |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures/) | The list of found signatures [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size/) | The source document size. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded/) | The list of found signatures ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures/) | The total number of processed signatures returned by the search process. |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([FormFieldSearchOptions()])
    print(f"Found {len(result.signatures)} form field signature(s)")
```

### See Also
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
