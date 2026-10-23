---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिफ़ॉल्ट मानों के साथ TextSearchOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/textsearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

डिफ़ॉल्ट मानों के साथ TextSearchOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    # डिफ़ॉल्ट विकल्पों का उपयोग करके टेक्स्ट सिग्नेचर खोजें
    result = signature.search([TextSearchOptions()])
    for text_signature in result.signatures:
        print(f"Found text signature: {text_signature.text}")
```

## __init__ {#text}

टेक्स्ट मान के साथ TextSearchOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self, text):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | `str` | टेक्स्ट सिग्नेचर का टेक्स्ट। |

### संबंधित देखें
* class [`TextSearchOptions`](/signature/python-net/groupdocs.signature.options/textsearchoptions/)
