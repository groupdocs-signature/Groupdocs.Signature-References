---
title: "μέθοδος to_double"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Μετατρέπει σε float."
type: docs
url: /el/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/
is_root: false
weight: 1110
---


## to_double

Μετατρέπει σε float.

Αναφέρει μια εξαίρεση εάν η τιμή metadata δεν μπορεί να μετατραπεί. Εάν η αρχική τιμή είναι συμβολοσειρά‑βασισμένη, χρησιμοποιείται η προεπιλεγμένη κουλτούρα από [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_double(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as a float.

## to_double {#provider}

Μετατρέπει την τιμή της μεταδεδομένης υπογραφής σε float.

Χρησιμοποιεί τον καθορισμένο πάροχο μορφής δεδομένων για την εκτέλεση της μετατροπής.

```python
def to_double(self, provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

**Returns:** float: The metadata signature value as a float.

### Δείτε επίσης
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
