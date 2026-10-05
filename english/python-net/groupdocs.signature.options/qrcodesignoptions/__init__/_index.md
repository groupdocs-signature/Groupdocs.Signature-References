---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a new instance of the QRCodeSignOptions class with default values."
type: docs
url: /python-net/groupdocs.signature.options/qrcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the QRCodeSignOptions class with default values.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Initializes a QR code signature options instance with the specified text.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | `str` | Signature text. |

### Example

```python
from groupdocs.signature.options import QrCodeSignOptions

# Create QR code signature options with the desired text
options = QrCodeSignOptions("Approved by John Smith")
```

## __init__ {#text-encode_type}

Initializes a new instance of the QrCodeSignOptions class with text.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | `str` | QRCode text. |
| encode_type | `QrCodeType` | QRCode encode type. |

### Example

```python
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeSignOptions(
    "https://www.example.com/verify-document",
    QrCodeTypes.QR
)
```

### See Also
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
