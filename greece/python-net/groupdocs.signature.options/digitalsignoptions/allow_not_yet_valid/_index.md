---
title: "ιδιότητα allow_not_yet_valid"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Η σημαία που επιτρέπει την υπογραφή με πιστοποιητικό του οποίου η περίοδος ισχύος δεν έχει ακόμη ξεκινήσει."
type: docs
url: /el/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/
is_root: false
weight: 2020
---


## allow_not_yet_valid property

Η σημαία που επιτρέπει την υπογραφή με ένα πιστοποιητικό του οποίου η περίοδος ισχύος δεν έχει ξεκινήσει ακόμη. Η προεπιλεγμένη τιμή είναι False· η υπογραφή με τέτοιο πιστοποιητικό προκαλεί την εξαίρεση `GroupDocsSignatureException` και το έγγραφο δεν υπογράφεται.

Οι επικυρωτές αναφέρουν μια υπογραφή που δημιουργήθηκε πριν το πιστοποιητικό γίνει έγκυρο ως μη έγκυρη. Ένα τέτοιο πιστοποιητικό συνήθως εκδίδεται για μεταγενέστερη ημερομηνία ή το ρολόι του υπολογιστή είναι λανθασμένο. Όταν αυτή η σημαία είναι True, το έγγραφο υπογράφεται και γράφεται μια προειδοποίηση στον καταγραφέα που έχει οριστεί στο [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Το πιστοποιητικό συγκρίνεται με την τρέχουσα ώρα σε UTC. Η σημαία εφαρμόζεται στα ίδια πιστοποιητικά όπως το [`DigitalSignOptions.AllowExpired`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/), το οποίο ελέγχει πιστοποιητικά των οποίων η περίοδος ισχύος έχει λήξει.

### Definition:
```python
@property
def allow_not_yet_valid(self):
    ...
@allow_not_yet_valid.setter
def allow_not_yet_valid(self, value):
    ...
```

### Δείτε επίσης
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
