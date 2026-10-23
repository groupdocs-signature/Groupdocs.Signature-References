---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "बारकोड हस्ताक्षर के लिए डिफ़ॉल्ट सत्यापन विकल्प आरंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

बारकोड हस्ताक्षर के लिए डिफ़ॉल्ट सत्यापन विकल्प आरंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.signature.options import BarcodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

options = BarcodeVerifyOptions()
options.text = "12345"
options.match_type = TextMatchType.CONTAINS
```

## __init__ {#text}

सत्यापन पाठ के साथ डिफ़ॉल्ट सत्यापन विकल्प आरंभ करता है।

```python
def __init__(self, text):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | `str` | बारकोड टेक्स्ट को सत्यापित करने के लिए। |

## __init__ {#encode_type}

बारकोड प्रकार सत्यापन के साथ डिफ़ॉल्ट सत्यापन विकल्प आरंभ करता है।

```python
def __init__(self, encode_type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| encode_type | `BarcodeType` | बारकोड प्रकार सत्यापन। |

## __init__ {#text-encode_type}

डिफ़ॉल्ट सत्यापन विकल्प को बारकोड प्रकार सत्यापन और टेक्स्ट के साथ प्रारंभ करता है।

```python
def __init__(self, text, encode_type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | `str` | बारकोड टेक्स्ट को सत्यापित करने के लिए। |
| encode_type | `BarcodeType` | बारकोड प्रकार सत्यापन। |

### संबंधित देखें
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/)
