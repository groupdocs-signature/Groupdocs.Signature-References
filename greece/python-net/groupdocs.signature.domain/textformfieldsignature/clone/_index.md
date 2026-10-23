---
title: "μέθοδος clone"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Κλωνοποιεί το αντίτυπο FormField Signature."
type: docs
url: /el/python-net/groupdocs.signature.domain/textformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

Κλωνοποιεί το αντίτυπο FormField Signature.

```python
def clone(self):
    ...
```

**Returns:** TextFormFieldSignature: Cloned FormField Signature instance.

### Παράδειγμα

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    new_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### Δείτε επίσης
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
