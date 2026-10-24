---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует параметр проверки по умолчанию для подписи штрихкода."
type: docs
url: /ru/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует параметр проверки по умолчанию для подписи штрихкода.

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.signature.options import BarcodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

options = BarcodeVerifyOptions()
options.text = "12345"
options.match_type = TextMatchType.CONTAINS
```

## __init__ {#text}

Инициализирует параметр проверки по умолчанию с текстом проверки.

```python
def __init__(self, text):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | `str` | Текст штрихкода для проверки. |

## __init__ {#encode_type}

Инициализирует параметр проверки по умолчанию с проверкой типа штрихкода.

```python
def __init__(self, encode_type):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| encode_type | `BarcodeType` | Проверка типа штрихкода. |

## __init__ {#text-encode_type}

Инициализирует параметр проверки по умолчанию с проверкой типа штрих‑кода и текста.

```python
def __init__(self, text, encode_type):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | `str` | Текст штрихкода для проверки. |
| encode_type | `BarcodeType` | Проверка типа штрихкода. |

### См. также
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/)
