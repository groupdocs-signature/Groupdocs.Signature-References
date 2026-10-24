---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует новый экземпляр класса TextSearchOptions со значениями по умолчанию."
type: docs
url: /ru/python-net/groupdocs.signature.options/textsearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса TextSearchOptions со значениями по умолчанию.

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    # Поиск текстовых подписей с использованием параметров по умолчанию
    result = signature.search([TextSearchOptions()])
    for text_signature in result.signatures:
        print(f"Found text signature: {text_signature.text}")
```

## __init__ {#text}

Инициализирует новый экземпляр класса TextSearchOptions со значением текста.

```python
def __init__(self, text):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | `str` | Текст текстовой подписи. |

### См. также
* class [`TextSearchOptions`](/signature/python-net/groupdocs.signature.options/textsearchoptions/)
