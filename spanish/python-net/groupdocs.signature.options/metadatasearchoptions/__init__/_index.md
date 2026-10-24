---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase MetadataSearchOptions con valores predeterminados."
type: docs
url: /es/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase MetadataSearchOptions con valores predeterminados.

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    print(f"Found {len(result.signatures)} metadata signature(s)")
```

### Ver también
* class [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/)
