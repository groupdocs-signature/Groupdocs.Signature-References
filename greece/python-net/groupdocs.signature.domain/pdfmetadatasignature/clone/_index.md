---
title: "μέθοδος clone"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Κλωνοποιεί το αντικείμενο Metadata Signature."
type: docs
url: /el/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Κλωνοποιεί το αντικείμενο Metadata Signature.

```python
def clone(self):
    ...
```

**Returns:** PdfMetadataSignature: Cloned Metadata Signature instance.

### Παράδειγμα

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Δημιουργήστε μια τυπική υπογραφή μεταδεδομένων με μια νέα τιμή
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

## clone {#value}

Κλωνοποιεί ένα αντικείμενο υπογραφής μεταδεδομένων PDF με τη δοθείσα τιμή.

```python
def clone(self, value):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | `Any` | Τιμή για το νέο κλωνοποιημένο αντικείμενο. |

**Returns:** A cloned metadata signature instance.

### Παράδειγμα

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Κλωνοποιήστε μια υπάρχουσα υπογραφή μεταδεδομένων με μια νέα τιμή
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Δείτε επίσης
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
