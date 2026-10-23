---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُهيئ توقيع بيانات وصفية للصورة بالمعرف والقيمة المحددين."
type: docs
url: /ar/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#id-value}

يُهيئ توقيع بيانات وصفية للصورة بالمعرف والقيمة المحددين.

```python
def __init__(self, id, value):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| id | `System.UInt16` | معرّف فريد لتوقيع Image Metadata Signature. راجع المراجع لمواصفات وسوم EXIF للقيم المحتملة للمعرّف. |
| value | `Any` | قيمة البيانات الوصفية. |

### مثال

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

### انظر أيضًا
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
