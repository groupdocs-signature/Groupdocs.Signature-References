---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert ein PdfTextFormFieldSignature mit einem vordefinierten Namen."
type: docs
url: /de/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initialisiert ein PdfTextFormFieldSignature mit einem vordefinierten Namen.

```python
def __init__(self, name):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| name | `str` | Name des Formularfeldobjekts. |

### Beispiel

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

Initialisiert ein PdfTextFormFieldSignature mit einem vordefinierten Namen.

```python
def __init__(self, name, text):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| name | `str` | Name des Formularfeldobjekts. |
| text | `str` | Text des Formularfeld-Objekts. |

### Beispiel

```python
from groupdocs.signature.domain import TextFormFieldSignature

# Erstelle ein Textformularfeld mit dem Namen "FieldText" und dem Wert "Value1"
text_field = TextFormFieldSignature("FieldText", "Value1")
```

### Siehe auch
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
