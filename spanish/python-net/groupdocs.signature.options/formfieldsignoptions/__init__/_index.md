---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase PdfFormFieldSignOptions con valores predeterminados."
type: docs
url: /es/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase PdfFormFieldSignOptions con valores predeterminados.

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

text_field = TextFormFieldSignature("FieldText", "Value1")
options = FormFieldSignOptions(text_field)
```

## __init__ {#signature}

Inicializa una nueva instancia de la clase PdfFormFieldSignOptions con una firma FormField.

```python
def __init__(self, signature):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| signature | `FormFieldSignature` | Objeto de firma de campo de formulario. |

### Ejemplo

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

### Ver también
* class [`FormFieldSignOptions`](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/)
