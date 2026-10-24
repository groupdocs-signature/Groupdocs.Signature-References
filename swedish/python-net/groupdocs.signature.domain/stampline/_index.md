---
title: "StampLine-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Ange stämpellinje‑egenskaper."
type: docs
url: /sv/python-net/groupdocs.signature.domain/stampline/
is_root: false
weight: 680
---


## StampLine class

Ange stämpellinje‑egenskaper.

StampLine-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/stampline/__init__/) | Initierar en StampLine med standardvärden. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [background_color](/signature/python-net/groupdocs.signature.domain/stampline/background_color/) | Bakgrundsfärgen för signaturen. |
| [font](/signature/python-net/groupdocs.signature.domain/stampline/font/) | Typsnittet för stämpelradens text. |
| [height](/signature/python-net/groupdocs.signature.domain/stampline/height/) | Radens höjd på stämpeln. |
| [inner_border](/signature/python-net/groupdocs.signature.domain/stampline/inner_border/) | Den interna kanten på stämpelraden. |
| [outer_border](/signature/python-net/groupdocs.signature.domain/stampline/outer_border/) | Den yttre kanten på stämpelraden. |
| [text](/signature/python-net/groupdocs.signature.domain/stampline/text/) | Texten för stämpelraden. |
| [text_bottom_intent](/signature/python-net/groupdocs.signature.domain/stampline/text_bottom_intent/) | Den nedre avsikten för texten. |
| [text_color](/signature/python-net/groupdocs.signature.domain/stampline/text_color/) | Textfärgen för signaturen. |
| [text_repeat_type](/signature/python-net/groupdocs.signature.domain/stampline/text_repeat_type/) | Textupprepningstypen. |
| [visible](/signature/python-net/groupdocs.signature.domain/stampline/visible/) | Synligheten för stämpelraden. |

### Exempel

```python
from groupdocs.signature.domain import StampLine
from groupdocs.pydrawing import Color

# Skapa en stämpelrad
line = StampLine()
line.text = " * European Union *"
line.font.size = 12
line.height = 22
line.text_bottom_intent = 6
line.text_color = Color.white_smoke
line.background_color = Color.dark_slate_blue
```

### Se även
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
