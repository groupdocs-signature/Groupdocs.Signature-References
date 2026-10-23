---
title: "StampLine वर्ग"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "स्टैम्प लाइन गुण निर्दिष्ट करें।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/stampline/
is_root: false
weight: 680
---


## StampLine class

स्टैम्प लाइन गुण निर्दिष्ट करें।

StampLine प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/stampline/__init__/) | डिफ़ॉल्ट मानों के साथ एक StampLine को प्रारंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [background_color](/signature/python-net/groupdocs.signature.domain/stampline/background_color/) | हस्ताक्षर का पृष्ठभूमि रंग। |
| [font](/signature/python-net/groupdocs.signature.domain/stampline/font/) | स्टैम्प लाइन टेक्स्ट का फ़ॉन्ट। |
| [height](/signature/python-net/groupdocs.signature.domain/stampline/height/) | स्टैम्प पर लाइन की ऊँचाई। |
| [inner_border](/signature/python-net/groupdocs.signature.domain/stampline/inner_border/) | स्टैम्प लाइन की आंतरिक सीमा। |
| [outer_border](/signature/python-net/groupdocs.signature.domain/stampline/outer_border/) | स्टैम्प लाइन की बाहरी सीमा। |
| [text](/signature/python-net/groupdocs.signature.domain/stampline/text/) | स्टैम्प लाइन का पाठ। |
| [text_bottom_intent](/signature/python-net/groupdocs.signature.domain/stampline/text_bottom_intent/) | पाठ का निचला इरादा। |
| [text_color](/signature/python-net/groupdocs.signature.domain/stampline/text_color/) | हस्ताक्षर का पाठ रंग। |
| [text_repeat_type](/signature/python-net/groupdocs.signature.domain/stampline/text_repeat_type/) | पाठ दोहराव प्रकार। |
| [visible](/signature/python-net/groupdocs.signature.domain/stampline/visible/) | स्टैम्प लाइन की दृश्यता। |

### उदाहरण

```python
from groupdocs.signature.domain import StampLine
from groupdocs.pydrawing import Color

# स्टैम्प लाइन बनाएं
line = StampLine()
line.text = " * European Union *"
line.font.size = 12
line.height = 22
line.text_bottom_intent = 6
line.text_color = Color.white_smoke
line.background_color = Color.dark_slate_blue
```

### संबंधित देखें
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
