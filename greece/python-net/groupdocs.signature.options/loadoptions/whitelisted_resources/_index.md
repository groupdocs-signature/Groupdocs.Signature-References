---
title: "ιδιότητα whitelisted_resources"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Η λίστα των τμημάτων διευθύνσεων εξωτερικών πόρων που φορτώνονται ακόμη και όταν το LoadOptions.SkipExternalResources είναι true."
type: docs
url: /el/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/
is_root: false
weight: 2060
---


## whitelisted_resources property

Η λίστα των τμημάτων διευθύνσεων των εξωτερικών πόρων που φορτώνονται ακόμη και όταν το [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) είναι true. Η προεπιλεγμένη τιμή είναι μια κενή λίστα.

Ένας πόρος φορτώνεται όταν η πλήρης διεύθυνσή του περιέχει ένα από τα τμήματα. Η σύγκριση αγνοεί τη διάκριση πεζών-κεφαλαίων, και τα κενά τμήματα αγνοούνται. Προτιμήστε μακρά τμήματα όπως `"https://cdn.example.com/images/"`: ένα σύντομο τμήμα ταιριάζει επίσης με άλλες διευθύνσεις που τυχαία το περιέχουν.

Ορίζοντας αυτή την ιδιότητα σε `None` καθαρίζει τη λίστα. Η λίστα δεν έχει καμία επίδραση όταν το [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) είναι false, επειδή τότε κάθε εξωτερικός πόρος φορτώνεται.

### Definition:
```python
@property
def whitelisted_resources(self):
    ...
@whitelisted_resources.setter
def whitelisted_resources(self, value):
    ...
```

### Δείτε επίσης
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
