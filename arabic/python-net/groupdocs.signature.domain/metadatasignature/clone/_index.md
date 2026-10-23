---
title: "طريقة clone"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "ينسخ نسخة من كائن توقيع البيانات الوصفية."
type: docs
url: /ar/python-net/groupdocs.signature.domain/metadatasignature/clone/
is_root: false
weight: 1010
---


## clone

ينسخ نسخة من كائن توقيع البيانات الوصفية.

```python
def clone(self):
    ...
```

**Returns:** Returns cloned Metadata Signature instance.

### مثال

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# إنشاء توقيع metadata جديد بناءً على توقيع AUTHOR المحدد مسبقًا
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

## clone {#value}

انسخ كائن توقيع البيانات الوصفية بالقيمة المعطاة.

```python
def clone(self, value):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| value | `Any` | القيمة للكائن المستنسخ الجديد. |

**Returns:** MetadataSignature: Cloned Metadata Signature instance with given value.

### مثال

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# استنساخ توقيع بيانات تعريف موجود بقيمة جديدة
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### انظر أيضًا
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
