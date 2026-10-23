---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُهيئ PdfTextFormFieldSignature باسم محدد مسبقًا."
type: docs
url: /ar/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

يُهيئ PdfTextFormFieldSignature باسم محدد مسبقًا.

```python
def __init__(self, name):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| name | `str` | اسم كائن حقل النموذج. |

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

## __init__ {#name-text}

يُهيئ PdfTextFormFieldSignature باسم محدد مسبقًا.

```python
def __init__(self, name, text):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| name | `str` | اسم كائن حقل النموذج. |
| text | `str` | نص كائن حقل النموذج. |

### مثال

```python
from groupdocs.signature.domain import TextFormFieldSignature

# إنشاء حقل نموذج نصي باسم "FieldText" بالقيمة "Value1"
text_field = TextFormFieldSignature("FieldText", "Value1")
```

### انظر أيضًا
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
