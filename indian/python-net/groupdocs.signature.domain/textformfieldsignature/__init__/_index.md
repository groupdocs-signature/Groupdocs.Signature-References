---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "एक पूर्वनिर्धारित नाम के साथ PdfTextFormFieldSignature को आरंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

एक पूर्वनिर्धारित नाम के साथ PdfTextFormFieldSignature को आरंभ करता है।

```python
def __init__(self, name):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| name | `str` | फ़ॉर्म फ़ील्ड ऑब्जेक्ट का नाम। |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

with Signature("sample.pdf") as signature:
    text_field = TextFormFieldSignature("FieldText", "Value1")
    options = FormFieldSignOptions(text_field)
    options.left = 100
    options.top = 400
    options.width = 200
    options.height = 20
    result = signature.sign("signed_form_field.pdf", options)
    for field in result.succeeded:
        print(f"Added form field '{field.name}' with value '{field.value}'")
```

## __init__ {#name-text}

एक पूर्वनिर्धारित नाम के साथ PdfTextFormFieldSignature को आरंभ करता है।

```python
def __init__(self, name, text):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| name | `str` | फ़ॉर्म फ़ील्ड ऑब्जेक्ट का नाम। |
| text | `str` | फ़ॉर्म फ़ील्ड ऑब्जेक्ट का टेक्स्ट। |

### उदाहरण

```python
from groupdocs.signature.domain import TextFormFieldSignature

# एक टेक्स्ट फ़ॉर्म फ़ील्ड जिसका नाम "FieldText" है और मान "Value1" है, बनाएं
text_field = TextFormFieldSignature("FieldText", "Value1")
```

### संबंधित देखें
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
