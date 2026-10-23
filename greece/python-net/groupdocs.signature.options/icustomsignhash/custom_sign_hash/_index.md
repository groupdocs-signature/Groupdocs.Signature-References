---
title: "μέθοδος custom_sign_hash"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Υπογράφει το δεδομένο hash χρησιμοποιώντας μια προσαρμοσμένη υλοποίηση υπογραφής."
type: docs
url: /el/python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 1010
---


## custom_sign_hash {#signable_hash-hash_algorithm-signature_context}

Υπογράφει το δεδομένο hash χρησιμοποιώντας μια προσαρμοσμένη υλοποίηση υπογραφής.

```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| signable_hash | `list[int]` | Η τιμή κατακερματισμού που θα υπογραφεί. |
| hash_algorithm | `HashAlgorithm` | Ο αλγόριθμος κατακερματισμού που χρησιμοποιείται για τη δημιουργία του κατακερματισμού. |
| signature_context | `SignatureContext` | Το πλαίσιο που παρέχει πρόσθετες επιλογές σχετικές με την υπογραφή. |

**Returns:** bytes: The signed hash as bytes.

### Δείτε επίσης
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash/)
