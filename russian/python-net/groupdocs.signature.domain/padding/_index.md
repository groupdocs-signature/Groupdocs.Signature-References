---
title: "Класс Padding"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет информацию о внутреннем отступе или внешнем поле, связанную с элементом."
type: docs
url: /ru/python-net/groupdocs.signature.domain/padding/
is_root: false
weight: 400
---


## Padding class

Представляет информацию о внутреннем отступе или внешнем поле, связанную с элементом.

Тип Padding раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/) | Инициализирует новый экземпляр класса Padding со значениями, равными нулю. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#all) | Инициализирует новый экземпляр класса Padding, используя заданный размер отступа для всех сторон. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#left-right-top-bottom) | Инициализирует новый экземпляр класса Padding, используя заданные размеры отступов. |

### Методы
| Метод | Описание |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/padding/clone/) | Возвращает копию этого объекта. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [all](/signature/python-net/groupdocs.signature.domain/padding/all/) | Значение отступа для всех сторон. |
| [bottom](/signature/python-net/groupdocs.signature.domain/padding/bottom/) | Значение отступа для нижней стороны. |
| [horizontal](/signature/python-net/groupdocs.signature.domain/padding/horizontal/) | Суммарный отступ для правой и левой сторон. |
| [left](/signature/python-net/groupdocs.signature.domain/padding/left/) | Значение отступа для левой стороны. |
| [right](/signature/python-net/groupdocs.signature.domain/padding/right/) | Значение отступа для правой стороны. |
| [top](/signature/python-net/groupdocs.signature.domain/padding/top/) | Значение отступа для верхней стороны. |
| [vertical](/signature/python-net/groupdocs.signature.domain/padding/vertical/) | Суммарный отступ для верхней и нижней сторон. |

### Поля
| Поле | Описание |
| :- | :- |
| [EMPTY](/signature/python-net/groupdocs.signature.domain/padding/empty/) | Предоставляет объект Padding без отступов. |

### Пример

```python
from groupdocs.signature.domain import Padding

# Однородный отступ в 5 единиц со всех сторон
uniform = Padding(5)

# Конкретный отступ справа и снизу
custom = Padding(right=40, bottom=60)
```

### Guides
Руководства задач, использующие `Padding`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### См. также
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
