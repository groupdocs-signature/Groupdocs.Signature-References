---
title: TextSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: "The TextSignature class contains text signature properties."
type: docs
url: /python-net/groupdocs.signature.domain/textsignature/
is_root: false
weight: 770
---


## TextSignature class

The TextSignature class contains text signature properties.

The TextSignature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textsignature/__init__/#signature_id) | Initializes a TextSignature object with the unique signature identifier obtained from a sign or search operation. |

### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textsignature/clone/) | Clones Text Signature instance. |
| [equals](/signature/python-net/groupdocs.signature.domain/textsignature/equals/#obj) | Compares the specified signature with this instance for equality. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textsignature/get_hash_code/) | Returns the hash code for the signature. |

### Properties
| Property | Description |
| :- | :- |
| [native](/signature/python-net/groupdocs.signature.domain/textsignature/native/) | The native attribute indicating whether the signature is document‑specific. |
| [signature_implementation](/signature/python-net/groupdocs.signature.domain/textsignature/signature_implementation/) | The text signature implementation. |
| [text](/signature/python-net/groupdocs.signature.domain/textsignature/text/) | The text of the signature. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | The signature creation date. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | The flag indicating whether this signature was deleted from the document. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | The height of the signature. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | The flag indicating whether this component represents a signature (`True`) or document content (`False`). (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | The left position of the signature. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | The signature modification date. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | The page number where the signature was found. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | The unique identifier of the signature, used to modify the signature in the document via update or delete operations. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | The type of signature. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | The top position of the signature. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | The width of the signature. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for text_sig in result.signatures:
        print(f"Text: {text_sig.text}, Position: ({text_sig.left}, {text_sig.top}), Size: {text_sig.width}x{text_sig.height}")
```

### Guides
Task guides that use `TextSignature`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)

### See Also
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
