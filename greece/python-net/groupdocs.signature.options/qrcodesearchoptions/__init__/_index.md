---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία της κλάσης QRCodeSearchOptions με προεπιλεγμένες τιμές."
type: docs
url: /el/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί μια νέα παρουσία της κλάσης QRCodeSearchOptions με προεπιλεγμένες τιμές.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

## __init__ {#encode_type}

Αρχικοποιεί μια νέα παρουσία της κλάσης QRCodeSearchOptions με τιμή τύπου κωδικοποίησης.

```python
def __init__(self, encode_type):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| encode_type | `QrCodeType` | Καθορίζει τον τύπο κωδικοποίησης QR-Code. |

## __init__ {#encode_type-text}

Αρχικοποιεί μια νέα παρουσία της κλάσης QRCodeSearchOptions με τύπο κωδικοποίησης και τιμές κειμένου.

```python
def __init__(self, encode_type, text):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| encode_type | `QrCodeType` | Καθορίζει τον τύπο κωδικοποίησης QR-Code. |
| text | `str` | Ορίστε το κείμενο της υπογραφής QR-Code. |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

### Δείτε επίσης
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
