---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa un PdfTextFormFieldSignature con un nombre predefinido."
type: docs
url: /es/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Inicializa un PdfTextFormFieldSignature con un nombre predefinido.

```python
def __init__(self, name):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| name | `str` | Nombre del objeto de campo de formulario. |

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

## __init__ {#name-text}

Inicializa un PdfTextFormFieldSignature con un nombre predefinido.

```python
def __init__(self, name, text):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| name | `str` | Nombre del objeto de campo de formulario. |
| text | `str` | Texto del objeto de campo de formulario. |

### Ejemplo

```python
from groupdocs.signature.domain import TextFormFieldSignature

# Crea un campo de formulario de texto llamado "FieldText" con el valor "Value1"
text_field = TextFormFieldSignature("FieldText", "Value1")
```

### Ver también
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
