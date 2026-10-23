---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "ينشئ مثيلاً جديداً من TextVerifyOptions بالقيم الافتراضية."
type: docs
url: /ar/python-net/groupdocs.signature.options/textverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلاً جديداً من TextVerifyOptions بالقيم الافتراضية.

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## __init__ {#text}

ينشئ مثيلاً جديداً من TextVerifyOptions بنص التحقق.

```python
def __init__(self, text):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | `str` | النص المراد التحقق منه. |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

## __init__ {#text-implementation}

ينشئ مثيلاً جديداً من TextVerifyOptions بالنص المراد التحقق منه ونوع تنفيذ التوقيع.

```python
def __init__(self, text, implementation):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | `str` | النص المراد التحقق منه. |
| implementation | `TextSignatureImplementation` | نوع تنفيذ التوقيع. |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

### انظر أيضًا
* class [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)
