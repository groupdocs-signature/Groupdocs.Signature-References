---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "TextVerifyOptions का एक नया उदाहरण डिफ़ॉल्ट मानों के साथ आरंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/textverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

TextVerifyOptions का एक नया उदाहरण डिफ़ॉल्ट मानों के साथ आरंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## __init__ {#text}

TextVerifyOptions का एक नया उदाहरण सत्यापन पाठ के साथ आरंभ करता है।

```python
def __init__(self, text):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | `str` | सत्यापित किया जाने वाला टेक्स्ट। |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

## __init__ {#text-implementation}

सत्यापित करने के पाठ और हस्ताक्षर कार्यान्वयन प्रकार के साथ एक नया TextVerifyOptions उदाहरण आरंभ करता है।

```python
def __init__(self, text, implementation):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | `str` | सत्यापित किया जाने वाला टेक्स्ट। |
| implementation | `TextSignatureImplementation` | सिग्नेचर इम्प्लीमेंटेशन प्रकार। |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

### संबंधित देखें
* class [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)
