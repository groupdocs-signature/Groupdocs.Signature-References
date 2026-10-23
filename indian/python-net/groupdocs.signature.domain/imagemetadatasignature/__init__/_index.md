---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "निर्दिष्ट पहचानकर्ता और मान के साथ एक Image Metadata Signature को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#id-value}

निर्दिष्ट पहचानकर्ता और मान के साथ एक Image Metadata Signature को प्रारंभ करता है।

```python
def __init__(self, id, value):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| id | `System.UInt16` | Image Metadata Signature के लिए अद्वितीय पहचानकर्ता। संभावित id मानों के लिए EXIF टैग विशिष्टताओं के संदर्भ देखें। |
| value | `Any` | मेटाडाटा मान। |

### उदाहरण

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

### संबंधित देखें
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
