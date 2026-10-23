---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "ينشئ مثيلاً جديداً من فئة PdfFormFieldSignOptions بالقيم الافتراضية."
type: docs
url: /ar/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلاً جديداً من فئة PdfFormFieldSignOptions بالقيم الافتراضية.

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

text_field = TextFormFieldSignature("FieldText", "Value1")
options = FormFieldSignOptions(text_field)
```

## __init__ {#signature}

ينشئ مثيلاً جديداً من فئة PdfFormFieldSignOptions بتوقيع FormField.

```python
def __init__(self, signature):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| signature | `FormFieldSignature` | كائن توقيع حقل النموذج. |

### مثال

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

### انظر أيضًا
* class [`FormFieldSignOptions`](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/)
