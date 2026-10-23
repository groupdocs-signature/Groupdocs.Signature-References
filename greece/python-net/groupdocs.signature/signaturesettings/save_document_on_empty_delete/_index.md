---
title: "save_document_on_empty_delete ιδιότητα"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Η σημαία που καθορίζει εάν το αρχικό έγγραφο αποθηκεύεται ξανά όταν η μέθοδος Delete δεν έχει υπογραφές που επηρεάζονται για αφαίρεση."
type: docs
url: /el/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 2050
---


## save_document_on_empty_delete property

Η σημαία που καθορίζει εάν το αρχικό έγγραφο αποθηκεύεται ξανά όταν η μέθοδος Delete δεν έχει υπογραφές που επηρεάζονται για αφαίρεση.

Όταν είναι True (προεπιλογή), το έγγραφο αποθηκεύεται με ένα ιστορικό αρχείο (ημερομηνία και τύπο λειτουργίας) ακόμη και αν δεν αφαιρεθούν υπογραφές· όταν είναι False, το αρχικό έγγραφο παραμένει αμετάβλητο.

### Definition:
```python
@property
def save_document_on_empty_delete(self):
    ...
@save_document_on_empty_delete.setter
def save_document_on_empty_delete(self, value):
    ...
```

### Δείτε επίσης
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
