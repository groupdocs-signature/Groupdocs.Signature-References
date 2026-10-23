---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "ينشئ مثيلًا جديدًا من فئة QRCodeSearchOptions بالقيم الافتراضية."
type: docs
url: /ar/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلًا جديدًا من فئة QRCodeSearchOptions بالقيم الافتراضية.

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

## __init__ {#encode_type}

ينشئ مثيلًا جديدًا من فئة QRCodeSearchOptions بقيمة نوع الترميز.

```python
def __init__(self, encode_type):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| encode_type | `QrCodeType` | يحدد نوع تشفير QR-Code. |

## __init__ {#encode_type-text}

يُنشئ مثيلاً جديدًا من الفئة QRCodeSearchOptions مع نوع الترميز وقيم النص.

```python
def __init__(self, encode_type, text):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| encode_type | `QrCodeType` | يحدد نوع تشفير QR-Code. |
| text | `str` | تعيين نص توقيع QR-Code. |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

### انظر أيضًا
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
