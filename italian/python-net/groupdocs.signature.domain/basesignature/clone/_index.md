---
title: "metodo clone"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Clona l'istanza della firma."
type: docs
url: /it/python-net/groupdocs.signature.domain/basesignature/clone/
is_root: false
weight: 1010
---


## clone

Clona l'istanza della firma.

```python
def clone(self):
    ...
```

**Returns:** The cloned `Signature` instance.

### Esempio

```python
    from datetime import datetime
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Clona una firma metadata con un nuovo valore
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### Vedi anche
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)
