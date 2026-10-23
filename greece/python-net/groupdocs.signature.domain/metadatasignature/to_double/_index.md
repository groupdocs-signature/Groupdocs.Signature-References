---
title: "μέθοδος to_double"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Μετατρέπει την τιμή της μεταδεδομένης υπογραφής σε float."
type: docs
url: /el/python-net/groupdocs.signature.domain/metadatasignature/to_double/
is_root: false
weight: 1130
---


## to_double

Μετατρέπει την τιμή της μεταδεδομένης υπογραφής σε float.

Εγείρει μια εξαίρεση εάν η τιμή μεταδεδομένων δεν μπορεί να μετατραπεί. Εάν η αρχική τιμή είναι συμβολοσειρά, η προεπιλεγμένη πολιτισμική ρύθμιση από [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) χρησιμοποιείται.

```python
def to_double(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_double {#provider}

Μετατρέπει σε Double.

```python
def to_double(self, provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

**Returns:** float: The metadata signature value as a float.

### Δείτε επίσης
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
