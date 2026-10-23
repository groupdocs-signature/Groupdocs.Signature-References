---
title: "طريقة to_date_time"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحول قيمة توقيع البيانات الوصفية إلى تاريخ ووقت."
type: docs
url: /ar/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/
is_root: false
weight: 1090
---


## to_date_time

يحول قيمة توقيع البيانات الوصفية إلى تاريخ ووقت.

إذا تعذر تحويل قيمة البيانات الوصفية، يتم رفع استثناء. عندما تكون القيمة الأصلية نصية، يتم استخدام الثقافة الافتراضية من [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) للتحويل.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime: The metadata signature value as a datetime.

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    for metadata in result.signatures:
        try:
            dt = metadata.to_date_time()
            print(f"{metadata.name} as datetime: {dt}")
        except Exception as e:
            print(f"Could not convert {metadata.name} to datetime: {e}")
```

## to_date_time {#provider}

يحول قيمة توقيع البيانات الوصفية إلى تاريخ ووقت.

```python
def to_date_time(self, provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| provider | `System.IFormatProvider` | مزود تنسيق البيانات للاستخدام مع عمليات تحويل البيانات. |

**Returns:** datetime.datetime: The metadata signature value as a datetime.

يرمي استثناءً إذا تعذر تحويل قيمة البيانات الوصفية.

### انظر أيضًا
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
