---
title: "μέθοδος to_decimal"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Μετατρέπει σε Decimal."
type: docs
url: /el/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/
is_root: false
weight: 1090
---


## to_decimal

Μετατρέπει σε Decimal.

Εγείρει μια εξαίρεση εάν η τιμή μεταδεδομένων δεν μπορεί να μετατραπεί. Εάν η αρχική τιμή είναι συμβολοσειρά, η προεπιλεγμένη πολιτισμική ρύθμιση από [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) χρησιμοποιείται.

```python
def to_decimal(self):
    ...
```

**Returns:** decimal.Decimal: The Image Metadata Signature value as Decimal.

## to_decimal {#provider}

Μετατρέπει την τιμή της υπογραφής μεταδεδομένων σε δεκαδικό.

Εγείρει μια εξαίρεση εάν η τιμή των μεταδεδομένων δεν μπορεί να μετατραπεί.

```python
def to_decimal(self, provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

**Returns:** float: The metadata signature value as a decimal.

### Δείτε επίσης
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
