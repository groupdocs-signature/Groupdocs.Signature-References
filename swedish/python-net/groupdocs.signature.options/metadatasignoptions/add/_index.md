---
title: "add metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Lägg till befintlig MetadataSignature‑instans i samlingen."
type: docs
url: /sv/python-net/groupdocs.signature.options/metadatasignoptions/add/
is_root: false
weight: 1010
---


## add {#metadata_signature}

Lägg till befintlig MetadataSignature‑instans i samlingen.

```python
def add(self, metadata_signature):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| metadata_signature | `MetadataSignature` | Den befintliga MetadataSignature‑instansen som ska läggas till. |

**Returns:** The MetadataSignOptions instance.

### Exempel

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

### Se även
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
