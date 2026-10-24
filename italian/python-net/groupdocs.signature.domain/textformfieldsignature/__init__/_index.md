---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza un PdfTextFormFieldSignature con un nome predefinito."
type: docs
url: /it/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Inizializza un PdfTextFormFieldSignature con un nome predefinito.

```python
def __init__(self, name):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| name | `str` | Nome dell'oggetto campo modulo. |

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

## __init__ {#name-text}

Inizializza un PdfTextFormFieldSignature con un nome predefinito.

```python
def __init__(self, name, text):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| name | `str` | Nome dell'oggetto campo modulo. |
| text | `str` | Testo dell'oggetto campo modulo. |

### Esempio

```python
from groupdocs.signature.domain import TextFormFieldSignature

# Crea un campo di testo denominato "FieldText" con il valore "Value1"
text_field = TextFormFieldSignature("FieldText", "Value1")
```

### Vedi anche
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
