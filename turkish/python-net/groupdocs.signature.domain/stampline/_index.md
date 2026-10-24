---
title: "StampLine sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Damga çizgi özelliklerini belirtin."
type: docs
url: /tr/python-net/groupdocs.signature.domain/stampline/
is_root: false
weight: 680
---


## StampLine class

Damga çizgi özelliklerini belirtin.

StampLine türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/stampline/__init__/) | Bir StampLine'ı varsayılan değerlerle başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [background_color](/signature/python-net/groupdocs.signature.domain/stampline/background_color/) | İmzanın arka plan rengi. |
| [font](/signature/python-net/groupdocs.signature.domain/stampline/font/) | Damga satırı metninin yazı tipi. |
| [height](/signature/python-net/groupdocs.signature.domain/stampline/height/) | Damgadaki satır yüksekliği. |
| [inner_border](/signature/python-net/groupdocs.signature.domain/stampline/inner_border/) | Damga satırının iç kenarı. |
| [outer_border](/signature/python-net/groupdocs.signature.domain/stampline/outer_border/) | Damga satırının dış kenarı. |
| [text](/signature/python-net/groupdocs.signature.domain/stampline/text/) | Damga satırının metni. |
| [text_bottom_intent](/signature/python-net/groupdocs.signature.domain/stampline/text_bottom_intent/) | Metnin alt amacı. |
| [text_color](/signature/python-net/groupdocs.signature.domain/stampline/text_color/) | İmzanın metin rengi. |
| [text_repeat_type](/signature/python-net/groupdocs.signature.domain/stampline/text_repeat_type/) | Metin tekrarlama türü. |
| [visible](/signature/python-net/groupdocs.signature.domain/stampline/visible/) | Damga satırının görünürlüğü. |

### Örnek

```python
from groupdocs.signature.domain import StampLine
from groupdocs.pydrawing import Color

# Bir damga satırı oluştur
line = StampLine()
line.text = " * European Union *"
line.font.size = 12
line.height = 22
line.text_bottom_intent = 6
line.text_color = Color.white_smoke
line.background_color = Color.dark_slate_blue
```

### Ayrıca Bakınız
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
