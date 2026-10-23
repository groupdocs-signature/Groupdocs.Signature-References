---
title: "Κλάση VerificationResult"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει μια παρουσία που διατηρεί τα αποτελέσματα της διαδικασίας επαλήθευσης."
type: docs
url: /el/python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 820
---


## VerificationResult class

Αντιπροσωπεύει μια παρουσία που διατηρεί τα αποτελέσματα της διαδικασίας επαλήθευσης.

Ο τύπος VerificationResult εκθέτει τα ακόλουθα μέλη:

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size/) | Το μέγεθος του εγγράφου προορισμού. Για επαλήθευση αυτή η μεταβλητή είναι πάντα μηδέν. |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed/) | Η λίστα των υπογραφών που απέτυχαν στη διαδικασία επαλήθευσης. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid/) | Το αποτέλεσμα επαλήθευσης· True εάν η διαδικασία επαλήθευσης ήταν επιτυχής, διαφορετικά False. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time/) | Ο χρόνος εκτέλεσης της διαδικασίας σε χιλιοστά του δευτερολέπτου. |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size/) | Το μέγεθος του πηγαίου εγγράφου σε bytes. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded/) | Η λίστα των επιτυχώς επαληθευμένων υπογραφών [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures/) | Ο συνολικός αριθμός των επεξεργασμένων υπογραφών. |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions
from groupdocs.signature.domain import TextMatchType

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions()
    options.text = "John Smith"
    options.match_type = TextMatchType.CONTAINS

    result = signature.verify(options)

    if result.is_valid:
        print(f"Verified: {len(result.succeeded)} matching signature(s).")
    else:
        print("Verification failed.")
```

### Δείτε επίσης
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
