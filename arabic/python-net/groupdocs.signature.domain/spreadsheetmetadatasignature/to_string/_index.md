---
title: "طريقة to_string"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يقوم بتحويل قيمة توقيع البيانات الوصفية إلى سلسلة باستخدام طريقة ToString المتجاوزة."
type: docs
url: /ar/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

يحوّل قيمة توقيع البيانات إلى سلسلة باستخدام الطريقة `ToString` المُعاد تعريفها.

يقوم بتحويل خاصية منطقية إلى `True` أو `False`. بالنسبة لأنواع البيانات الأخرى، يتم استخدام موفر تنسيق البيانات الافتراضي.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

يحول توقيع البيانات الوصفية إلى سلسلة نصية باستخدام التنسيق المحدد.

يقوم بتحويل خاصية منطقية إلى "True" أو "False".

```python
def to_string(self, format, provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| format | `str` | سلسلة تنسيق البيانات. |
| provider | `System.IFormatProvider` | مزود تنسيق البيانات للاستخدام مع عمليات تحويل البيانات. |

**Returns:** str: The metadata signature value as a string.

### انظر أيضًا
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
