---
title: "μέθοδος to_string"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Μετατρέπει την υπογραφή μεταδεδομένων σε συμβολοσειρά χρησιμοποιώντας τη υπερκαλυπτική μέθοδο ToString."
type: docs
url: /el/python-net/groupdocs.signature.domain/certificatemetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Μετατρέπει την υπογραφή μεταδεδομένων σε συμβολοσειρά χρησιμοποιώντας τη υπερκαλυπτική μέθοδο ToString.

Μετατρέπει μια λογική ιδιότητα σε "True" ή "False". Για άλλους τύπους δεδομένων χρησιμοποιείται ο προεπιλεγμένος πάροχος μορφής δεδομένων.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Μετατρέπει σε συμβολοσειρά με το καθορισμένο μορφότυπο.

Μετατρέπει μια ιδιότητα boolean σε "True" ή "False".

```python
def to_string(self, format, provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| format | `str` | Συμβολοσειρά μορφοποίησης δεδομένων. |
| provider | `System.IFormatProvider` | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

**Returns:** The metadata signature value as a string.

### Δείτε επίσης
* class [`CertificateMetadataSignature`](/signature/python-net/groupdocs.signature.domain/certificatemetadatasignature/)
