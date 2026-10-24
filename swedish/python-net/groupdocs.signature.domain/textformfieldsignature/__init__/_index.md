---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en PdfTextFormFieldSignature med ett fördefinierat namn."
type: docs
url: /sv/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initierar en PdfTextFormFieldSignature med ett fördefinierat namn.

```python
def __init__(self, name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| name | `str` | Namn på formulärfältobjekt. |

### Exempel

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

Initierar en PdfTextFormFieldSignature med ett fördefinierat namn.

```python
def __init__(self, name, text):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| name | `str` | Namn på formulärfältobjekt. |
| text | `str` | Text för formulärfältobjekt. |

### Exempel

```python
from groupdocs.signature.domain import TextFormFieldSignature

# Skapa ett textformulärfält med namnet "FieldText" och värdet "Value1"
text_field = TextFormFieldSignature("FieldText", "Value1")
```

### Se även
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
