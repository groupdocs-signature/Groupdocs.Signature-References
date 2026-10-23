---
title: "μέθοδος to_date_time"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Μετατρέπει την τιμή της υπογραφής μεταδεδομένων σε datetime.datetime."
type: docs
url: /el/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/
is_root: false
weight: 1070
---


## to_date_time

Μετατρέπει την τιμή της υπογραφής μεταδεδομένων σε `datetime.datetime`.

Αναφέρει μια εξαίρεση εάν η τιμή metadata δεν μπορεί να μετατραπεί. Εάν η αρχική τιμή είναι συμβολοσειρά‑βασισμένη, χρησιμοποιείται η προεπιλεγμένη κουλτούρα από [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_date_time(self):
    ...
```

**Returns:** datetime.datetime: The metadata signature value as a `datetime.datetime`.

## to_date_time {#provider}

Μετατρέπει την τιμή της υπογραφής μεταδεδομένων σε `datetime`.

Εκτοπίζει μια εξαίρεση εάν η τιμή μεταδεδομένων δεν μπορεί να μετατραπεί.

```python
def to_date_time(self, provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

**Returns:** datetime: The metadata signature value as a `datetime`.

### Δείτε επίσης
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
