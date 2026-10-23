---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία της κλάσης DigitalVBA με αρχείο πιστοποιητικού."
type: docs
url: /el/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/
is_root: false
weight: 10
---


## __init__ {#certificate_file_path-password}

Αρχικοποιεί μια νέα παρουσία της κλάσης DigitalVBA με αρχείο πιστοποιητικού.

```python
def __init__(self, certificate_file_path, password):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| certificate_file_path | `str` | Διαδρομή αρχείου ψηφιακού πιστοποιητικού. |
| password | `str` | Κωδικός πρόσβασης ψηφιακού πιστοποιητικού. |

### Παράδειγμα

```python
from groupdocs.signature.domain.extensions import DigitalVBA

# Δημιουργήστε μια επέκταση DigitalVBA χρησιμοποιώντας αρχείο πιστοποιητικού και κωδικό πρόσβασης.
digital_vba = DigitalVBA("certificate.pfx", "1234567890")
```

## __init__ {#certificate_stream-password}

Αρχικοποιεί μια νέα παρουσία της κλάσης DigitalVBA με ροή πιστοποιητικού.

```python
def __init__(self, certificate_stream, password):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase που περιέχει το ψηφιακό πιστοποιητικό. |
| password | `str` | str κωδικός πρόσβασης για το ψηφιακό πιστοποιητικό. |

### Δείτε επίσης
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)
