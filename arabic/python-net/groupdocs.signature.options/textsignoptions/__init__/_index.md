---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "ينشئ مثيلاً جديدًا من فئة TextSignOptions بالقيم الافتراضية."
type: docs
url: /ar/python-net/groupdocs.signature.options/textsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلاً جديدًا من فئة TextSignOptions بالقيم الافتراضية.

```python
def __init__(self):
    ...
```

## __init__ {#text}

ينشئ مثيلاً جديدًا من فئة TextSignOptions بالنص.

```python
def __init__(self, text):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | `str` | نص التوقيع. |

### مثال

```python
from groupdocs.signature.options import TextSignOptions

# إنشاء خيار توقيع نصي مع نص التوقيع المطلوب
options = TextSignOptions("John Smith")
```

### انظر أيضًا
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)
