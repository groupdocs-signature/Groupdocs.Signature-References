---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en PresentationMetadataSignature med det angivna namnet och ett tomt värde."
type: docs
url: /sv/python-net/groupdocs.signature.domain/presentationmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initierar en PresentationMetadataSignature med det angivna namnet och ett tomt värde.

```python
def __init__(self, name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| name | `str` | Presentation Metadata Signature‑namn. |

## __init__ {#name-value}

Initierar en PresentationMetadataSignature med fördefinierade värden.

```python
def __init__(self, name, value):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| name | `str` | Namn på metadata‑signaturobjektet. |
| value | `Any` | Värde för metadata‑signaturen. |

### Exempel

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

### Se även
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
