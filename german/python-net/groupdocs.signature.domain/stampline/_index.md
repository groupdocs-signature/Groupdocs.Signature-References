---
title: "StampLine Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Geben Sie Stempel-Linieneigenschaften an."
type: docs
url: /de/python-net/groupdocs.signature.domain/stampline/
is_root: false
weight: 680
---


## StampLine class

Geben Sie Stempel-Linieneigenschaften an.

Der StampLine Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/stampline/__init__/) | Initialisiert ein StampLine mit Standardwerten. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [background_color](/signature/python-net/groupdocs.signature.domain/stampline/background_color/) | Die Hintergrundfarbe der Signatur. |
| [font](/signature/python-net/groupdocs.signature.domain/stampline/font/) | Die Schriftart des Stempelzeilentextes. |
| [height](/signature/python-net/groupdocs.signature.domain/stampline/height/) | Die Zeilenhöhe auf dem Stempel. |
| [inner_border](/signature/python-net/groupdocs.signature.domain/stampline/inner_border/) | Der innere Rand der Stempelzeile. |
| [outer_border](/signature/python-net/groupdocs.signature.domain/stampline/outer_border/) | Der äußere Rand der Stempelzeile. |
| [text](/signature/python-net/groupdocs.signature.domain/stampline/text/) | Der Text der Stempelzeile. |
| [text_bottom_intent](/signature/python-net/groupdocs.signature.domain/stampline/text_bottom_intent/) | Die untere Ausrichtung des Textes. |
| [text_color](/signature/python-net/groupdocs.signature.domain/stampline/text_color/) | Die Textfarbe der Signatur. |
| [text_repeat_type](/signature/python-net/groupdocs.signature.domain/stampline/text_repeat_type/) | Der Textwiederholungstyp. |
| [visible](/signature/python-net/groupdocs.signature.domain/stampline/visible/) | Die Sichtbarkeit der Stempelzeile. |

### Beispiel

```python
from groupdocs.signature.domain import StampLine
from groupdocs.pydrawing import Color

# Eine Stempelzeile erstellen
line = StampLine()
line.text = " * European Union *"
line.font.size = 12
line.height = 22
line.text_bottom_intent = 6
line.text_color = Color.white_smoke
line.background_color = Color.dark_slate_blue
```

### Siehe auch
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
