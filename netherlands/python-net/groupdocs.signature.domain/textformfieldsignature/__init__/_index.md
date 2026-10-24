---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een PdfTextFormFieldSignature met een vooraf gedefinieerde naam."
type: docs
url: /nl/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initialiseert een PdfTextFormFieldSignature met een vooraf gedefinieerde naam.

```python
def __init__(self, name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| name | `str` | Naam van formulierveldobject. |

### Voorbeeld

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

Initialiseert een PdfTextFormFieldSignature met een vooraf gedefinieerde naam.

```python
def __init__(self, name, text):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| name | `str` | Naam van formulierveldobject. |
| text | `str` | Tekst van formulier-veldobject. |

### Voorbeeld

```python
from groupdocs.signature.domain import TextFormFieldSignature

# Maak een tekstformulierveld met de naam "FieldText" en de waarde "Value1"
text_field = TextFormFieldSignature("FieldText", "Value1")
```

### Zie ook
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
