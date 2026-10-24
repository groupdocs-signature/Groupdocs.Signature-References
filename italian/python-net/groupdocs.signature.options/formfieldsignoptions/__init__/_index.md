---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una nuova istanza della classe PdfFormFieldSignOptions con valori predefiniti."
type: docs
url: /it/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe PdfFormFieldSignOptions con valori predefiniti.

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

text_field = TextFormFieldSignature("FieldText", "Value1")
options = FormFieldSignOptions(text_field)
```

## __init__ {#signature}

Inizializza una nuova istanza della classe PdfFormFieldSignOptions con firma FormField.

```python
def __init__(self, signature):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| signature | `FormFieldSignature` | Oggetto firma Form Field. |

### Esempio

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

### Vedi anche
* class [`FormFieldSignOptions`](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/)
