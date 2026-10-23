---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί την προεπιλεγμένη επιλογή επαλήθευσης για την υπογραφή barcode."
type: docs
url: /el/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί την προεπιλεγμένη επιλογή επαλήθευσης για την υπογραφή barcode.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.signature.options import BarcodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

options = BarcodeVerifyOptions()
options.text = "12345"
options.match_type = TextMatchType.CONTAINS
```

## __init__ {#text}

Αρχικοποιεί μια προεπιλεγμένη επιλογή επαλήθευσης με κείμενο επαλήθευσης.

```python
def __init__(self, text):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | `str` | Κείμενο barcode για επαλήθευση. |

## __init__ {#encode_type}

Αρχικοποιεί μια προεπιλεγμένη επιλογή επαλήθευσης με επαλήθευση τύπου barcode.

```python
def __init__(self, encode_type):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| encode_type | `BarcodeType` | Επαλήθευση τύπου barcode. |

## __init__ {#text-encode_type}

Αρχικοποιεί μια προεπιλεγμένη επιλογή επαλήθευσης με επαλήθευση τύπου barcode και κείμενο.

```python
def __init__(self, text, encode_type):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | `str` | Κείμενο barcode για επαλήθευση. |
| encode_type | `BarcodeType` | Επαλήθευση τύπου barcode. |

### Δείτε επίσης
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/)
