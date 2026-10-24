---
title: "metodo add"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Aggiungi un'istanza esistente di MetadataSignature alla raccolta."
type: docs
url: /it/python-net/groupdocs.signature.options/metadatasignoptions/add/
is_root: false
weight: 1010
---


## add {#metadata_signature}

Aggiungi un'istanza esistente di MetadataSignature alla raccolta.

```python
def add(self, metadata_signature):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| metadata_signature | `MetadataSignature` | L'istanza MetadataSignature esistente da aggiungere. |

**Returns:** The MetadataSignOptions instance.

### Esempio

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

### Vedi anche
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
