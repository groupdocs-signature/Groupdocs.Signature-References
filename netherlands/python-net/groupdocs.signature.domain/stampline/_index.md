---
title: "StampLine klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Specificeer stempel‑lijneigenschappen."
type: docs
url: /nl/python-net/groupdocs.signature.domain/stampline/
is_root: false
weight: 680
---


## StampLine class

Specificeer stempel‑lijneigenschappen.

Het StampLine type toont de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/stampline/__init__/) | Initialiseert een StampLine met standaardwaarden. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [background_color](/signature/python-net/groupdocs.signature.domain/stampline/background_color/) | De achtergrondkleur van de handtekening. |
| [font](/signature/python-net/groupdocs.signature.domain/stampline/font/) | Het lettertype van de stempelregeltekst. |
| [height](/signature/python-net/groupdocs.signature.domain/stampline/height/) | De regelhoogte op de stempel. |
| [inner_border](/signature/python-net/groupdocs.signature.domain/stampline/inner_border/) | De interne rand van de stempelregel. |
| [outer_border](/signature/python-net/groupdocs.signature.domain/stampline/outer_border/) | De buitenste rand van de stempelregel. |
| [text](/signature/python-net/groupdocs.signature.domain/stampline/text/) | De tekst van de stempelregel. |
| [text_bottom_intent](/signature/python-net/groupdocs.signature.domain/stampline/text_bottom_intent/) | De onderste intentie van tekst. |
| [text_color](/signature/python-net/groupdocs.signature.domain/stampline/text_color/) | De tekstkleur van de handtekening. |
| [text_repeat_type](/signature/python-net/groupdocs.signature.domain/stampline/text_repeat_type/) | Het type tekstherhaling. |
| [visible](/signature/python-net/groupdocs.signature.domain/stampline/visible/) | De zichtbaarheid van de stempelregel. |

### Voorbeeld

```python
from groupdocs.signature.domain import StampLine
from groupdocs.pydrawing import Color

# Maak een stempelregel
line = StampLine()
line.text = " * European Union *"
line.font.size = 12
line.height = 22
line.text_bottom_intent = 6
line.text_color = Color.white_smoke
line.background_color = Color.dark_slate_blue
```

### Zie ook
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
