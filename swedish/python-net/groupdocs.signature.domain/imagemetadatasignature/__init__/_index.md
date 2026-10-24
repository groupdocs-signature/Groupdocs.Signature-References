---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en Image Metadata Signature med det angivna identifieraren och värdet."
type: docs
url: /sv/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#id-value}

Initierar en Image Metadata Signature med det angivna identifieraren och värdet.

```python
def __init__(self, id, value):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| id | `System.UInt16` | Unik identifierare för Image Metadata‑signaturen. Se referenser för EXIF‑taggspecifikationer för möjliga id‑värden. |
| value | `Any` | Metadata‑värdet. |

### Exempel

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import ImageMetadataSignature

with Signature("sample.png") as signature:
    options = MetadataSignOptions()
    metadata_id = 41996
    options.add(ImageMetadataSignature(metadata_id, "Mr. Sherlock Holmes"))  # text
    options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
    options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # integer
    options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # float
    result = signature.sign("signed.png", options)
```

### Se även
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
