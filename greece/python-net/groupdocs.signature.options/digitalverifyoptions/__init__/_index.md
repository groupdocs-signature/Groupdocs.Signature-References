---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα αντικείμενο DigitalVerifyOptions με προεπιλεγμένες τιμές."
type: docs
url: /el/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί ένα αντικείμενο DigitalVerifyOptions με προεπιλεγμένες τιμές.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

with Signature("signed.pdf") as signature:
    options = DigitalVerifyOptions("certificate.pfx")
    options.password = "1234567890"
    result = signature.verify(options)
    print(f"Verification result: {result.is_valid}")
```

## __init__ {#certificate_file_path}

Αρχικοποιεί ένα αντικείμενο DigitalVerifyOptions με τη δοσμένη διαδρομή αρχείου ψηφιακού πιστοποιητικού.

```python
def __init__(self, certificate_file_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| certificate_file_path | `str` | Διαδρομή αρχείου προς ψηφιακό πιστοποιητικό. |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

options = DigitalVerifyOptions("certificate.pfx")
options.password = "1234567890"
```

## __init__ {#certificate_stream}

Αρχικοποιεί ένα αντικείμενο DigitalVerifyOptions με το δοσμένο ρεύμα πιστοποιητικού.

```python
def __init__(self, certificate_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Ροή του πιστοποιητικού. |

### Δείτε επίσης
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
