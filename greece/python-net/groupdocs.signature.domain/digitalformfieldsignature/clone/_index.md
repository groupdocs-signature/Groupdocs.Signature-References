---
title: "μέθοδος clone"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Κλωνοποιεί το στιγμιότυπο FormField Signature."
type: docs
url: /el/python-net/groupdocs.signature.domain/digitalformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

Κλωνοποιεί το στιγμιότυπο FormField Signature.

```python
def clone(self):
    ...
```

**Returns:** DigitalFormFieldSignature: Cloned FormField Signature instance.

### Παράδειγμα

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Κλωνοποίηση μιας υπογραφής μεταδεδομένων με μια νέα τιμή
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Δείτε επίσης
* class [`DigitalFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/digitalformfieldsignature/)
