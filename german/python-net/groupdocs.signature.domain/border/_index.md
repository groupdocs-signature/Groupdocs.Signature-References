---
title: "Border Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt das Erscheinungsbild des Rahmens dar."
type: docs
url: /de/python-net/groupdocs.signature.domain/border/
is_root: false
weight: 60
---


## Border class

Stellt das Erscheinungsbild des Rahmens dar.

Der Typ Border stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/border/__init__/) |  |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/border/clone/) | Implementiert das IClonable-Interface. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [color](/signature/python-net/groupdocs.signature.domain/border/color/) | Die Randfarbe der Signatur. |
| [dash_style](/signature/python-net/groupdocs.signature.domain/border/dash_style/) | Der Signaturrandstil. |
| [transparency](/signature/python-net/groupdocs.signature.domain/border/transparency/) | Die Transparenz des Signaturrandes, von 0,0 (undurchsichtig) bis 1,0 (transparent), standardmäßig 0 (undurchsichtig). |
| [visible](/signature/python-net/groupdocs.signature.domain/border/visible/) | Die Sichtbarkeit des Randes. |
| [weight](/signature/python-net/groupdocs.signature.domain/border/weight/) | Die Stärke des Signaturrandes. |

### Beispiel

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
Aufgabenleitfäden, die `Border` verwenden:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)

### Siehe auch
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
