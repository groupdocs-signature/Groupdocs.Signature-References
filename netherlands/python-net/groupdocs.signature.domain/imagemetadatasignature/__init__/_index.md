---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een Image Metadata Signature met de opgegeven identifier en waarde."
type: docs
url: /nl/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#id-value}

Initialiseert een Image Metadata Signature met de opgegeven identifier en waarde.

```python
def __init__(self, id, value):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| id | `System.UInt16` | Unieke identifier voor de Image Metadata Signature. Zie referenties voor EXIF‑tag‑specificaties voor mogelijke id‑waarden. |
| value | `Any` | De metadata‑waarde. |

### Voorbeeld

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

### Zie ook
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
