---
title: "μέθοδος from_extension"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αντιστοιχίζει την επέκταση αρχείου με τον τύπο αρχείου."
type: docs
url: /el/python-net/groupdocs.signature.domain/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Αντιστοιχίζει την επέκταση αρχείου με τον τύπο αρχείου.

```python
def from_extension(cls, extension):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| extension | `str` | Επέκταση αρχείου (συμπεριλαμβανομένου του σημείου "."). |

**Returns:** FileType: When file type is supported returns it, otherwise returns default `FileType.unknown` file type.

| Εγείρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εγείρεται όταν το `extension` είναι null ή κενή συμβολοσειρά. |

### Παράδειγμα

```python
import os
from groupdocs.signature.domain import FileType

extension = os.path.splitext("contract.pdf")[1]
if FileType.from_extension(extension) == FileType.UNKNOWN:
    print(f"{extension} files are not supported")
else:
    print(f"{extension} files are supported")
```

### Δείτε επίσης
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
