---
title: "ιδιότητα load_external_resources"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Η σημαία που καθορίζει εάν το έγγραφο φορτώνει εξωτερικούς πόρους."
type: docs
url: /el/python-net/groupdocs.signature.options/loadoptions/load_external_resources/
is_root: false
weight: 2020
---


## load_external_resources property

Η σημαία που καθορίζει αν το έγγραφο φορτώνει εξωτερικούς πόρους. Αυτή η ιδιότητα είναι παρωχημένη· χρησιμοποιήστε το [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) αντί αυτού, το οποίο έχει το αντίστροφο νόημα.

LoadExternalResources = True ισοδυναμεί με `SkipExternalResources` = False, και LoadExternalResources = False ισοδυναμεί με `SkipExternalResources` = True. Η προεπιλεγμένη τιμή είναι False, που σημαίνει ότι οι εξωτερικοί πόροι δεν φορτώνονται εκτός εάν επιτραπεί ρητά.

### Definition:
```python
@property
def load_external_resources(self):
    ...
@load_external_resources.setter
def load_external_resources(self, value):
    ...
```

### Δείτε επίσης
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
