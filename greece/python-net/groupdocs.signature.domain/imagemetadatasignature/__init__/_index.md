---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια Υπογραφή Μεταδεδομένων Εικόνας με τον καθορισμένο ταυτοποιητή και τιμή."
type: docs
url: /el/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#id-value}

Αρχικοποιεί μια Υπογραφή Μεταδεδομένων Εικόνας με τον καθορισμένο ταυτοποιητή και τιμή.

```python
def __init__(self, id, value):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| id | `System.UInt16` | Μοναδικό αναγνωριστικό για την Υπογραφή Μεταδεδομένων Εικόνας. Δείτε τις αναφορές για τις προδιαγραφές ετικετών EXIF για πιθανές τιμές id. |
| value | `Any` | Η τιμή των μεταδεδομένων. |

### Παράδειγμα

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import ImageMetadataSignature

with Signature("sample.png") as signature:
    options = MetadataSignOptions()
    metadata_id = 41996
    options.add(ImageMetadataSignature(metadata_id, "Mr. Sherlock Holmes"))  # text
    options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
    options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # integer
    options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # float
    result = signature.sign("signed.png", options)
```

### Δείτε επίσης
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
