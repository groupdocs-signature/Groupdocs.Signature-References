---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα PdfTextFormFieldSignature με προκαθορισμένο όνομα."
type: docs
url: /el/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Αρχικοποιεί ένα PdfTextFormFieldSignature με προκαθορισμένο όνομα.

```python
def __init__(self, name):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| name | `str` | Όνομα του αντικειμένου πεδίου φόρμας. |

### Παράδειγμα

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

Αρχικοποιεί ένα PdfTextFormFieldSignature με προκαθορισμένο όνομα.

```python
def __init__(self, name, text):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| name | `str` | Όνομα του αντικειμένου πεδίου φόρμας. |
| text | `str` | Κείμενο αντικειμένου πεδίου φόρμας. |

### Παράδειγμα

```python
from groupdocs.signature.domain import TextFormFieldSignature

# Δημιουργήστε ένα πεδίο κειμένου με όνομα "FieldText" και τιμή "Value1"
text_field = TextFormFieldSignature("FieldText", "Value1")
```

### Δείτε επίσης
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
