---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί την Υπογραφή Μεταδεδομένων Φύλλου Εργασίας με προκαθορισμένο όνομα και κενή τιμή."
type: docs
url: /el/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Αρχικοποιεί την Υπογραφή Μεταδεδομένων Φύλλου Εργασίας με προκαθορισμένο όνομα και κενή τιμή.

```python
def __init__(self, name):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| name | `str` | Όνομα υπογραφής μεταδεδομένων λογιστικού φύλλου. |

## __init__ {#name-value}

Αρχικοποιεί μια Υπογραφή Μεταδεδομένων Φύλλου Εργασίας με προκαθορισμένες τιμές.

```python
def __init__(self, name, value):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| name | `str` | Όνομα του αντικειμένου υπογραφής μεταδεδομένων. |
| value | `Any` | Τιμή της υπογραφής μεταδεδομένων. |

### Παράδειγμα

```python
from datetime import datetime
from groupdocs.signature.domain import SpreadsheetMetadataSignature

# Δημιουργήστε υπογραφές μεταδεδομένων για ένα λογιστικό φύλλο
author_sig = SpreadsheetMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = SpreadsheetMetadataSignature("DateCreated", datetime.now())
id_sig = SpreadsheetMetadataSignature("DocumentId", 123456)
float_sig = SpreadsheetMetadataSignature("SignatureId", 123.456)
```

### Δείτε επίσης
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
