---
title: "méthode add"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Ajoute une instance existante de MetadataSignature à la collection."
type: docs
url: /fr/python-net/groupdocs.signature.options/metadatasignoptions/add/
is_root: false
weight: 1010
---


## add {#metadata_signature}

Ajoute une instance existante de MetadataSignature à la collection.

```python
def add(self, metadata_signature):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| metadata_signature | `MetadataSignature` | L'instance MetadataSignature existante à ajouter. |

**Returns:** The MetadataSignOptions instance.

### Exemple

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

### Voir aussi
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
