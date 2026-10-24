---
title: "Classe StampLine"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Specifica le proprietà della linea del timbro."
type: docs
url: /it/python-net/groupdocs.signature.domain/stampline/
is_root: false
weight: 680
---


## StampLine class

Specifica le proprietà della linea del timbro.

Il tipo StampLine espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/stampline/__init__/) | Inizializza un StampLine con valori predefiniti. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [background_color](/signature/python-net/groupdocs.signature.domain/stampline/background_color/) | Il colore di sfondo della firma. |
| [font](/signature/python-net/groupdocs.signature.domain/stampline/font/) | Il carattere del testo della linea di timbro. |
| [height](/signature/python-net/groupdocs.signature.domain/stampline/height/) | L'altezza della linea sul timbro. |
| [inner_border](/signature/python-net/groupdocs.signature.domain/stampline/inner_border/) | Il bordo interno della linea di timbro. |
| [outer_border](/signature/python-net/groupdocs.signature.domain/stampline/outer_border/) | Il bordo esterno della linea di timbro. |
| [text](/signature/python-net/groupdocs.signature.domain/stampline/text/) | Il testo della linea di timbro. |
| [text_bottom_intent](/signature/python-net/groupdocs.signature.domain/stampline/text_bottom_intent/) | L'intento inferiore del testo. |
| [text_color](/signature/python-net/groupdocs.signature.domain/stampline/text_color/) | Il colore del testo della firma. |
| [text_repeat_type](/signature/python-net/groupdocs.signature.domain/stampline/text_repeat_type/) | Il tipo di ripetizione del testo. |
| [visible](/signature/python-net/groupdocs.signature.domain/stampline/visible/) | La visibilità della linea di timbro. |

### Esempio

```python
from groupdocs.signature.domain import StampLine
from groupdocs.pydrawing import Color

# Crea una linea di timbro
line = StampLine()
line.text = " * European Union *"
line.font.size = 12
line.height = 22
line.text_bottom_intent = 6
line.text_color = Color.white_smoke
line.background_color = Color.dark_slate_blue
```

### Vedi anche
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
