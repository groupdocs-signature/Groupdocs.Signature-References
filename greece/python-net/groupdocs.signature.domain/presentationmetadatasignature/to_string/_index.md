---
title: "μέθοδος to_string"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Μετατρέπει τη μεταδεδομένη υπογραφή σε συμβολοσειρά."
type: docs
url: /el/python-net/groupdocs.signature.domain/presentationmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Μετατρέπει τη μεταδεδομένη υπογραφή σε συμβολοσειρά.

Μετατρέπει μια λογική ιδιότητα σε "True" ή "False". Για άλλους τύπους δεδομένων χρησιμοποιείται ο προεπιλεγμένος πάροχος μορφής δεδομένων.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Μετατρέπει σε συμβολοσειρά με καθορισμένη μορφή.

Μετατρέπει μια ιδιότητα boolean σε "True" ή "False".

```python
def to_string(self, format, provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| format | `str` | Συμβολοσειρά μορφοποίησης δεδομένων. |
| provider | `System.IFormatProvider` | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

**Returns:** str: The metadata signature value as string.

### Δείτε επίσης
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
