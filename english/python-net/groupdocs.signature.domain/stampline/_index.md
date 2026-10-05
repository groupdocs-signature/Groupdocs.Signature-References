---
title: StampLine class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Specify Stamp line properties."
type: docs
url: /python-net/groupdocs.signature.domain/stampline/
is_root: false
weight: 680
---


## StampLine class

Specify Stamp line properties.

The StampLine type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/stampline/__init__/) | Initializes a StampLine with default values. |

### Properties
| Property | Description |
| :- | :- |
| [background_color](/signature/python-net/groupdocs.signature.domain/stampline/background_color/) | The background color of the signature. |
| [font](/signature/python-net/groupdocs.signature.domain/stampline/font/) | The font of the stamp line text. |
| [height](/signature/python-net/groupdocs.signature.domain/stampline/height/) | The line height on the stamp. |
| [inner_border](/signature/python-net/groupdocs.signature.domain/stampline/inner_border/) | The internal border of the stamp line. |
| [outer_border](/signature/python-net/groupdocs.signature.domain/stampline/outer_border/) | The outer border of the stamp line. |
| [text](/signature/python-net/groupdocs.signature.domain/stampline/text/) | The text of the stamp line. |
| [text_bottom_intent](/signature/python-net/groupdocs.signature.domain/stampline/text_bottom_intent/) | The bottom intent of text. |
| [text_color](/signature/python-net/groupdocs.signature.domain/stampline/text_color/) | The text color of the signature. |
| [text_repeat_type](/signature/python-net/groupdocs.signature.domain/stampline/text_repeat_type/) | The text repeat type. |
| [visible](/signature/python-net/groupdocs.signature.domain/stampline/visible/) | The visibility of the stamp line. |

### Example

```python
from groupdocs.signature.domain import StampLine
from groupdocs.pydrawing import Color

# Create a stamp line
line = StampLine()
line.text = " * European Union *"
line.font.size = 12
line.height = 22
line.text_bottom_intent = 6
line.text_color = Color.white_smoke
line.background_color = Color.dark_slate_blue
```

### See Also
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
