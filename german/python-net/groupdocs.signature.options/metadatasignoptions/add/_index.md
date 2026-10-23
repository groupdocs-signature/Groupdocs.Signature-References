---
title: "add Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Fügt eine vorhandene MetadataSignature‑Instanz zur Sammlung hinzu."
type: docs
url: /de/python-net/groupdocs.signature.options/metadatasignoptions/add/
is_root: false
weight: 1010
---


## add {#metadata_signature}

Fügt eine vorhandene MetadataSignature‑Instanz zur Sammlung hinzu.

```python
def add(self, metadata_signature):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| metadata_signature | `MetadataSignature` | Die vorhandene MetadataSignature‑Instanz, die hinzugefügt werden soll. |

**Returns:** The MetadataSignOptions instance.

### Beispiel

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

### Siehe auch
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
