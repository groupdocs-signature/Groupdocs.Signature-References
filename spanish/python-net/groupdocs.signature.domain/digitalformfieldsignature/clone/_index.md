---
title: "clone método"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Clona la instancia de FormField Signature."
type: docs
url: /es/python-net/groupdocs.signature.domain/digitalformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

Clona la instancia de FormField Signature.

```python
def clone(self):
    ...
```

**Returns:** DigitalFormFieldSignature: Cloned FormField Signature instance.

### Ejemplo

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Clonar una firma de metadatos con un nuevo valor
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Ver también
* class [`DigitalFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/digitalformfieldsignature/)
