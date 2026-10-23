---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "ينشئ مثيلاً جديدًا من فئة BarcodeSignOptions بالقيم الافتراضية."
type: docs
url: /ar/python-net/groupdocs.signature.options/barcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلاً جديدًا من فئة BarcodeSignOptions بالقيم الافتراضية.

```python
def __init__(self):
    ...
```

## __init__ {#text}

ينشئ مثيلاً جديدًا من فئة BarcodeSignOptions بالنص.

```python
def __init__(self, text):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | `str` | نص الباركود. |

### مثال

```python
from groupdocs.signature.options import BarcodeSignOptions

# إنشاء خيارات توقيع الباركود بالنص المطلوب
options = BarcodeSignOptions("JohnSmith")
```

## __init__ {#text-encode_type}

ينشئ مثيلاً جديدًا من فئة BarcodeSignOptions بالنص.

```python
def __init__(self, text, encode_type):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | `str` | نص الباركود. |
| encode_type | `BarcodeType` | نوع ترميز الباركود. |

### مثال

```python
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

# إنشاء خيارات توقيع الباركود بالنص والنوع
options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
```

### انظر أيضًا
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
