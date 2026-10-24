---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una nuova istanza della classe MetadataSearchOptions con i valori predefiniti."
type: docs
url: /it/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe MetadataSearchOptions con i valori predefiniti.

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    print(f"Found {len(result.signatures)} metadata signature(s)")
```

### Vedi anche
* class [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/)
