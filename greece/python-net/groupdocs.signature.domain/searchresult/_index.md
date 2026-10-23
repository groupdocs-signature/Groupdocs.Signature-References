---
title: "SearchResult κλάση"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει το αποτέλεσμα της αναζήτησης υπογραφών σε ένα καθορισμένο έγγραφο."
type: docs
url: /el/python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 590
---


## SearchResult class

Αντιπροσωπεύει το αποτέλεσμα της αναζήτησης υπογραφών σε ένα καθορισμένο έγγραφο.

Ο τύπος SearchResult εκθέτει τα ακόλουθα μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [get_enumerator](/signature/python-net/groupdocs.signature.domain/searchresult/get_enumerator/) | Επιστρέφει έναν επαναλήπτη πάνω στα αποτελέσματα αναζήτησης. |
| [to_list](/signature/python-net/groupdocs.signature.domain/searchresult/to_list/) |  |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size/) | Το μέγεθος του προορισμού εγγράφου, το οποίο είναι πάντα 0 για τη μέθοδο Search. |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed/) | Η λίστα των υπογραφών [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) που απέτυχαν στη διαδικασία αναζήτησης βάσει κριτηρίων αναζήτησης. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time/) | Ο χρόνος εκτέλεσης της διαδικασίας αναζήτησης σε χιλιοστά του δευτερολέπτου. |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures/) | Η λίστα των ευρεθέντων υπογραφών [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size/) | Το μέγεθος του πηγαίου εγγράφου. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded/) | Η λίστα των ευρεθέντων υπογραφών ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures/) | Ο συνολικός αριθμός των επεξεργασμένων υπογραφών που επιστρέφονται από τη διαδικασία αναζήτησης. |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([FormFieldSearchOptions()])
    print(f"Found {len(result.signatures)} form field signature(s)")
```

### Δείτε επίσης
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
