---
title: "Border classe"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente l'apparence de la bordure."
type: docs
url: /fr/python-net/groupdocs.signature.domain/border/
is_root: false
weight: 60
---


## Border class

Représente l'apparence de la bordure.

Le type Border expose les membres suivants:

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/border/__init__/) |  |

### Méthodes
| Méthode | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/border/clone/) | Implémente l'interface IClonable. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [color](/signature/python-net/groupdocs.signature.domain/border/color/) | La couleur de bordure de la signature. |
| [dash_style](/signature/python-net/groupdocs.signature.domain/border/dash_style/) | Le style de bordure de la signature. |
| [transparency](/signature/python-net/groupdocs.signature.domain/border/transparency/) | La transparence de la bordure de la signature, allant de 0.0 (opaque) à 1.0 (transparent), par défaut 0 (opaque). |
| [visible](/signature/python-net/groupdocs.signature.domain/border/visible/) | La visibilité de la bordure. |
| [weight](/signature/python-net/groupdocs.signature.domain/border/weight/) | L'épaisseur de la bordure de la signature. |

### Exemple

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
Guides de tâches qui utilisent `Border`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)

### Voir aussi
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
