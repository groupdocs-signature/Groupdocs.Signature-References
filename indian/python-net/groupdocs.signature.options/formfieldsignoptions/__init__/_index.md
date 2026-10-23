---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "PdfFormFieldSignOptions क्लास का एक नया उदाहरण डिफ़ॉल्ट मानों के साथ आरंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

PdfFormFieldSignOptions क्लास का एक नया उदाहरण डिफ़ॉल्ट मानों के साथ आरंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

text_field = TextFormFieldSignature("FieldText", "Value1")
options = FormFieldSignOptions(text_field)
```

## __init__ {#signature}

PdfFormFieldSignOptions क्लास का एक नया उदाहरण FormField हस्ताक्षर के साथ आरंभ करता है।

```python
def __init__(self, signature):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| signature | `FormFieldSignature` | फ़ॉर्म फ़ील्ड हस्ताक्षर ऑब्जेक्ट। |

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

### संबंधित देखें
* class [`FormFieldSignOptions`](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/)
