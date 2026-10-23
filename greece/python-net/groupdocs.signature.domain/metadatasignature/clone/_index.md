---
title: "μέθοδος clone"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Δημιουργεί κλώνο ενός αντικειμένου Metadata Signature."
type: docs
url: /el/python-net/groupdocs.signature.domain/metadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Δημιουργεί κλώνο ενός αντικειμένου Metadata Signature.

```python
def clone(self):
    ...
```

**Returns:** Returns cloned Metadata Signature instance.

### Παράδειγμα

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Δημιουργήστε μια νέα υπογραφή metadata βασισμένη στην προκαθορισμένη υπογραφή AUTHOR
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

## clone {#value}

Κλωνοποιήστε το αντικείμενο Metadata Signature με την δεδομένη τιμή.

```python
def clone(self, value):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | `Any` | Τιμή για νέο κλωνοποιημένο αντικείμενο. |

**Returns:** MetadataSignature: Cloned Metadata Signature instance with given value.

### Παράδειγμα

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Κλωνοποιήστε μια υπάρχουσα υπογραφή μεταδεδομένων με μια νέα τιμή
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Δείτε επίσης
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
