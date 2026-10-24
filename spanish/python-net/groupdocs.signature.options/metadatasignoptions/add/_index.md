---
title: "método add"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Agregar una instancia existente de MetadataSignature a la colección."
type: docs
url: /es/python-net/groupdocs.signature.options/metadatasignoptions/add/
is_root: false
weight: 1010
---


## add {#metadata_signature}

Agregar una instancia existente de MetadataSignature a la colección.

```python
def add(self, metadata_signature):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| metadata_signature | `MetadataSignature` | La instancia existente de MetadataSignature que se añadirá. |

**Returns:** The MetadataSignOptions instance.

### Ejemplo

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr.Scherlock Holmes"))
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s)")
```

### Ver también
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
