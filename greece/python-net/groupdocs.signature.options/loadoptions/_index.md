---
title: "Κλάση LoadOptions"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Η κλάση LoadOptions επιτρέπει τον καθορισμό πρόσθετων επιλογών (όπως κωδικός πρόσβασης) κατά το άνοιγμα ενός εγγράφου για υπογραφή."
type: docs
url: /el/python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 300
---


## LoadOptions class

Η κλάση LoadOptions επιτρέπει τον καθορισμό πρόσθετων επιλογών (όπως κωδικός πρόσβασης) κατά το άνοιγμα ενός εγγράφου για υπογραφή.

Ορίστε το χαρακτηριστικό `password` στον κωδικό πρόσβασης του εγγράφου εάν το αρχείο είναι κρυπτογραφημένο.

Ο τύπος LoadOptions εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/) | Αρχικοποιεί μια νέα παρουσία της κλάσης LoadOptions. |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#file_type) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) με συγκεκριμένο τύπο αρχείου. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type/) | Ο τύπος αρχείου που σχετίζεται με τις επιλογές φόρτωσης, προεπιλεγμένος σε [`FileType.unknown`](/signature/python-net/groupdocs.signature.domain/filetype/unknown/). |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) | Η σημαία που καθορίζει αν το έγγραφο φορτώνει εξωτερικούς πόρους. Αυτή η ιδιότητα είναι παρωχημένη· χρησιμοποιήστε το [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) αντί αυτού, το οποίο έχει το αντίστροφο νόημα. |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password/) | Ο κωδικός πρόσβασης που χρησιμοποιείται για το άνοιγμα ενός προστατευμένου εγγράφου και για την αποθήκευση ενός υπογεγραμμένου εγγράφου ως προστατευμένο. |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions/) | Τα δικαιώματα εγγράφου PDF όπως εκτύπωση, τροποποίηση και εξαγωγή δεδομένων. Ισχύει μόνο για έγγραφα PDF. |
| [skip_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) | Η σημαία που εμποδίζει το έγγραφο να φορτώνει εξωτερικούς πόρους. Η προεπιλεγμένη τιμή είναι True· οι εξωτερικοί πόροι δεν φορτώνονται εκτός από εκείνους που ταιριάζουν με [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/). |
| [whitelisted_resources](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) | Η λίστα των τμημάτων διευθύνσεων των εξωτερικών πόρων που φορτώνονται ακόμη και όταν το [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) είναι true. Η προεπιλεγμένη τιμή είναι μια κενή λίστα. |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions

load_options = LoadOptions()
load_options.password = "1234567890"
with Signature("protected.pdf", load_options) as signature:
    info = signature.get_document_info()
    print(f"{info.file_type.file_format}, {info.page_count} page(s), {info.size} bytes")
```

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
