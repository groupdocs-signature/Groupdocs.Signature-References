---
title: "clone método"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Clonar instancia de firma."
type: docs
url: /es/python-net/groupdocs.signature.domain/basesignature/clone/
is_root: false
weight: 1010
---


## clone

Clonar instancia de firma.

```python
def clone(self):
    ...
```

**Returns:** The cloned `Signature` instance.

### Ejemplo

```python
    from datetime import datetime
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Clonar una firma de metadatos con un nuevo valor
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### Ver también
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)
