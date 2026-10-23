---
title: "طريقة to_single"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحول إلى عدد عائم."
type: docs
url: /ar/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/
is_root: false
weight: 1150
---


## to_single

يحول إلى عدد عائم.

يرمي استثناءً إذا تعذر تحويل قيمة Metadata. إذا كانت القيمة الأصلية نصية، سيتم استخدام معلومات خاصية الثقافة الافتراضية من [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_single(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as float.

## to_single {#provider}

يحول قيمة توقيع البيانات الوصفية إلى عدد عائم.

يثير استثناءً إذا تعذر تحويل قيمة البيانات الوصفية.

```python
def to_single(self, provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| provider | `System.IFormatProvider` | مزود تنسيق البيانات للاستخدام مع عمليات تحويل البيانات. |

**Returns:** float: The metadata signature value as a float.

### انظر أيضًا
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
