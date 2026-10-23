---
title: "طريقة add"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "إضافة مثيل MetadataSignature موجود إلى المجموعة."
type: docs
url: /ar/python-net/groupdocs.signature.options/metadatasignoptions/add/
is_root: false
weight: 1010
---


## add {#metadata_signature}

إضافة مثيل MetadataSignature موجود إلى المجموعة.

```python
def add(self, metadata_signature):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| metadata_signature | `MetadataSignature` | الكائن MetadataSignature الحالي الذي سيتم إضافته. |

**Returns:** The MetadataSignOptions instance.

### مثال

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr.Scherlock Holmes"))
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s)")
```

### انظر أيضًا
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
