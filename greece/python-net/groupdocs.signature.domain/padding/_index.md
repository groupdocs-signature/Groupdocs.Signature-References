---
title: "Κλάση Padding"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά πληροφορίες γεμίσματος ή περιθωρίου που σχετίζονται με το στοιχείο."
type: docs
url: /el/python-net/groupdocs.signature.domain/padding/
is_root: false
weight: 400
---


## Padding class

Αναπαριστά πληροφορίες γεμίσματος ή περιθωρίου που σχετίζονται με το στοιχείο.

Ο τύπος Padding εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/) | Αρχικοποιεί μια νέα παρουσία της κλάσης Padding με μηδενικές τιμές. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#all) | Αρχικοποιεί μια νέα παρουσία της κλάσης Padding χρησιμοποιώντας το παρεχόμενο μέγεθος περιθωρίου για όλες τις άκρες. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#left-right-top-bottom) | Αρχικοποιεί μια νέα παρουσία της κλάσης Padding χρησιμοποιώντας τα παρεχόμενα μεγέθη περιθωρίων. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/padding/clone/) | Λαμβάνει ένα αντίγραφο αυτού του αντικειμένου. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [all](/signature/python-net/groupdocs.signature.domain/padding/all/) | Η τιμή περιθωρίου για όλες τις άκρες. |
| [bottom](/signature/python-net/groupdocs.signature.domain/padding/bottom/) | Η τιμή περιθωρίου για την κάτω άκρη. |
| [horizontal](/signature/python-net/groupdocs.signature.domain/padding/horizontal/) | Το συνδυασμένο περιθώριο για τις δεξιές και αριστερές άκρες. |
| [left](/signature/python-net/groupdocs.signature.domain/padding/left/) | Η τιμή περιθωρίου για την αριστερή άκρη. |
| [right](/signature/python-net/groupdocs.signature.domain/padding/right/) | Η τιμή περιθωρίου για τη δεξιά άκρη. |
| [top](/signature/python-net/groupdocs.signature.domain/padding/top/) | Η τιμή περιθωρίου για την άνω άκρη. |
| [vertical](/signature/python-net/groupdocs.signature.domain/padding/vertical/) | Το συνδυασμένο περιθώριο για τις άνω και κάτω άκρες. |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [EMPTY](/signature/python-net/groupdocs.signature.domain/padding/empty/) | Παρέχει ένα αντικείμενο Padding χωρίς περιθώριο. |

### Παράδειγμα

```python
from groupdocs.signature.domain import Padding

# Ομοιόμορφο περιθώριο 5 μονάδων σε όλες τις πλευρές
uniform = Padding(5)

# Συγκεκριμένο περιθώριο στα δεξιά και κάτω
custom = Padding(right=40, bottom=60)
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `Padding`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Δείτε επίσης
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
