---
title: "add-methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Voeg een bestaande MetadataSignature‑instantie toe aan de collectie."
type: docs
url: /nl/python-net/groupdocs.signature.options/metadatasignoptions/add/
is_root: false
weight: 1010
---


## add {#metadata_signature}

Voeg een bestaande MetadataSignature‑instantie toe aan de collectie.

```python
def add(self, metadata_signature):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| metadata_signature | `MetadataSignature` | De bestaande MetadataSignature‑instantie die moet worden toegevoegd. |

**Returns:** The MetadataSignOptions instance.

### Voorbeeld

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

### Zie ook
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
