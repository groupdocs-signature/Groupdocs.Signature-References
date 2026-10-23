---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُنشئ مثلاً جديداً من فئة BarcodeSearchOptions بالقيم الافتراضية."
type: docs
url: /ar/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

يُنشئ مثلاً جديداً من فئة BarcodeSearchOptions بالقيم الافتراضية.

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.signature.options import BarcodeSearchOptions

# إنشاء كائن خيارات البحث بالإعدادات الافتراضية
options = BarcodeSearchOptions()
```

## __init__ {#encode_type}

يُنشئ مثلاً جديداً من فئة BarcodeSearchOptions بقيمة نوع الترميز.

```python
def __init__(self, encode_type):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| encode_type | `BarcodeType` | يحدد نوع ترميز الباركود. |

## __init__ {#encode_type-text}

يُنشئ مثلاً جديداً من فئة BarcodeSearchOptions بقيم نوع الترميز والنص.

```python
def __init__(self, encode_type, text):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| encode_type | `BarcodeType` | يحدد نوع ترميز الباركود. |
| text | `str` | تعيين النص لتوقيع الباركود. |

### انظر أيضًا
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
