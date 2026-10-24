---
title: "Classe Border"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta l'aspetto del bordo."
type: docs
url: /it/python-net/groupdocs.signature.domain/border/
is_root: false
weight: 60
---


## Border class

Rappresenta l'aspetto del bordo.

Il tipo Border espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/border/__init__/) |  |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/border/clone/) | Implementa l'interfaccia IClonable. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [color](/signature/python-net/groupdocs.signature.domain/border/color/) | Il colore del bordo della firma. |
| [dash_style](/signature/python-net/groupdocs.signature.domain/border/dash_style/) | Lo stile del bordo della firma. |
| [transparency](/signature/python-net/groupdocs.signature.domain/border/transparency/) | La trasparenza del bordo della firma, da 0,0 (opaco) a 1,0 (trasparente), predefinita a 0 (opaco). |
| [visible](/signature/python-net/groupdocs.signature.domain/border/visible/) | La visibilità del bordo. |
| [weight](/signature/python-net/groupdocs.signature.domain/border/weight/) | Lo spessore del bordo della firma. |

### Esempio

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
Guide operative che utilizzano `Border`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)

### Vedi anche
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
