---
title: "Класс Border"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет внешний вид границы."
type: docs
url: /ru/python-net/groupdocs.signature.domain/border/
is_root: false
weight: 60
---


## Border class

Представляет внешний вид границы.

Тип Border раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/border/__init__/) |  |

### Методы
| Метод | Описание |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/border/clone/) | Реализует интерфейс IClonable. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [color](/signature/python-net/groupdocs.signature.domain/border/color/) | Цвет границы подписи. |
| [dash_style](/signature/python-net/groupdocs.signature.domain/border/dash_style/) | Стиль границы подписи. |
| [transparency](/signature/python-net/groupdocs.signature.domain/border/transparency/) | Прозрачность границы подписи, варьируется от 0.0 (непрозрачный) до 1.0 (прозрачный), по умолчанию 0 (непрозрачный). |
| [visible](/signature/python-net/groupdocs.signature.domain/border/visible/) | Видимость границы. |
| [weight](/signature/python-net/groupdocs.signature.domain/border/weight/) | Толщина границы подписи. |

### Пример

```python
from groupdocs.signature.domain import Border, DashStyle
from groupdocs.pydrawing import Color

border = Border()
border.color = Color.dark_green
border.dash_style = DashStyle.DASH
border.weight = 2
border.visible = True
```

### Guides
Руководства задач, использующие `Border`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)

### См. также
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
