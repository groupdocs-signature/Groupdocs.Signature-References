---
title: "méthode clone"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Cloner l'instance de signature."
type: docs
url: /fr/python-net/groupdocs.signature.domain/basesignature/clone/
is_root: false
weight: 1010
---


## clone

Cloner l'instance de signature.

```python
def clone(self):
    ...
```

**Returns:** The cloned `Signature` instance.

### Exemple

```python
    from datetime import datetime
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Cloner une signature metadata avec une nouvelle valeur
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### Voir aussi
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)
