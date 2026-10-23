---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُنشئ مثيلاً جديدًا من الفئة DigitalVBA باستخدام ملف شهادة."
type: docs
url: /ar/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/
is_root: false
weight: 10
---


## __init__ {#certificate_file_path-password}

يُنشئ مثيلاً جديدًا من الفئة DigitalVBA باستخدام ملف شهادة.

```python
def __init__(self, certificate_file_path, password):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| certificate_file_path | `str` | مسار ملف الشهادة الرقمية. |
| password | `str` | كلمة مرور الشهادة الرقمية. |

### مثال

```python
from groupdocs.signature.domain.extensions import DigitalVBA

# إنشاء امتداد DigitalVBA باستخدام ملف شهادة وكلمة مرور
digital_vba = DigitalVBA("certificate.pfx", "1234567890")
```

## __init__ {#certificate_stream-password}

يُنشئ مثيلاً جديدًا من الفئة DigitalVBA باستخدام تدفق شهادة.

```python
def __init__(self, certificate_stream, password):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase يحتوي على الشهادة الرقمية. |
| password | `str` | كلمة مرور str للشهادة الرقمية. |

### انظر أيضًا
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)
