---
title: "Класс SignatureFont"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Класс SignatureFont задает свойства шрифта для текстовой подписи."
type: docs
url: /ru/python-net/groupdocs.signature.domain/signaturefont/
is_root: false
weight: 620
---


## SignatureFont class

Класс SignatureFont задает свойства шрифта для текстовой подписи.

Тип SignatureFont раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/signaturefont/__init__/) | Инициализирует SignatureFont со значениями по умолчанию. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [bold](/signature/python-net/groupdocs.signature.domain/signaturefont/bold/) | Стиль шрифта жирный. |
| [family_name](/signature/python-net/groupdocs.signature.domain/signaturefont/family_name/) | Название семейства шрифта. |
| [italic](/signature/python-net/groupdocs.signature.domain/signaturefont/italic/) | Стиль шрифта курсив. |
| [size](/signature/python-net/groupdocs.signature.domain/signaturefont/size/) | Размер шрифта. |
| [strikeout](/signature/python-net/groupdocs.signature.domain/signaturefont/strikeout/) | Стиль шрифта зачёркнутый. |
| [underline](/signature/python-net/groupdocs.signature.domain/signaturefont/underline/) | Стиль подчеркивания шрифта. |

### Пример

```python
from groupdocs.signature.domain import SignatureFont

font = SignatureFont()
font.family_name = "Arial"
font.size = 20
font.bold = True
```

### Guides
Руководства задач, использующие `SignatureFont`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### См. также
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
