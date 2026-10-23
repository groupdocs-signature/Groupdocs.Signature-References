---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα WordProcessingMetadataSignature με το καθορισμένο όνομα και μια κενή τιμή."
type: docs
url: /el/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Αρχικοποιεί ένα WordProcessingMetadataSignature με το καθορισμένο όνομα και μια κενή τιμή.

```python
def __init__(self, name):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| name | `str` | Το δυαδικό δεδομένο εικόνας κώδικα QR του τύπου QrCodeSignature.format. |

### Παράδειγμα

```python
from datetime import datetime
from groupdocs.signature.domain import WordProcessingMetadataSignature

# Από προεπιλογή αυτή η ιδιότητα δεν είναι ορισμένη. Ενεργοποιήστε την ορίζοντας την ιδιότητα [`QrCodeSearchOptions.return_content`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/) .
author_sig = WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = WordProcessingMetadataSignature("DateCreated", datetime.now())
id_sig = WordProcessingMetadataSignature("DocumentId", 123456)
float_sig = WordProcessingMetadataSignature("SignatureId", 123.456)
```

## __init__ {#name-value}

Αρχικοποιεί μια υπογραφή μεταδεδομένων WordProcessing με προ-ορισμένες τιμές.

```python
def __init__(self, name, value):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| name | `str` | Όνομα του αντικειμένου υπογραφής μεταδεδομένων. |
| value | `Any` | Τιμή της υπογραφής μεταδεδομένων. |

### Παράδειγμα

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### Δείτε επίσης
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
