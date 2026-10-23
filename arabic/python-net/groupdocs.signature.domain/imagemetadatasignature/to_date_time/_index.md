---
title: "طريقة to_date_time"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يقوم بتحويل قيمة توقيع البيانات الوصفية إلى datetime.datetime."
type: docs
url: /ar/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/
is_root: false
weight: 1070
---


## to_date_time

يحوّل قيمة توقيع البيانات الوصفية إلى `datetime.datetime`.

يثير استثناءً إذا لم يتم تحويل قيمة metadata. إذا كانت القيمة الأصلية قائمة على سلسلة، يتم استخدام الثقافة الافتراضية من [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_date_time(self):
    ...
```

**Returns:** datetime.datetime: The metadata signature value as a `datetime.datetime`.

## to_date_time {#provider}

يحوّل قيمة توقيع البيانات الوصفية إلى `datetime`.

يرمي استثناءً إذا تعذر تحويل قيمة البيانات الوصفية.

```python
def to_date_time(self, provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| provider | `System.IFormatProvider` | مزود تنسيق البيانات للاستخدام مع عمليات تحويل البيانات. |

**Returns:** datetime: The metadata signature value as a `datetime`.

### انظر أيضًا
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
