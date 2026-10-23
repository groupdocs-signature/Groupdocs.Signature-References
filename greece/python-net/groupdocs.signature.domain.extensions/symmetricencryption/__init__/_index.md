---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί έναν αλγόριθμο συμμετρικής κρυπτογράφησης με τις καθορισμένες παραμέτρους."
type: docs
url: /el/python-net/groupdocs.signature.domain.extensions/symmetricencryption/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

Αρχικοποιεί έναν αλγόριθμο συμμετρικής κρυπτογράφησης με τις καθορισμένες παραμέτρους.

```python
def __init__(self, algorithm_type, key, salt):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Καθορίστε τύπο συμμετρικού αλγορίθμου |
| key | `str` | Κλειδί κρυπτογράφησης |
| salt | `str` | Φράση πρόσβασης για κρυπτογράφηση |

## __init__ {#algorithm_type-key}

Αρχικοποιεί έναν αλγόριθμο συμμετρικής κρυπτογράφησης με προεπιλεγμένη φράση πρόσβασης.

```python
def __init__(self, algorithm_type, key):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Καθορίστε τον τύπο συμμετρικού αλγορίθμου. |
| key | `str` | Κλειδί κρυπτογράφησης. |

### Δείτε επίσης
* class [`SymmetricEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/)
