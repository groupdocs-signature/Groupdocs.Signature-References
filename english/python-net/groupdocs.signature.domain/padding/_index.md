---
title: Padding class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents padding or margin information associated with element."
type: docs
url: /python-net/groupdocs.signature.domain/padding/
is_root: false
weight: 400
---


## Padding class

Represents padding or margin information associated with element.

The Padding type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/) | Initializes a new instance of the Padding class with zero values. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#all) | Initializes a new instance of the Padding class using the supplied padding size for all edges. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#left-right-top-bottom) | Initializes a new instance of the Padding class using the supplied padding sizes. |

### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/padding/clone/) | Gets a copy of this object. |

### Properties
| Property | Description |
| :- | :- |
| [all](/signature/python-net/groupdocs.signature.domain/padding/all/) | The padding value for all edges. |
| [bottom](/signature/python-net/groupdocs.signature.domain/padding/bottom/) | The padding value for the bottom edge. |
| [horizontal](/signature/python-net/groupdocs.signature.domain/padding/horizontal/) | The combined padding for the right and left edges. |
| [left](/signature/python-net/groupdocs.signature.domain/padding/left/) | The padding value for the left edge. |
| [right](/signature/python-net/groupdocs.signature.domain/padding/right/) | The padding value for the right edge. |
| [top](/signature/python-net/groupdocs.signature.domain/padding/top/) | The padding value for the top edge. |
| [vertical](/signature/python-net/groupdocs.signature.domain/padding/vertical/) | The combined padding for the top and bottom edges. |

### Fields
| Field | Description |
| :- | :- |
| [EMPTY](/signature/python-net/groupdocs.signature.domain/padding/empty/) | Provides a Padding object with no padding. |

### Example

```python
from groupdocs.signature.domain import Padding

# Uniform padding of 5 units on all sides
uniform = Padding(5)

# Specific padding on right and bottom
custom = Padding(right=40, bottom=60)
```

### Guides
Task guides that use `Padding`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### See Also
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
