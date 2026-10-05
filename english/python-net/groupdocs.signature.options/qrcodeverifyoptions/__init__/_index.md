---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes verification options for QR-Code signatures."
type: docs
url: /python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes verification options for QR-Code signatures.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions

with Signature("signed.pdf") as signature:
    options = QrCodeVerifyOptions()
    options.text = "John"
    result = signature.verify(options)
    print(f"Verified: {result.is_valid}")
```

## __init__ {#text}

Initializes verification options for QR-Code signatures with the specified QR-code text.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | `str` | QR-code text to verify. |

### Example

```python
from groupdocs.signature.options import QrCodeVerifyOptions

# Create options and set the QR-code text to verify
options = QrCodeVerifyOptions()
options.text = "Approved by John Smith"
```

## __init__ {#text-encode_type}

Initializes verification options for QR-Code signatures with text and QR-Code encode type to verify.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | `str` | Text to be verified. |
| encode_type | `QrCodeType` | Type of encoding. |

### Example

```python
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeVerifyOptions(text="John Smith", encode_type=QrCodeTypes.QR)
```

### See Also
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/)
