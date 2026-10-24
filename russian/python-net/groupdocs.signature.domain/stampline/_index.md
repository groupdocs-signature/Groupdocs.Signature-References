---
title: "Класс StampLine"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Укажите свойства линии печати."
type: docs
url: /ru/python-net/groupdocs.signature.domain/stampline/
is_root: false
weight: 680
---


## StampLine class

Укажите свойства линии печати.

Тип StampLine раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/stampline/__init__/) | Инициализирует объект StampLine со значениями по умолчанию. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [background_color](/signature/python-net/groupdocs.signature.domain/stampline/background_color/) | Фоновый цвет подписи. |
| [font](/signature/python-net/groupdocs.signature.domain/stampline/font/) | Шрифт текста строки штампа. |
| [height](/signature/python-net/groupdocs.signature.domain/stampline/height/) | Высота строки на штампе. |
| [inner_border](/signature/python-net/groupdocs.signature.domain/stampline/inner_border/) | Внутренняя граница строки штампа. |
| [outer_border](/signature/python-net/groupdocs.signature.domain/stampline/outer_border/) | Внешняя граница строки штампа. |
| [text](/signature/python-net/groupdocs.signature.domain/stampline/text/) | Текст строки штампа. |
| [text_bottom_intent](/signature/python-net/groupdocs.signature.domain/stampline/text_bottom_intent/) | Нижнее намерение текста. |
| [text_color](/signature/python-net/groupdocs.signature.domain/stampline/text_color/) | Цвет текста подписи. |
| [text_repeat_type](/signature/python-net/groupdocs.signature.domain/stampline/text_repeat_type/) | Тип повторения текста. |
| [visible](/signature/python-net/groupdocs.signature.domain/stampline/visible/) | Видимость строки штампа. |

### Пример

```python
from groupdocs.signature.domain import StampLine
from groupdocs.pydrawing import Color

# Создать строку штампа
line = StampLine()
line.text = " * European Union *"
line.font.size = 12
line.height = 22
line.text_bottom_intent = 6
line.text_color = Color.white_smoke
line.background_color = Color.dark_slate_blue
```

### См. также
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
