---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία της κλάσης QRCodeSignOptions με προεπιλεγμένες τιμές."
type: docs
url: /el/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί μια νέα παρουσία της κλάσης QRCodeSignOptions με προεπιλεγμένες τιμές.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Αρχικοποιεί μια παρουσία QR code signature options με το καθορισμένο κείμενο.

```python
def __init__(self, text):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | `str` | Κείμενο υπογραφής. |

### Παράδειγμα

```python
from groupdocs.signature.options import QrCodeSignOptions

# Δημιουργήστε επιλογές υπογραφής QR code με το επιθυμητό κείμενο
options = QrCodeSignOptions("Approved by John Smith")
```

## __init__ {#text-encode_type}

Αρχικοποιεί μια νέα παρουσία της κλάσης QrCodeSignOptions με κείμενο.

```python
def __init__(self, text, encode_type):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | `str` | Κείμενο QRCode. |
| encode_type | `QrCodeType` | Τύπος κωδικοποίησης QRCode. |

### Παράδειγμα

```python
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeSignOptions(
    "https://www.example.com/verify-document",
    QrCodeTypes.QR
)
```

### Δείτε επίσης
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
