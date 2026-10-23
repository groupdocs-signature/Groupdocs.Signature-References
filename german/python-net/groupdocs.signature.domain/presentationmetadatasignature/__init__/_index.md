---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert ein PresentationMetadataSignature mit dem angegebenen Namen und einem leeren Wert."
type: docs
url: /de/python-net/groupdocs.signature.domain/presentationmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initialisiert ein PresentationMetadataSignature mit dem angegebenen Namen und einem leeren Wert.

```python
def __init__(self, name):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| name | `str` | Presentation Metadata Signature Name. |

## __init__ {#name-value}

Initialisiert ein PresentationMetadataSignature mit vordefinierten Werten.

```python
def __init__(self, name, value):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| name | `str` | Name des Metadaten-Signaturobjekts. |
| value | `Any` | Wert der Metadaten-Signatur. |

### Beispiel

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

### Siehe auch
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
