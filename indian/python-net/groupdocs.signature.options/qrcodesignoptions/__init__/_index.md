---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिफ़ॉल्ट मानों के साथ QRCodeSignOptions वर्ग का एक नया इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

डिफ़ॉल्ट मानों के साथ QRCodeSignOptions वर्ग का एक नया इंस्टेंस प्रारंभ करता है।

```python
def __init__(self):
    ...
```

## __init__ {#text}

निर्दिष्ट टेक्स्ट के साथ QR कोड सिग्नेचर विकल्पों का एक इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, text):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | `str` | हस्ताक्षर पाठ। |

### उदाहरण

```python
from groupdocs.signature.options import QrCodeSignOptions

# इच्छित टेक्स्ट के साथ QR कोड हस्ताक्षर विकल्प बनाएं
options = QrCodeSignOptions("Approved by John Smith")
```

## __init__ {#text-encode_type}

टेक्स्ट के साथ QrCodeSignOptions वर्ग का एक नया इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, text, encode_type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | `str` | QRCode टेक्स्ट। |
| encode_type | `QrCodeType` | QRCode एन्कोड प्रकार। |

### उदाहरण

```python
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeSignOptions(
    "https://www.example.com/verify-document",
    QrCodeTypes.QR
)
```

### संबंधित देखें
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
