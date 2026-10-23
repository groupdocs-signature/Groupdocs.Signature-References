---
title: "κλάση ImageSignature"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Η κλάση περιέχει ιδιότητες υπογραφής εικόνας."
type: docs
url: /el/python-net/groupdocs.signature.domain/imagesignature/
is_root: false
weight: 340
---


## ImageSignature class

Η κλάση περιέχει ιδιότητες υπογραφής εικόνας.

Ο τύπος ImageSignature εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagesignature/__init__/#signature_id) | Αρχικοποιεί ένα αντικείμενο ImageSignature με ένα μοναδικό αναγνωριστικό υπογραφής που λαμβάνεται από τη μέθοδο Sign ή Search της κλάσης [`GroupDocs.Signature`](/signature/python-net/groupdocs.signature/signature/). |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagesignature/clone/) | Clone αντικείμενο ImageSignature. |
| [equals](/signature/python-net/groupdocs.signature.domain/imagesignature/equals/#obj) | Καθορίζει εάν η υπογραφή που καθορίστηκε είναι ίση με αυτήν την παρουσία. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagesignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagesignature/get_hash_code/) | Επιστρέφει τον κωδικό κατακερματισμού για την υπογραφή. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/imagesignature/content/) | Τα δυαδικά δεδομένα εικόνας της υπογραφής, στη μορφή που καθορίζεται από το [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). |
| [format](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) | Η μορφή της εικόνας υπογραφής. |
| [size](/signature/python-net/groupdocs.signature.domain/imagesignature/size/) | Το μέγεθος σε byte της εικόνας υπογραφής. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Η ημερομηνία δημιουργίας της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Η σημαία που υποδεικνύει εάν αυτή η υπογραφή διαγράφηκε από το έγγραφο. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Το ύψος της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Η σημαία που υποδεικνύει εάν αυτό το στοιχείο αντιπροσωπεύει υπογραφή (`True`) ή περιεχόμενο εγγράφου (`False`). (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Η αριστερή θέση της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Η ημερομηνία τροποποίησης της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Ο αριθμός σελίδας όπου βρέθηκε η υπογραφή. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Το μοναδικό αναγνωριστικό της υπογραφής, που χρησιμοποιείται για την τροποποίηση της υπογραφής στο έγγραφο μέσω λειτουργιών ενημέρωσης ή διαγραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Ο τύπος της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Η άνω θέση της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Το πλάτος της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([ImageSearchOptions()])
    for image in result.signatures:
        print(
            f"Page {image.page_number}: {image.size} bytes at ({image.left}, {image.top}), "
            f"size {image.width}x{image.height}"
        )
```

### Δείτε επίσης
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
