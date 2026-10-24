---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een PresentationMetadataSignature met de opgegeven naam en een lege waarde."
type: docs
url: /nl/python-net/groupdocs.signature.domain/presentationmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initialiseert een PresentationMetadataSignature met de opgegeven naam en een lege waarde.

```python
def __init__(self, name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| name | `str` | Presentation Metadata Signature naam. |

## __init__ {#name-value}

Initialiseert een PresentationMetadataSignature met vooraf gedefinieerde waarden.

```python
def __init__(self, name, value):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| name | `str` | Naam van het metadata‑handtekeningobject. |
| value | `Any` | Waarde van de metadata‑handtekening. |

### Voorbeeld

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PresentationMetadataSignature

with Signature("sample.ppsx") as signature:
    options = MetadataSignOptions()
    signatures = [
        PresentationMetadataSignature("Author", "Mr. Sherlock Holmes"),
        PresentationMetadataSignature("DateCreated", datetime.now()),
        PresentationMetadataSignature("DocumentId", 123456),
        PresentationMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.ppsx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### Zie ook
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
