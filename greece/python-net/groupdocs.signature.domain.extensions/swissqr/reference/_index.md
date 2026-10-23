---
title: "ιδιότητα αναφοράς"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Η αναφορά πληρωμής του πιστωτή."
type: docs
url: /el/python-net/groupdocs.signature.domain.extensions/swissqr/reference/
is_root: false
weight: 2070
---


## reference property

Η αναφορά πληρωμής του πιστωτή.

Είναι υποχρεωτικό για τα IBAN SwissQR (IBAN στην περιοχή CHxx30000xxxxxx έως CHxx31999xxxxx). Εάν καθοριστεί, η αναφορά πρέπει να είναι είτε μια έγκυρη αναφορά SwissQR (σύμφωνη με τη φόρμα αναφοράς ISR) είτε μια έγκυρη αναφορά πιστωτή σύμφωνα με το ISO 11649 ("RFxxxx"). Και οι δύο μπορεί να περιέχουν κενά για μορφοποίηση.

### Definition:
```python
@property
def reference(self):
    ...
@reference.setter
def reference(self, value):
    ...
```

### Δείτε επίσης
* class [`SwissQR`](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/)
