---
title: SignatureFont class
second_title: GroupDocs.Signature for Python via .NET API References
description: "The SignatureFont class specifies font properties for a text signature."
type: docs
url: /python-net/groupdocs.signature.domain/signaturefont/
is_root: false
weight: 620
---


## SignatureFont class

The SignatureFont class specifies font properties for a text signature.

The SignatureFont type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/signaturefont/__init__/) | Initializes a SignatureFont with default values. |

### Properties
| Property | Description |
| :- | :- |
| [bold](/signature/python-net/groupdocs.signature.domain/signaturefont/bold/) | The font bold style. |
| [family_name](/signature/python-net/groupdocs.signature.domain/signaturefont/family_name/) | The font family name. |
| [italic](/signature/python-net/groupdocs.signature.domain/signaturefont/italic/) | The font italic style. |
| [size](/signature/python-net/groupdocs.signature.domain/signaturefont/size/) | The font size. |
| [strikeout](/signature/python-net/groupdocs.signature.domain/signaturefont/strikeout/) | The font strikeout style. |
| [underline](/signature/python-net/groupdocs.signature.domain/signaturefont/underline/) | The underline style of the font. |

### Example

```python
from groupdocs.signature.domain import SignatureFont

font = SignatureFont()
font.family_name = "Arial"
font.size = 20
font.bold = True
```

### Guides
Task guides that use `SignatureFont`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### See Also
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
