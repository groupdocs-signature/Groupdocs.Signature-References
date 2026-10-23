---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο αντικείμενο της κλάσης BarcodeSignOptions με προεπιλεγμένες τιμές."
type: docs
url: /el/python-net/groupdocs.signature.options/barcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης BarcodeSignOptions με προεπιλεγμένες τιμές.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης BarcodeSignOptions με κείμενο.

```python
def __init__(self, text):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | `str` | Κείμενο barcode. |

### Παράδειγμα

```python
from groupdocs.signature.options import BarcodeSignOptions

# Δημιουργήστε επιλογές υπογραφής barcode με το επιθυμητό κείμενο.
options = BarcodeSignOptions("JohnSmith")
```

## __init__ {#text-encode_type}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης BarcodeSignOptions με κείμενο.

```python
def __init__(self, text, encode_type):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | `str` | Κείμενο barcode. |
| encode_type | `BarcodeType` | Τύπος κωδικοποίησης barcode. |

### Παράδειγμα

```python
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

# Δημιουργήστε επιλογές υπογραφής barcode με κείμενο και τύπο.
options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
```

### Δείτε επίσης
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
