---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en WordProcessingMetadataSignature med det angivna namnet och ett tomt värde."
type: docs
url: /sv/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initierar en WordProcessingMetadataSignature med det angivna namnet och ett tomt värde.

```python
def __init__(self, name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| name | `str` | WordProcessing Metadata Signature‑namn. |

### Exempel

```python
from datetime import datetime
from groupdocs.signature.domain import WordProcessingMetadataSignature

# Skapa metadatasignaturer med namn och värde
author_sig = WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = WordProcessingMetadataSignature("DateCreated", datetime.now())
id_sig = WordProcessingMetadataSignature("DocumentId", 123456)
float_sig = WordProcessingMetadataSignature("SignatureId", 123.456)
```

## __init__ {#name-value}

Initierar en WordProcessing-metadata-signatur med fördefinierade värden.

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

### Se även
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
