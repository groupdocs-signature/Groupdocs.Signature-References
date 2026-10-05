---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes an Image Metadata Signature with the specified identifier and value."
type: docs
url: /python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#id-value}

Initializes an Image Metadata Signature with the specified identifier and value.

```python
def __init__(self, id, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| id | `System.UInt16` | Unique identifier for the Image Metadata Signature. See references for EXIF tag specifications for possible id values. |
| value | `Any` | The metadata value. |

### Example

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

### See Also
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
