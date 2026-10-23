---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिफ़ॉल्ट मानों के साथ TextSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/textsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

डिफ़ॉल्ट मानों के साथ TextSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

```python
def __init__(self):
    ...
```

## __init__ {#text}

टेक्स्ट के साथ TextSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, text):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | `str` | हस्ताक्षर पाठ। |

### उदाहरण

```python
from groupdocs.signature.options import TextSignOptions

# इच्छित हस्ताक्षर पाठ के साथ एक टेक्स्ट हस्ताक्षर विकल्प बनाएं
options = TextSignOptions("John Smith")
```

### संबंधित देखें
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)
