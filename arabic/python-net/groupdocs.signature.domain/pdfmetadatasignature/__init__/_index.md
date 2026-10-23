---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُهيئ توقيع بيانات تعريف PDF باسم محدد مسبقًا وقيمة فارغة."
type: docs
url: /ar/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

يُهيئ توقيع بيانات تعريف PDF باسم محدد مسبقًا وقيمة فارغة.

```python
def __init__(self, name):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| name | `str` | اسم توقيع بيانات تعريف PDF. |

## __init__ {#name-value}

يُهيئ توقيع بيانات تعريف PDF بقيم محددة مسبقًا.

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
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr. Sherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
```

## __init__ {#name-value-tag}

يُهيئ توقيع بيانات تعريف PDF بقيم محددة مسبقًا.

```python
def __init__(self, name, value, tag):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| name | `str` | اسم كائن توقيع بيانات التعريف. |
| value | `Any` | قيمة توقيع بيانات التعريف. |
| tag | `str` | علامة البادئة لتوقيع بيانات التعريف. |

### مثال

```python
from groupdocs.signature.domain import PdfMetadataSignature

# إنشاء توقيع بيانات تعريف لمؤلف PDF
author_sig = PdfMetadataSignature("Author", "Mr. Sherlock Holmes")

# إنشاء توقيع بيانات تعريف لتاريخ الإنشاء
from datetime import datetime
created_sig = PdfMetadataSignature("CreatedOn", datetime.now())

# إنشاء توقيع بيانات تعريف لمعرّف رقمي
id_sig = PdfMetadataSignature("DocumentId", 123456)

# إنشاء توقيع بيانات تعريف لقيمة عددية عائمة
float_sig = PdfMetadataSignature("SignatureId", 123.456)
```

### انظر أيضًا
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
