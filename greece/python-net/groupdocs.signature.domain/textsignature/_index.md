---
title: "Κλάση TextSignature"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Η κλάση TextSignature περιέχει τις ιδιότητες υπογραφής κειμένου."
type: docs
url: /el/python-net/groupdocs.signature.domain/textsignature/
is_root: false
weight: 770
---


## TextSignature class

Η κλάση TextSignature περιέχει τις ιδιότητες υπογραφής κειμένου.

Ο τύπος TextSignature εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textsignature/__init__/#signature_id) | Αρχικοποιεί ένα αντικείμενο TextSignature με το μοναδικό αναγνωριστικό υπογραφής που ελήφθη από λειτουργία υπογραφής ή αναζήτησης. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textsignature/clone/) | Κλωνοποιεί το στιγμιότυπο Text Signature. |
| [equals](/signature/python-net/groupdocs.signature.domain/textsignature/equals/#obj) | Συγκρίνει τη συγκεκριμένη υπογραφή με αυτήν την περίπτωση για ισότητα. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textsignature/get_hash_code/) | Επιστρέφει τον κωδικό κατακερματισμού για την υπογραφή. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [native](/signature/python-net/groupdocs.signature.domain/textsignature/native/) | Το εγγενές χαρακτηριστικό που υποδεικνύει εάν η υπογραφή είναι ειδική για το έγγραφο. |
| [signature_implementation](/signature/python-net/groupdocs.signature.domain/textsignature/signature_implementation/) | Η υλοποίηση υπογραφής κειμένου. |
| [text](/signature/python-net/groupdocs.signature.domain/textsignature/text/) | Το κείμενο της υπογραφής. |
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
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for text_sig in result.signatures:
        print(f"Text: {text_sig.text}, Position: ({text_sig.left}, {text_sig.top}), Size: {text_sig.width}x{text_sig.height}")
```

### Δείτε επίσης
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
