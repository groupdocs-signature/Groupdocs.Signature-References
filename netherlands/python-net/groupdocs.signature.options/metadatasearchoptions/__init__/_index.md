---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de MetadataSearchOptions klasse met standaardwaarden."
type: docs
url: /nl/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de MetadataSearchOptions klasse met standaardwaarden.

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    print(f"Found {len(result.signatures)} metadata signature(s)")
```

### Zie ook
* class [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/)
