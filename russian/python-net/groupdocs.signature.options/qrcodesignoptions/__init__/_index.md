---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует новый экземпляр класса QRCodeSignOptions со значениями по умолчанию."
type: docs
url: /ru/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса QRCodeSignOptions со значениями по умолчанию.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Инициализирует экземпляр параметров подписи QR-кода с указанным текстом.

```python
def __init__(self, text):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | `str` | Текст подписи. |

### Пример

```python
from groupdocs.signature.options import QrCodeSignOptions

# Создайте параметры подписи QR‑кода с желаемым текстом
options = QrCodeSignOptions("Approved by John Smith")
```

## __init__ {#text-encode_type}

Инициализирует новый экземпляр класса QrCodeSignOptions с текстом.

```python
def __init__(self, text, encode_type):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | `str` | Текст QR‑кода. |
| encode_type | `QrCodeType` | Тип кодирования QR‑кода. |

### Пример

```python
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeSignOptions(
    "https://www.example.com/verify-document",
    QrCodeTypes.QR
)
```

### См. также
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
