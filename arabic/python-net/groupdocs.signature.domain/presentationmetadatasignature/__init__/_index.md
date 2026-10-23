---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُهيئ PresentationMetadataSignature بالاسم المحدد وقيمة فارغة."
type: docs
url: /ar/python-net/groupdocs.signature.domain/presentationmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

يُهيئ PresentationMetadataSignature بالاسم المحدد وقيمة فارغة.

```python
def __init__(self, name):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| name | `str` | اسم Presentation Metadata Signature. |

## __init__ {#name-value}

يُهيئ PresentationMetadataSignature بقيم محددة مسبقًا.

```python
def __init__(self, name, value):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| name | `str` | اسم كائن توقيع بيانات التعريف. |
| value | `Any` | قيمة توقيع بيانات التعريف. |

### مثال

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

### انظر أيضًا
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
