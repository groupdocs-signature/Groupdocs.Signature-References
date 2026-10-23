---
title: "μέθοδος to_single"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Μετατρέπει σε float."
type: docs
url: /el/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/
is_root: false
weight: 1150
---


## to_single

Μετατρέπει σε float.

Ρίχνει μια εξαίρεση εάν η τιμή των Μεταδεδομένων δεν μπορεί να μετατραπεί. Εάν η αρχική τιμή είναι βασισμένη σε συμβολοσειρά, θα χρησιμοποιηθεί η προεπιλεγμένη πληροφορία ιδιότητας πολιτισμού από [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_single(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as float.

## to_single {#provider}

Μετατρέπει την τιμή της μεταδεδομένης υπογραφής σε float.

Εγείρει μια εξαίρεση εάν η τιμή των μεταδεδομένων δεν μπορεί να μετατραπεί.

```python
def to_single(self, provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

**Returns:** float: The metadata signature value as a float.

### Δείτε επίσης
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
