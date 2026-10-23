---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُهيئ خيارات التحقق لتواقيع QR-Code."
type: docs
url: /ar/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

يُهيئ خيارات التحقق لتواقيع QR-Code.

```python
def __init__(self):
    ...
```

### مثال

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

يُهيئ خيارات التحقق لتواقيع QR-Code بالنص المحدد لرمز QR.

```python
def __init__(self, text):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | `str` | نص QR-code للتحقق. |

### مثال

```python
from groupdocs.signature.options import QrCodeVerifyOptions

# إنشاء الخيارات وتعيين نص QR-code للتحقق
options = QrCodeVerifyOptions()
options.text = "Approved by John Smith"
```

## __init__ {#text-encode_type}

يُهيئ خيارات التحقق لتواقيع QR-Code بالنص ونوع ترميز QR-Code للتحقق.

```python
def __init__(self, text, encode_type):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | `str` | النص المراد التحقق منه. |
| encode_type | `QrCodeType` | نوع الترميز. |

### مثال

```python
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeVerifyOptions(text="John Smith", encode_type=QrCodeTypes.QR)
```

### انظر أيضًا
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/)
