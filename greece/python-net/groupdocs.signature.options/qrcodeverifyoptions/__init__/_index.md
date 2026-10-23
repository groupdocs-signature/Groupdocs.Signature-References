---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί τις επιλογές επαλήθευσης για υπογραφές QR-Code."
type: docs
url: /el/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί τις επιλογές επαλήθευσης για υπογραφές QR-Code.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions

with Signature("signed.pdf") as signature:
    options = QrCodeVerifyOptions()
    options.text = "John"
    result = signature.verify(options)
    print(f"Verified: {result.is_valid}")
```

## __init__ {#text}

Αρχικοποιεί τις επιλογές επαλήθευσης για υπογραφές QR-Code με το καθορισμένο κείμενο QR-code.

```python
def __init__(self, text):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | `str` | Κείμενο QR-code για επαλήθευση |

### Παράδειγμα

```python
from groupdocs.signature.options import QrCodeVerifyOptions

# Δημιουργήστε επιλογές και ορίστε το κείμενο QR-code για επαλήθευση
options = QrCodeVerifyOptions()
options.text = "Approved by John Smith"
```

## __init__ {#text-encode_type}

Αρχικοποιεί τις επιλογές επαλήθευσης για υπογραφές QR-Code με κείμενο και τύπο κωδικοποίησης QR-Code για επαλήθευση.

```python
def __init__(self, text, encode_type):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | `str` | Κείμενο για επαλήθευση. |
| encode_type | `QrCodeType` | Τύπος κωδικοποίησης |

### Παράδειγμα

```python
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeVerifyOptions(text="John Smith", encode_type=QrCodeTypes.QR)
```

### Δείτε επίσης
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/)
