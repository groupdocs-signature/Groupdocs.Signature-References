---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिफ़ॉल्ट मानों के साथ BarcodeSignOptions क्लास का एक नया उदाहरण आरंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/barcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

डिफ़ॉल्ट मानों के साथ BarcodeSignOptions क्लास का एक नया उदाहरण आरंभ करता है।

```python
def __init__(self):
    ...
```

## __init__ {#text}

पाठ के साथ BarcodeSignOptions क्लास का एक नया उदाहरण आरंभ करता है।

```python
def __init__(self, text):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | `str` | बारकोड पाठ। |

### उदाहरण

```python
from groupdocs.signature.options import BarcodeSignOptions

# इच्छित पाठ के साथ बारकोड सिग्नेचर विकल्प बनाएं
options = BarcodeSignOptions("JohnSmith")
```

## __init__ {#text-encode_type}

पाठ के साथ BarcodeSignOptions क्लास का एक नया उदाहरण आरंभ करता है।

```python
def __init__(self, text, encode_type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | `str` | बारकोड पाठ। |
| encode_type | `BarcodeType` | बारकोड एन्कोड प्रकार। |

### उदाहरण

```python
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

# पाठ और प्रकार के साथ बारकोड सिग्नेचर विकल्प बनाएं
options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
```

### संबंधित देखें
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
