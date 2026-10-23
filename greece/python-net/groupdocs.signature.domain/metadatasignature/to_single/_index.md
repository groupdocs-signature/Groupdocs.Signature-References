---
title: "μέθοδος to_single"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Μετατρέπει την τιμή της μεταδεδομένης υπογραφής σε float."
type: docs
url: /el/python-net/groupdocs.signature.domain/metadatasignature/to_single/
is_root: false
weight: 1160
---


## to_single

Μετατρέπει την τιμή της μεταδεδομένης υπογραφής σε float.

Αναφέρει μια εξαίρεση εάν η τιμή metadata δεν μπορεί να μετατραπεί. Εάν η αρχική τιμή είναι συμβολοσειρά‑βασισμένη, χρησιμοποιείται η προεπιλεγμένη κουλτούρα από [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_single(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_single {#provider}

Μετατρέπει σε float.

```python
def to_single(self, provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

**Returns:** float: The Metadata Signature value as float.

### Δείτε επίσης
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
