---
title: "μέθοδος to_string"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Μετατρέπει την τιμή της υπογραφής μεταδεδομένων σε συμβολοσειρά χρησιμοποιώντας τη υπερκαλυμμένη μέθοδο ToString."
type: docs
url: /el/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Μετατρέπει την τιμή της υπογραφής μεταδεδομένων σε συμβολοσειρά χρησιμοποιώντας τη υπερκαλυμμένη μέθοδο `ToString`.

Μετατρέπει μια λογική ιδιότητα σε `True` ή `False`. Για άλλους τύπους δεδομένων, χρησιμοποιείται ο προεπιλεγμένος πάροχος μορφοποίησης δεδομένων.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Μετατρέπει τη μεταδεδομένη υπογραφή σε συμβολοσειρά χρησιμοποιώντας την καθορισμένη μορφή.

Μετατρέπει μια ιδιότητα boolean σε "True" ή "False".

```python
def to_string(self, format, provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| format | `str` | Συμβολοσειρά μορφοποίησης δεδομένων. |
| provider | `System.IFormatProvider` | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

**Returns:** str: The metadata signature value as a string.

### Δείτε επίσης
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
