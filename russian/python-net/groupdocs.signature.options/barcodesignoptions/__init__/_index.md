---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует новый экземпляр класса BarcodeSignOptions со значениями по умолчанию."
type: docs
url: /ru/python-net/groupdocs.signature.options/barcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса BarcodeSignOptions со значениями по умолчанию.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Инициализирует новый экземпляр класса BarcodeSignOptions с текстом.

```python
def __init__(self, text):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | `str` | Текст штрих‑кода. |

### Пример

```python
from groupdocs.signature.options import BarcodeSignOptions

# Создайте параметры подписи штрих‑кода с желаемым текстом
options = BarcodeSignOptions("JohnSmith")
```

## __init__ {#text-encode_type}

Инициализирует новый экземпляр класса BarcodeSignOptions с текстом.

```python
def __init__(self, text, encode_type):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | `str` | Текст штрих‑кода. |
| encode_type | `BarcodeType` | Тип кодирования штрих‑кода. |

### Пример

```python
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

# Создайте параметры подписи штрих‑кода с текстом и типом
options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
```

### См. также
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
