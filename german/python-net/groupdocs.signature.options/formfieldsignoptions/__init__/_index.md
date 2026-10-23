---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der PdfFormFieldSignOptions‑Klasse mit Standardwerten."
type: docs
url: /de/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der PdfFormFieldSignOptions‑Klasse mit Standardwerten.

```python
def __init__(self):
    ...
```

### Beispiel

```python
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

text_field = TextFormFieldSignature("FieldText", "Value1")
options = FormFieldSignOptions(text_field)
```

## __init__ {#signature}

Initialisiert eine neue Instanz der PdfFormFieldSignOptions‑Klasse mit einer Formularfeld‑Signatur.

```python
def __init__(self, signature):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| signature | `FormFieldSignature` | Formularfeldsignatur-Objekt. |

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

### Siehe auch
* class [`FormFieldSignOptions`](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/)
