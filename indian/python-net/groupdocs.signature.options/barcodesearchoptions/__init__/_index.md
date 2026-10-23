---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिफ़ॉल्ट मानों के साथ BarcodeSearchOptions क्लास का नया इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

डिफ़ॉल्ट मानों के साथ BarcodeSearchOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.signature.options import BarcodeSearchOptions

# डिफ़ॉल्ट सेटिंग्स के साथ एक सर्च विकल्प ऑब्जेक्ट बनाएं
options = BarcodeSearchOptions()
```

## __init__ {#encode_type}

एन्कोड प्रकार मान के साथ BarcodeSearchOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, encode_type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| encode_type | `BarcodeType` | Barcode एन्कोड प्रकार निर्दिष्ट करता है। |

## __init__ {#encode_type-text}

एन्कोड प्रकार और टेक्स्ट मानों के साथ BarcodeSearchOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, encode_type, text):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| encode_type | `BarcodeType` | Barcode एन्कोड प्रकार निर्दिष्ट करता है। |
| text | `str` | Barcode सिग्नेचर का टेक्स्ट सेट करें। |

### संबंधित देखें
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
