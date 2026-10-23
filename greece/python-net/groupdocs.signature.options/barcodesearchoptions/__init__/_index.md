---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία της κλάσης BarcodeSearchOptions με προεπιλεγμένες τιμές."
type: docs
url: /el/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί μια νέα παρουσία της κλάσης BarcodeSearchOptions με προεπιλεγμένες τιμές.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.signature.options import BarcodeSearchOptions

# Δημιουργήστε ένα αντικείμενο επιλογών αναζήτησης με προεπιλεγμένες ρυθμίσεις
options = BarcodeSearchOptions()
```

## __init__ {#encode_type}

Αρχικοποιεί μια νέα παρουσία της κλάσης BarcodeSearchOptions με τιμή τύπου κωδικοποίησης.

```python
def __init__(self, encode_type):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| encode_type | `BarcodeType` | Καθορίζει τον τύπο κωδικοποίησης Barcode. |

## __init__ {#encode_type-text}

Αρχικοποιεί μια νέα παρουσία της κλάσης BarcodeSearchOptions με τιμές τύπου κωδικοποίησης και κειμένου.

```python
def __init__(self, encode_type, text):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| encode_type | `BarcodeType` | Καθορίζει τον τύπο κωδικοποίησης Barcode. |
| text | `str` | Ορίστε το κείμενο της υπογραφής Barcode. |

### Δείτε επίσης
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
