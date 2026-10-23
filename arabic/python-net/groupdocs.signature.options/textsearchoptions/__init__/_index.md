---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "ينشئ مثيلاً جديداً من فئة TextSearchOptions بالقيم الافتراضية."
type: docs
url: /ar/python-net/groupdocs.signature.options/textsearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلاً جديداً من فئة TextSearchOptions بالقيم الافتراضية.

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    # ابحث عن توقيعات النص باستخدام الخيارات الافتراضية
    result = signature.search([TextSearchOptions()])
    for text_signature in result.signatures:
        print(f"Found text signature: {text_signature.text}")
```

## __init__ {#text}

ينشئ مثيلاً جديداً من فئة TextSearchOptions بقيمة نصية.

```python
def __init__(self, text):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | `str` | نص توقيع النص. |

### انظر أيضًا
* class [`TextSearchOptions`](/signature/python-net/groupdocs.signature.options/textsearchoptions/)
