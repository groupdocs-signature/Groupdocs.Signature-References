---
title: "Clase StampLine"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Especifique las propiedades de la línea del sello."
type: docs
url: /es/python-net/groupdocs.signature.domain/stampline/
is_root: false
weight: 680
---


## StampLine class

Especifique las propiedades de la línea del sello.

El tipo StampLine expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/stampline/__init__/) | Inicializa un StampLine con valores predeterminados. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [background_color](/signature/python-net/groupdocs.signature.domain/stampline/background_color/) | El color de fondo de la firma. |
| [font](/signature/python-net/groupdocs.signature.domain/stampline/font/) | La fuente del texto de la línea de sello. |
| [height](/signature/python-net/groupdocs.signature.domain/stampline/height/) | La altura de línea en el sello. |
| [inner_border](/signature/python-net/groupdocs.signature.domain/stampline/inner_border/) | El borde interno de la línea de sello. |
| [outer_border](/signature/python-net/groupdocs.signature.domain/stampline/outer_border/) | El borde exterior de la línea de sello. |
| [text](/signature/python-net/groupdocs.signature.domain/stampline/text/) | El texto de la línea de sello. |
| [text_bottom_intent](/signature/python-net/groupdocs.signature.domain/stampline/text_bottom_intent/) | La intención inferior del texto. |
| [text_color](/signature/python-net/groupdocs.signature.domain/stampline/text_color/) | El color del texto de la firma. |
| [text_repeat_type](/signature/python-net/groupdocs.signature.domain/stampline/text_repeat_type/) | El tipo de repetición del texto. |
| [visible](/signature/python-net/groupdocs.signature.domain/stampline/visible/) | La visibilidad de la línea de sello. |

### Ejemplo

```python
from groupdocs.signature.domain import StampLine
from groupdocs.pydrawing import Color

# Crear una línea de sello
line = StampLine()
line.text = " * European Union *"
line.font.size = 12
line.height = 22
line.text_bottom_intent = 6
line.text_color = Color.white_smoke
line.background_color = Color.dark_slate_blue
```

### Ver también
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
