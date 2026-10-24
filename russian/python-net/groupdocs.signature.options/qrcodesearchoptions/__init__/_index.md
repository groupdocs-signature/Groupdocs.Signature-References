---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует новый экземпляр класса QRCodeSearchOptions со значениями по умолчанию."
type: docs
url: /ru/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса QRCodeSearchOptions со значениями по умолчанию.

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

## __init__ {#encode_type}

Инициализирует новый экземпляр класса QRCodeSearchOptions со значением типа кодирования.

```python
def __init__(self, encode_type):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| encode_type | `QrCodeType` | Указывает тип кодирования QR‑Code. |

## __init__ {#encode_type-text}

Инициализирует новый экземпляр класса QRCodeSearchOptions с типом кодирования и значениями текста.

```python
def __init__(self, encode_type, text):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| encode_type | `QrCodeType` | Указывает тип кодирования QR‑Code. |
| text | `str` | Установить текст подписи QR‑Code. |

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

### См. также
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
