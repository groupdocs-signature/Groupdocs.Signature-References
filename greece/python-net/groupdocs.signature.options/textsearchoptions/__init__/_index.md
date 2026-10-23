---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης TextSearchOptions με προεπιλεγμένες τιμές."
type: docs
url: /el/python-net/groupdocs.signature.options/textsearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης TextSearchOptions με προεπιλεγμένες τιμές.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    # Αναζήτηση υπογραφών κειμένου χρησιμοποιώντας τις προεπιλεγμένες επιλογές
    result = signature.search([TextSearchOptions()])
    for text_signature in result.signatures:
        print(f"Found text signature: {text_signature.text}")
```

## __init__ {#text}

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης TextSearchOptions με μια τιμή κειμένου.

```python
def __init__(self, text):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | `str` | Κείμενο της υπογραφής κειμένου. |

### Δείτε επίσης
* class [`TextSearchOptions`](/signature/python-net/groupdocs.signature.options/textsearchoptions/)
