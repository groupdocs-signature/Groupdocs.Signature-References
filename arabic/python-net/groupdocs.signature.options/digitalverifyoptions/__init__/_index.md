---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُهيئ مثيل DigitalVerifyOptions بالقيم الافتراضية."
type: docs
url: /ar/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

يُهيئ مثيل DigitalVerifyOptions بالقيم الافتراضية.

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

with Signature("signed.pdf") as signature:
    options = DigitalVerifyOptions("certificate.pfx")
    options.password = "1234567890"
    result = signature.verify(options)
    print(f"Verification result: {result.is_valid}")
```

## __init__ {#certificate_file_path}

يُهيئ مثيل DigitalVerifyOptions بمسار ملف الشهادة الرقمية المحدد.

```python
def __init__(self, certificate_file_path):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| certificate_file_path | `str` | مسار الملف إلى الشهادة الرقمية. |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

options = DigitalVerifyOptions("certificate.pfx")
options.password = "1234567890"
```

## __init__ {#certificate_stream}

يُهيئ مثيل DigitalVerifyOptions بتدفق الشهادة المحدد.

```python
def __init__(self, certificate_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | دفق الشهادة. |

### انظر أيضًا
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
