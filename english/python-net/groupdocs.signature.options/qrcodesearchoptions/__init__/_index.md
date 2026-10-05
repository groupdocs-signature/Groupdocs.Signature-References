---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a new instance of the QRCodeSearchOptions class with default values."
type: docs
url: /python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the QRCodeSearchOptions class with default values.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

## __init__ {#encode_type}

Initializes a new instance of the QRCodeSearchOptions class with encode type value.

```python
def __init__(self, encode_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| encode_type | `QrCodeType` | Specifies QR-Code encode type. |

## __init__ {#encode_type-text}

Initializes a new instance of the QRCodeSearchOptions class with encode type and text values.

```python
def __init__(self, encode_type, text):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| encode_type | `QrCodeType` | Specifies QR-Code encode type. |
| text | `str` | Set text of QR-Code signature. |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

### See Also
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
