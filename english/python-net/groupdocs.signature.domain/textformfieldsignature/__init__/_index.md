---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a PdfTextFormFieldSignature with a predefined name."
type: docs
url: /python-net/groupdocs.signature.domain/textformfieldsignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initializes a PdfTextFormFieldSignature with a predefined name.

```python
def __init__(self, name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | Name of form field object. |

### Example

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

Initializes a PdfTextFormFieldSignature with a predefined name.

```python
def __init__(self, name, text):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | Name of form field object. |
| text | `str` | Text of form field object. |

### Example

```python
from groupdocs.signature.domain import TextFormFieldSignature

# Create a text form field named "FieldText" with the value "Value1"
text_field = TextFormFieldSignature("FieldText", "Value1")
```

### See Also
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
