---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een WordProcessingMetadataSignature met de opgegeven naam en een lege waarde."
type: docs
url: /nl/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initialiseert een WordProcessingMetadataSignature met de opgegeven naam en een lege waarde.

```python
def __init__(self, name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| name | `str` | WordProcessing Metadata Signature naam. |

### Voorbeeld

```python
from datetime import datetime
from groupdocs.signature.domain import WordProcessingMetadataSignature

# Maak metadata-handtekeningen met naam en waarde
author_sig = WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = WordProcessingMetadataSignature("DateCreated", datetime.now())
id_sig = WordProcessingMetadataSignature("DocumentId", 123456)
float_sig = WordProcessingMetadataSignature("SignatureId", 123.456)
```

## __init__ {#name-value}

Initialiseert een WordProcessing metadatavertekening met vooraf gedefinieerde waarden.

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
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### Zie ook
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
