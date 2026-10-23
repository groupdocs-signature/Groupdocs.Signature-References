---
title: "طريقة try_parse"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يرجع نوع Barcode المطابق لاسم نوع التحليل المعطى."
type: docs
url: /ar/python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

يرجع نوع Barcode المطابق لاسم نوع التحليل المعطى.

إذا كان الاسم غير معروف، تُعيد الطريقة القيمة None بدلاً من رفع استثناء.

```python
def try_parse(cls, parsing_type):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| parsing_type | `str` | سلسلة المصدر لاسم نوع الباركود. |

**Returns:** BarcodeType: The matching BarcodeType instance, or None if not found.

### انظر أيضًا
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
