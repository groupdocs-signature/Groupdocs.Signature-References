---
title: "clone-Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Klont die FormField-Signaturinstanz."
type: docs
url: /de/python-net/groupdocs.signature.domain/comboboxformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

Klont die FormField-Signaturinstanz.

```python
def clone(self):
    ...
```

**Returns:** A cloned FormField signature instance.

### Beispiel

```python
from groupdocs.signature.domain import ComboboxFormFieldSignature

# Erstelle eine originale Combobox-Formularfeld-Signatur
original = ComboboxFormFieldSignature()

# Kopiere die Signatur
cloned = original.clone()
```

### Siehe auch
* class [`ComboboxFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/)
