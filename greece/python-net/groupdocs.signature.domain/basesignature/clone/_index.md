---
title: "μέθοδος clone"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Κλωνοποίηση στιγμιότυπου υπογραφής."
type: docs
url: /el/python-net/groupdocs.signature.domain/basesignature/clone/
is_root: false
weight: 1010
---


## clone

Κλωνοποίηση στιγμιότυπου υπογραφής.

```python
def clone(self):
    ...
```

**Returns:** The cloned `Signature` instance.

### Παράδειγμα

```python
    from datetime import datetime
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Κλωνοποίηση μιας υπογραφής μεταδεδομένων με μια νέα τιμή
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### Δείτε επίσης
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)
