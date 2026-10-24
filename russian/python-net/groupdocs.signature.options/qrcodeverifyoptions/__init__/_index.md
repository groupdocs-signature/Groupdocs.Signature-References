---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует параметры проверки для подписей QR-Code."
type: docs
url: /ru/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует параметры проверки для подписей QR-Code.

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions

with Signature("signed.pdf") as signature:
    options = QrCodeVerifyOptions()
    options.text = "John"
    result = signature.verify(options)
    print(f"Verified: {result.is_valid}")
```

## __init__ {#text}

Инициализирует параметры проверки для подписей QR-Code с указанным текстом QR-кода.

```python
def __init__(self, text):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | `str` | Текст QR‑code для проверки. |

### Пример

```python
from groupdocs.signature.options import QrCodeVerifyOptions

# Создайте параметры и задайте текст QR‑code для проверки.
options = QrCodeVerifyOptions()
options.text = "Approved by John Smith"
```

## __init__ {#text-encode_type}

Инициализирует параметры проверки для подписей QR-Code с текстом и типом кодирования QR-Code для проверки.

```python
def __init__(self, text, encode_type):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | `str` | Текст для проверки. |
| encode_type | `QrCodeType` | Тип кодирования. |

### Пример

```python
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeVerifyOptions(text="John Smith", encode_type=QrCodeTypes.QR)
```

### См. также
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/)
