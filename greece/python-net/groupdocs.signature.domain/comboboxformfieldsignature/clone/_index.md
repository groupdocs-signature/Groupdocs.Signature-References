---
title: "μέθοδος clone"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Κλωνοποιεί το στιγμιότυπο υπογραφής FormField."
type: docs
url: /el/python-net/groupdocs.signature.domain/comboboxformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

Κλωνοποιεί το στιγμιότυπο υπογραφής FormField.

```python
def clone(self):
    ...
```

**Returns:** A cloned FormField signature instance.

### Παράδειγμα

```python
from groupdocs.signature.domain import ComboboxFormFieldSignature

# Δημιουργήστε μια αρχική υπογραφή πεδίου φόρμας combobox
original = ComboboxFormFieldSignature()

# Κλωνοποιήστε την υπογραφή
cloned = original.clone()
```

### Δείτε επίσης
* class [`ComboboxFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/)
