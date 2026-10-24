---
title: "SignatureFont klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "De SignatureFont‑klasse specificeert lettertype‑eigenschappen voor een teksthandtekening."
type: docs
url: /nl/python-net/groupdocs.signature.domain/signaturefont/
is_root: false
weight: 620
---


## SignatureFont class

De SignatureFont‑klasse specificeert lettertype‑eigenschappen voor een teksthandtekening.

Het type SignatureFont bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/signaturefont/__init__/) | Initialiseert een SignatureFont met standaardwaarden. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [bold](/signature/python-net/groupdocs.signature.domain/signaturefont/bold/) | De vette stijl van het lettertype. |
| [family_name](/signature/python-net/groupdocs.signature.domain/signaturefont/family_name/) | De naam van het lettertype. |
| [italic](/signature/python-net/groupdocs.signature.domain/signaturefont/italic/) | De cursieve stijl van het lettertype. |
| [size](/signature/python-net/groupdocs.signature.domain/signaturefont/size/) | De grootte van het lettertype. |
| [strikeout](/signature/python-net/groupdocs.signature.domain/signaturefont/strikeout/) | De doorhalingsstijl van het lettertype. |
| [underline](/signature/python-net/groupdocs.signature.domain/signaturefont/underline/) | De onderstreepte stijl van het lettertype. |

### Voorbeeld

```python
from groupdocs.signature.domain import SignatureFont

font = SignatureFont()
font.family_name = "Arial"
font.size = 20
font.bold = True
```

### Guides
Taakgidsen die `SignatureFont` gebruiken:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Zie ook
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
