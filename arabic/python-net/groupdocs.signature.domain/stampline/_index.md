---
title: "StampLine فئة"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "حدد خصائص خط الطابع."
type: docs
url: /ar/python-net/groupdocs.signature.domain/stampline/
is_root: false
weight: 680
---


## StampLine class

حدد خصائص خط الطابع.

النوع StampLine يعرض الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/stampline/__init__/) | يُهيئ StampLine بالقيم الافتراضية. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [background_color](/signature/python-net/groupdocs.signature.domain/stampline/background_color/) | لون الخلفية للتوقيع. |
| [font](/signature/python-net/groupdocs.signature.domain/stampline/font/) | خط نص سطر الختم. |
| [height](/signature/python-net/groupdocs.signature.domain/stampline/height/) | ارتفاع السطر على الختم. |
| [inner_border](/signature/python-net/groupdocs.signature.domain/stampline/inner_border/) | الحد الداخلي لسطر الختم. |
| [outer_border](/signature/python-net/groupdocs.signature.domain/stampline/outer_border/) | الحد الخارجي لخط الختم. |
| [text](/signature/python-net/groupdocs.signature.domain/stampline/text/) | نص خط الختم. |
| [text_bottom_intent](/signature/python-net/groupdocs.signature.domain/stampline/text_bottom_intent/) | النية السفلية للنص. |
| [text_color](/signature/python-net/groupdocs.signature.domain/stampline/text_color/) | لون نص التوقيع. |
| [text_repeat_type](/signature/python-net/groupdocs.signature.domain/stampline/text_repeat_type/) | نوع تكرار النص. |
| [visible](/signature/python-net/groupdocs.signature.domain/stampline/visible/) | ظهور خط الختم. |

### مثال

```python
from groupdocs.signature.domain import StampLine
from groupdocs.pydrawing import Color

# إنشاء خط ختم
line = StampLine()
line.text = " * European Union *"
line.font.size = 12
line.height = 22
line.text_bottom_intent = 6
line.text_color = Color.white_smoke
line.background_color = Color.dark_slate_blue
```

### انظر أيضًا
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
