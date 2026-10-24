---
title: "clone metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Klona signaturinstansen."
type: docs
url: /sv/python-net/groupdocs.signature.domain/basesignature/clone/
is_root: false
weight: 1010
---


## clone

Klona signaturinstansen.

```python
def clone(self):
    ...
```

**Returns:** The cloned `Signature` instance.

### Exempel

```python
    from datetime import datetime
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Klona en metadata‑signatur med ett nytt värde
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### Se även
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)
