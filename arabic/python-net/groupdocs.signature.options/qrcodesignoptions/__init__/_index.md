---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "ينشئ كائنًا جديدًا من فئة QRCodeSignOptions بالقيم الافتراضية."
type: docs
url: /ar/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ كائنًا جديدًا من فئة QRCodeSignOptions بالقيم الافتراضية.

```python
def __init__(self):
    ...
```

## __init__ {#text}

ينشئ كائنًا من خيارات توقيع رمز الاستجابة السريعة بالنص المحدد.

```python
def __init__(self, text):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | `str` | نص التوقيع. |

### مثال

```python
from groupdocs.signature.options import QrCodeSignOptions

# إنشاء خيارات توقيع QR code بالنص المطلوب
options = QrCodeSignOptions("Approved by John Smith")
```

## __init__ {#text-encode_type}

ينشئ كائنًا جديدًا من فئة QrCodeSignOptions بالنص.

```python
def __init__(self, text, encode_type):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | `str` | نص QRCode. |
| encode_type | `QrCodeType` | نوع ترميز QRCode. |

### مثال

```python
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeSignOptions(
    "https://www.example.com/verify-document",
    QrCodeTypes.QR
)
```

### انظر أيضًا
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
