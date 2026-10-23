---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُهيئ WordProcessingMetadataSignature بالاسم المحدد وقيمة فارغة."
type: docs
url: /ar/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

يُهيئ WordProcessingMetadataSignature بالاسم المحدد وقيمة فارغة.

```python
def __init__(self, name):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| name | `str` | اسم WordProcessing Metadata Signature. |

### مثال

```python
from datetime import datetime
from groupdocs.signature.domain import WordProcessingMetadataSignature

# إنشاء توقيعات البيانات الوصفية بالاسم والقيمة
author_sig = WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = WordProcessingMetadataSignature("DateCreated", datetime.now())
id_sig = WordProcessingMetadataSignature("DocumentId", 123456)
float_sig = WordProcessingMetadataSignature("SignatureId", 123.456)
```

## __init__ {#name-value}

يُهيئ توقيع بيانات وصفية لمعالجة النصوص بقيم مسبقة.

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

### انظر أيضًا
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
