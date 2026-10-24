---
title: "clone methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Kloont FormField Signature‑instantie."
type: docs
url: /nl/python-net/groupdocs.signature.domain/digitalformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

Kloont FormField Signature‑instantie.

```python
def clone(self):
    ...
```

**Returns:** DigitalFormFieldSignature: Cloned FormField Signature instance.

### Voorbeeld

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Kloon een metadata-handtekening met een nieuwe waarde
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Zie ook
* class [`DigitalFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/digitalformfieldsignature/)
