---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια υπογραφή μεταδεδομένων PDF με προκαθορισμένο όνομα και κενή τιμή."
type: docs
url: /el/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Αρχικοποιεί μια υπογραφή μεταδεδομένων PDF με προκαθορισμένο όνομα και κενή τιμή.

```python
def __init__(self, name):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| name | `str` | Όνομα υπογραφής μεταδεδομένων PDF. |

## __init__ {#name-value}

Αρχικοποιεί μια υπογραφή μεταδεδομένων PDF με προκαθορισμένες τιμές.

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
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr. Sherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
```

## __init__ {#name-value-tag}

Αρχικοποιεί μια υπογραφή μεταδεδομένων PDF με προκαθορισμένες τιμές.

```python
def __init__(self, name, value, tag):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| name | `str` | Όνομα του αντικειμένου υπογραφής μεταδεδομένων. |
| value | `Any` | Τιμή της υπογραφής μεταδεδομένων. |
| tag | `str` | Ετικέτα προθέματος της υπογραφής μεταδεδομένων. |

### Παράδειγμα

```python
from groupdocs.signature.domain import PdfMetadataSignature

# Δημιουργήστε μια υπογραφή μεταδεδομένων για τον συγγραφέα PDF
author_sig = PdfMetadataSignature("Author", "Mr. Sherlock Holmes")

# Δημιουργήστε μια υπογραφή μεταδεδομένων για την ημερομηνία δημιουργίας
from datetime import datetime
created_sig = PdfMetadataSignature("CreatedOn", datetime.now())

# Δημιουργήστε μια υπογραφή μεταδεδομένων για έναν αριθμητικό αναγνωριστικό
id_sig = PdfMetadataSignature("DocumentId", 123456)

# Δημιουργήστε μια υπογραφή μεταδεδομένων για μια τιμή κινητής υποδιαστολής
float_sig = PdfMetadataSignature("SignatureId", 123.456)
```

### Δείτε επίσης
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
