---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise un PdfTextFormFieldSignature avec un nom prédéfini."
type: docs
url: /fr/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initialise un PdfTextFormFieldSignature avec un nom prédéfini.

```python
def __init__(self, name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| name | `str` | Nom de l'objet champ de formulaire. |

### Exemple

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

Initialise un PdfTextFormFieldSignature avec un nom prédéfini.

```python
def __init__(self, name, text):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| name | `str` | Nom de l'objet champ de formulaire. |
| text | `str` | Texte de l'objet champ de formulaire. |

### Exemple

```python
from groupdocs.signature.domain import TextFormFieldSignature

# Créez un champ de texte nommé "FieldText" avec la valeur "Value1"
text_field = TextFormFieldSignature("FieldText", "Value1")
```

### Voir aussi
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
