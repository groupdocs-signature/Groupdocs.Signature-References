---
title: "clone methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Kloon handtekeninginstantie."
type: docs
url: /nl/python-net/groupdocs.signature.domain/basesignature/clone/
is_root: false
weight: 1010
---


## clone

Kloon handtekeninginstantie.

```python
def clone(self):
    ...
```

**Returns:** The cloned `Signature` instance.

### Voorbeeld

```python
    from datetime import datetime
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Kloon een metadata-handtekening met een nieuwe waarde
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### Zie ook
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)
