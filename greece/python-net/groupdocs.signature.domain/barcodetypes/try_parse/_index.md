---
title: "try_parse μέθοδος"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Επιστρέφει τον τύπο Barcode που ταιριάζει με το δεδομένο όνομα τύπου ανάλυσης."
type: docs
url: /el/python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

Επιστρέφει τον τύπο Barcode που ταιριάζει με το δεδομένο όνομα τύπου ανάλυσης.

Αν το όνομα είναι άγνωστο, η μέθοδος επιστρέφει None αντί να ρίξει εξαίρεση.

```python
def try_parse(cls, parsing_type):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| parsing_type | `str` | Συμβολοσειρά προέλευσης του ονόματος τύπου barcode. |

**Returns:** BarcodeType: The matching BarcodeType instance, or None if not found.

### Δείτε επίσης
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
