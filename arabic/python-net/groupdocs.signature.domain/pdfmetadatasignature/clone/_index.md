---
title: "طريقة clone"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "استنساخ كائن Metadata Signature."
type: docs
url: /ar/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/
is_root: false
weight: 1010
---


## clone

استنساخ كائن Metadata Signature.

```python
def clone(self):
    ...
```

**Returns:** PdfMetadataSignature: Cloned Metadata Signature instance.

### مثال

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    # استنساخ توقيع بيانات تعريف قياسي بقيمة جديدة
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

## clone {#value}

ينسخ كائن توقيع بيانات تعريف PDF بالقيمة المعطاة.

```python
def clone(self, value):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| value | `Any` | القيمة للكائن المستنسخ الجديد. |

**Returns:** A cloned metadata signature instance.

### مثال

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# استنساخ توقيع بيانات تعريف موجود بقيمة جديدة
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### انظر أيضًا
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
