---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a new instance of the TextVerifyOptions with default values."
type: docs
url: /python-net/groupdocs.signature.options/textverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the TextVerifyOptions with default values.

```python
def __init__(self):
    ...
```

### Example

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

Initializes a new instance of the TextVerifyOptions with verification text.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | `str` | Text to be verified. |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

## __init__ {#text-implementation}

Initializes a new TextVerifyOptions instance with the text to verify and the signature implementation type.

```python
def __init__(self, text, implementation):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | `str` | Text to be verified. |
| implementation | `TextSignatureImplementation` | Signature implementation type. |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

### See Also
* class [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)
