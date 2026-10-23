---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُهيئ Spreadsheet Metadata Signature بالاسم المحدد مسبقًا والقيمة الفارغة."
type: docs
url: /ar/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

يُهيئ Spreadsheet Metadata Signature بالاسم المحدد مسبقًا والقيمة الفارغة.

```python
def __init__(self, name):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| name | `str` | اسم توقيع بيانات جدول البيانات. |

## __init__ {#name-value}

يُهيئ Spreadsheet Metadata Signature بقيم محددة مسبقًا.

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
from groupdocs.signature.domain import SpreadsheetMetadataSignature

# إنشاء توقيعات بيانات تعريفية لجدول بيانات
author_sig = SpreadsheetMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = SpreadsheetMetadataSignature("DateCreated", datetime.now())
id_sig = SpreadsheetMetadataSignature("DocumentId", 123456)
float_sig = SpreadsheetMetadataSignature("SignatureId", 123.456)
```

### انظر أيضًا
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
