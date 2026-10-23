---
title: "save_document_on_empty_update ιδιότητα"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Η σημαία που καθορίζει αν το αρχικό έγγραφο θα αποθηκευτεί ξανά όταν η μέθοδος Update δεν έχει υπογραφές προς ενημέρωση."
type: docs
url: /el/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 2060
---


## save_document_on_empty_update property

Η σημαία που καθορίζει εάν το αρχικό έγγραφο αποθηκεύεται ξανά όταν η μέθοδος `Update` δεν έχει υπογραφές για ενημέρωση.

Εάν οριστεί σε `True` (προεπιλογή), το έγγραφο αποθηκεύεται με ένα αντίστοιχο αρχείο ιστορικής διαδικασίας (ημερομηνία και τύπο λειτουργίας) ακόμη και όταν δεν ενημερώνονται υπογραφές. Όταν οριστεί σε `False`, το αρχικό έγγραφο δεν τροποποιείται καθόλου.

### Definition:
```python
@property
def save_document_on_empty_update(self):
    ...
@save_document_on_empty_update.setter
def save_document_on_empty_update(self, value):
    ...
```

### Δείτε επίσης
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
