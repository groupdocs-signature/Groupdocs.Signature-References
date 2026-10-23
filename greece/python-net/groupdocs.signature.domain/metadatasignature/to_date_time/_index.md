---
title: "μέθοδος to_date_time"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Μετατρέπει την τιμή της μεταδεδομένης υπογραφής σε datetime."
type: docs
url: /el/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/
is_root: false
weight: 1090
---


## to_date_time

Μετατρέπει την τιμή της μεταδεδομένης υπογραφής σε datetime.

Εάν η τιμή μεταδεδομένων δεν μπορεί να μετατραπεί, εγείρεται μια εξαίρεση. Όταν η αρχική τιμή είναι συμβολοσειρά, η προεπιλεγμένη πολιτισμική ρύθμιση από [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) χρησιμοποιείται για τη μετατροπή.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime: The metadata signature value as a datetime.

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    for metadata in result.signatures:
        try:
            dt = metadata.to_date_time()
            print(f"{metadata.name} as datetime: {dt}")
        except Exception as e:
            print(f"Could not convert {metadata.name} to datetime: {e}")
```

## to_date_time {#provider}

Μετατρέπει την τιμή της μεταδεδομένης υπογραφής σε datetime.

```python
def to_date_time(self, provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

**Returns:** datetime.datetime: The metadata signature value as a datetime.

Εκτοπίζει μια εξαίρεση εάν η τιμή μεταδεδομένων δεν μπορεί να μετατραπεί.

### Δείτε επίσης
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
