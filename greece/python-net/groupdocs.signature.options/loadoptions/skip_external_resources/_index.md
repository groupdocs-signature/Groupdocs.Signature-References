---
title: "ιδιότητα skip_external_resources"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Η σημαία που εμποδίζει το έγγραφο από το φόρτωμα εξωτερικών πόρων."
type: docs
url: /el/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/
is_root: false
weight: 2050
---


## skip_external_resources property

Η σημαία που εμποδίζει το έγγραφο να φορτώνει εξωτερικούς πόρους. Η προεπιλεγμένη τιμή είναι True· οι εξωτερικοί πόροι δεν φορτώνονται εκτός από εκείνους που ταιριάζουν με [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

Ένα έγγραφο μπορεί να αναφέρεται σε πόρους που αποθηκεύονται εκτός αυτού, όπως συνδεδεμένες εικόνες, εικόνες που εισάγονται μέσω πεδίου INCLUDEPICTURE, συνδεδεμένες εικόνες σε παρουσιάσεις και λογιστικά φύλλα, καθώς και εικόνες και φύλλα στυλ που αναφέρονται από μια εικόνα SVG. Η φόρτωση ενός τέτοιου πόρου κάνει τη βιβλιοθήκη να ζητήσει τη διεύθυνσή του. Σε διακομιστή που επεξεργάζεται μη αξιόπιστα έγγραφα, ένα έγγραφο θα μπορούσε να το χρησιμοποιήσει για να κάνει τον διακομιστή να στείλει αιτήματα σε εσωτερικές διευθύνσεις (server‑side request forgery), και μια διαδρομή UNC ή `file://` θα μπορούσε να προκαλέσει τα Windows να στείλουν τα διαπιστευτήρια NTLM του λογαριασμού σε άλλο κεντρικό υπολογιστή. Σε εγκατάσταση εκτός σύνδεσης ή αερο-απομονωμένη, τα αιτήματα αποτυγχάνουν ή περιμένουν λήξη χρόνου.

Οι πόροι που παραλείπονται δεν σχεδιάζονται στις προεπισκοπήσεις σελίδων ή σε έγγραφα αποθηκευμένα ως εικόνες, και η αναζήτηση εικόνας, barcode και QR‑code δεν τους βλέπει. Ορίστε αυτή την ιδιότητα σε False μόνο για αξιόπιστα έγγραφα, και προτιμήστε την άδεια συγκεκριμένων διευθύνσεων με [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

Η ρύθμιση εφαρμόζεται σε έγγραφα επεξεργασίας κειμένου, παρουσιάσεις, λογιστικά φύλλα και εικόνες SVG, συμπεριλαμβανομένων των εγγράφων μέσα σε αρχεία. Για εικόνες SVG, οι αναφορές που δεν επιτρέπονται αφαιρούνται από την εικόνα πριν διαβαστεί, και μια εικόνα SVG που δεν είναι καλά σχηματισμένο XML απορρίπτεται. Η ρύθμιση δεν ελέγχει ελέγχους ανάκλησης πιστοποιητικών, διακομιστές χρονοσήμανσης ή αδειοδότηση.

Αυτή η ιδιότητα αντικαθιστά το [`LoadOptions.LoadExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/), το οποίο έχει το αντίστροφο νόημα.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### Δείτε επίσης
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
