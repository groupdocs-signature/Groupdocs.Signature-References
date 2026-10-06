---
title: Border class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents border appearance."
type: docs
url: /python-net/groupdocs.signature.domain/border/
is_root: false
weight: 60
---


## Border class

Represents border appearance.

The Border type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/border/__init__/) |  |

### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/border/clone/) | Implements IClonable interface. |

### Properties
| Property | Description |
| :- | :- |
| [color](/signature/python-net/groupdocs.signature.domain/border/color/) | The border color of the signature. |
| [dash_style](/signature/python-net/groupdocs.signature.domain/border/dash_style/) | The signature border style. |
| [transparency](/signature/python-net/groupdocs.signature.domain/border/transparency/) | The signature border transparency, ranging from 0.0 (opaque) to 1.0 (clear), defaults to 0 (opaque). |
| [visible](/signature/python-net/groupdocs.signature.domain/border/visible/) | The visibility of the border. |
| [weight](/signature/python-net/groupdocs.signature.domain/border/weight/) | The weight of the signature border. |

### Example

```python
from groupdocs.signature.domain import Border, DashStyle
from groupdocs.pydrawing import Color

border = Border()
border.color = Color.dark_green
border.dash_style = DashStyle.DASH
border.weight = 2
border.visible = True
```

### Guides
Task guides that use `Border`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)

### See Also
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
