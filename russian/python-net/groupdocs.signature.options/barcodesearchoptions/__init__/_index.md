---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует новый экземпляр класса BarcodeSearchOptions со значениями по умолчанию."
type: docs
url: /ru/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса BarcodeSearchOptions со значениями по умолчанию.

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.signature.options import BarcodeSearchOptions

# Создайте объект параметров поиска с настройками по умолчанию
options = BarcodeSearchOptions()
```

## __init__ {#encode_type}

Инициализирует новый экземпляр класса BarcodeSearchOptions со значением типа кодирования.

```python
def __init__(self, encode_type):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| encode_type | `BarcodeType` | Указывает тип кодирования штрих‑кода. |

## __init__ {#encode_type-text}

Инициализирует новый экземпляр класса BarcodeSearchOptions со значениями типа кодирования и текста.

```python
def __init__(self, encode_type, text):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| encode_type | `BarcodeType` | Указывает тип кодирования штрих‑кода. |
| text | `str` | Установите Text подписи штрих‑кода. |

### См. также
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
