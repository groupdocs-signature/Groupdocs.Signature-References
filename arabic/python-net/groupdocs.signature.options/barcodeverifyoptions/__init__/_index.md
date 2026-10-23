---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "ينشئ خيار التحقق الافتراضي لتوقيع الباركود."
type: docs
url: /ar/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ خيار التحقق الافتراضي لتوقيع الباركود.

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.signature.options import BarcodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

options = BarcodeVerifyOptions()
options.text = "12345"
options.match_type = TextMatchType.CONTAINS
```

## __init__ {#text}

ينشئ خيار التحقق الافتراضي مع نص التحقق.

```python
def __init__(self, text):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | `str` | نص الباركود للتحقق منه. |

## __init__ {#encode_type}

ينشئ خيار التحقق الافتراضي مع التحقق من نوع الباركود.

```python
def __init__(self, encode_type):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| encode_type | `BarcodeType` | التحقق من نوع الباركود. |

## __init__ {#text-encode_type}

يُهيئ خيار التحقق الافتراضي مع التحقق من نوع الباركود والنص.

```python
def __init__(self, text, encode_type):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | `str` | نص الباركود للتحقق منه. |
| encode_type | `BarcodeType` | التحقق من نوع الباركود. |

### انظر أيضًا
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/)
