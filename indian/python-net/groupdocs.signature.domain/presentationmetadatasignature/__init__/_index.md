---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "निर्दिष्ट नाम और खाली मान के साथ एक PresentationMetadataSignature को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/presentationmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

निर्दिष्ट नाम और खाली मान के साथ एक PresentationMetadataSignature को प्रारंभ करता है।

```python
def __init__(self, name):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| name | `str` | Presentation Metadata Signature नाम। |

## __init__ {#name-value}

पूर्वनिर्धारित मानों के साथ एक PresentationMetadataSignature को प्रारंभ करता है।

```python
def __init__(self, name, value):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| name | `str` | मेटाडाटा सिग्नेचर ऑब्जेक्ट का नाम। |
| value | `Any` | मेटाडाटा सिग्नेचर का मान। |

### उदाहरण

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

### संबंधित देखें
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
