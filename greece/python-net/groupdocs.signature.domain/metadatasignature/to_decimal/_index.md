---
title: "μέθοδος to_decimal"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Μετατρέπει την τιμή της μεταδεδομένης υπογραφής σε Decimal."
type: docs
url: /el/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/
is_root: false
weight: 1110
---


## to_decimal

Μετατρέπει την τιμή της μεταδεδομένης υπογραφής σε Decimal.

Εγείρει μια εξαίρεση εάν η τιμή μεταδεδομένων δεν μπορεί να μετατραπεί. Εάν η αρχική τιμή είναι συμβολοσειρά, οι πληροφορίες προεπιλεγμένης πολιτισμικής ρύθμισης θα χρησιμοποιηθούν από [`SignatureSettings.DefaultCulture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_decimal(self):
    ...
```

**Returns:** The metadata signature value as Decimal.

## to_decimal {#provider}

Μετατρέπει την τιμή της μεταδεδομένης υπογραφής σε Decimal.

```python
def to_decimal(self, provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

**Returns:** The metadata signature value as Decimal.

### Δείτε επίσης
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
