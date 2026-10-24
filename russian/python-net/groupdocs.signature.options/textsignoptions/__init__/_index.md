---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует новый экземпляр класса TextSignOptions со значениями по умолчанию."
type: docs
url: /ru/python-net/groupdocs.signature.options/textsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса TextSignOptions со значениями по умолчанию.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Инициализирует новый экземпляр класса TextSignOptions с текстом.

```python
def __init__(self, text):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | `str` | Текст подписи. |

### Пример

```python
from groupdocs.signature.options import TextSignOptions

# Создайте параметр текстовой подписи с желаемым текстом подписи.
options = TextSignOptions("John Smith")
```

### См. также
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)
