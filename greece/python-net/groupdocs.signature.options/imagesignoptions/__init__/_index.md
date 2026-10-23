---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ImageSignOptions με προεπιλεγμένες τιμές."
type: docs
url: /el/python-net/groupdocs.signature.options/imagesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ImageSignOptions με προεπιλεγμένες τιμές.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.signature.options import ImageSignOptions

# Δημιουργήστε επιλογές υπογραφής εικόνας χρησιμοποιώντας μια διαδρομή αρχείου εικόνας
options = ImageSignOptions("signature.jpg")
```

## __init__ {#image_file_path}

Αρχικοποιεί το ImageSignOptions με αρχείο εικόνας.

```python
def __init__(self, image_file_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_file_path | `str` | Διαδρομή αρχείου εικόνας. |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    options = ImageSignOptions("signature.jpg")
    # Διαμορφώστε πρόσθετες επιλογές εδώ, π.χ. θέση, μέγεθος, κ.λπ.
    result = signature.sign("signed_image.pdf", options)
    print(f"Signed with {len(result.succeeded)} image signature(s)")
```

## __init__ {#image_stream}

Αρχικοποιεί ένα νέο αντικείμενο ImageSignOptions με ροή εικόνας.

```python
def __init__(self, image_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | Ροή εικόνας. |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    with open("signature.jpg", "rb") as image_stream:
        options = ImageSignOptions(image_stream)
        options.left = 100
        options.top = 400
        result = signature.sign("signed_image_stream.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Δείτε επίσης
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)
