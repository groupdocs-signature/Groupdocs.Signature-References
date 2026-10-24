---
title: "metodo clone"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Clona l'istanza di FormField Signature."
type: docs
url: /it/python-net/groupdocs.signature.domain/digitalformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

Clona l'istanza di FormField Signature.

```python
def clone(self):
    ...
```

**Returns:** DigitalFormFieldSignature: Cloned FormField Signature instance.

### Esempio

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Clona una firma metadata con un nuovo valore
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Vedi anche
* class [`DigitalFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/digitalformfieldsignature/)
