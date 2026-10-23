---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "ينشئ مثيلاً جديدًا من فئة ImageSignOptions بالقيم الافتراضية."
type: docs
url: /ar/python-net/groupdocs.signature.options/imagesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلاً جديدًا من فئة ImageSignOptions بالقيم الافتراضية.

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.signature.options import ImageSignOptions

# إنشاء خيارات توقيع الصورة باستخدام مسار ملف الصورة
options = ImageSignOptions("signature.jpg")
```

## __init__ {#image_file_path}

ينشئ ImageSignOptions بملف صورة.

```python
def __init__(self, image_file_path):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_file_path | `str` | مسار ملف الصورة. |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    options = ImageSignOptions("signature.jpg")
    # تكوين خيارات إضافية هنا، مثل الموقع، الحجم، إلخ.
    result = signature.sign("signed_image.pdf", options)
    print(f"Signed with {len(result.succeeded)} image signature(s)")
```

## __init__ {#image_stream}

ينشئ مثيلاً جديدًا من ImageSignOptions باستخدام تدفق صورة.

```python
def __init__(self, image_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | دفق الصورة. |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    with open("signature.jpg", "rb") as image_stream:
        options = ImageSignOptions(image_stream)
        options.left = 100
        options.top = 400
        result = signature.sign("signed_image_stream.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### انظر أيضًا
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)
