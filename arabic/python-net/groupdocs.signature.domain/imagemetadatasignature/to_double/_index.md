---
title: "طريقة to_double"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحوّل إلى عدد عائم."
type: docs
url: /ar/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/
is_root: false
weight: 1110
---


## to_double

يحوّل إلى عدد عائم.

يثير استثناءً إذا لم يتم تحويل قيمة metadata. إذا كانت القيمة الأصلية قائمة على سلسلة، يتم استخدام الثقافة الافتراضية من [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_double(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as a float.

## to_double {#provider}

يحول قيمة توقيع البيانات الوصفية إلى عدد عائم.

يستخدم موفر تنسيق البيانات المحدد لإجراء التحويل.

```python
def to_double(self, provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| provider | `System.IFormatProvider` | مزود تنسيق البيانات للاستخدام مع عمليات تحويل البيانات. |

**Returns:** float: The metadata signature value as a float.

### انظر أيضًا
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
