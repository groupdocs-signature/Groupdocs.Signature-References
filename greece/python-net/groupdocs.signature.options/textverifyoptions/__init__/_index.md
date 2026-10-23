---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο αντικείμενο του TextVerifyOptions με προεπιλεγμένες τιμές."
type: docs
url: /el/python-net/groupdocs.signature.options/textverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί ένα νέο αντικείμενο του TextVerifyOptions με προεπιλεγμένες τιμές.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## __init__ {#text}

Αρχικοποιεί ένα νέο αντικείμενο του TextVerifyOptions με κείμενο επαλήθευσης.

```python
def __init__(self, text):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | `str` | Κείμενο για επαλήθευση. |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

## __init__ {#text-implementation}

Αρχικοποιεί ένα νέο αντικείμενο TextVerifyOptions με το κείμενο προς επαλήθευση και τον τύπο υλοποίησης της υπογραφής.

```python
def __init__(self, text, implementation):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | `str` | Κείμενο για επαλήθευση. |
| implementation | `TextSignatureImplementation` | Τύπος υλοποίησης υπογραφής. |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

### Δείτε επίσης
* class [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)
