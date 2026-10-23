---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिफ़ॉल्ट मानों के साथ QRCodeSearchOptions क्लास का नया इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

डिफ़ॉल्ट मानों के साथ QRCodeSearchOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

## __init__ {#encode_type}

एन्कोड प्रकार मान के साथ QRCodeSearchOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, encode_type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| encode_type | `QrCodeType` | QR-Code एन्कोड प्रकार निर्दिष्ट करता है। |

## __init__ {#encode_type-text}

QRCodeSearchOptions क्लास का नया उदाहरण एन्कोड प्रकार और टेक्स्ट मानों के साथ आरंभ करता है।

```python
def __init__(self, encode_type, text):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| encode_type | `QrCodeType` | QR-Code एन्कोड प्रकार निर्दिष्ट करता है। |
| text | `str` | QR-Code हस्ताक्षर का पाठ सेट करें। |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

### संबंधित देखें
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
