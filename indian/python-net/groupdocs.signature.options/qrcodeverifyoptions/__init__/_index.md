---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "QR-कोड हस्ताक्षरों के लिए सत्यापन विकल्पों को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

QR-कोड हस्ताक्षरों के लिए सत्यापन विकल्पों को प्रारंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

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

निर्दिष्ट QR-कोड पाठ के साथ QR-कोड हस्ताक्षरों के लिए सत्यापन विकल्पों को प्रारंभ करता है।

```python
def __init__(self, text):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | `str` | सत्यापन के लिए QR-code टेक्स्ट। |

### उदाहरण

```python
from groupdocs.signature.options import QrCodeVerifyOptions

# विकल्प बनाएं और सत्यापन के लिए QR-code टेक्स्ट सेट करें
options = QrCodeVerifyOptions()
options.text = "Approved by John Smith"
```

## __init__ {#text-encode_type}

पाठ और सत्यापन के लिए QR-कोड एन्कोड प्रकार के साथ QR-कोड हस्ताक्षरों के लिए सत्यापन विकल्पों को प्रारंभ करता है।

```python
def __init__(self, text, encode_type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | `str` | सत्यापित किया जाने वाला टेक्स्ट। |
| encode_type | `QrCodeType` | एन्कोडिंग का प्रकार। |

### उदाहरण

```python
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeVerifyOptions(text="John Smith", encode_type=QrCodeTypes.QR)
```

### संबंधित देखें
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/)
