---
title: "طريقة to_single"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحول قيمة توقيع البيانات الوصفية إلى عدد عائم."
type: docs
url: /ar/python-net/groupdocs.signature.domain/metadatasignature/to_single/
is_root: false
weight: 1160
---


## to_single

يحول قيمة توقيع البيانات الوصفية إلى عدد عائم.

يثير استثناءً إذا لم يتم تحويل قيمة metadata. إذا كانت القيمة الأصلية قائمة على سلسلة، يتم استخدام الثقافة الافتراضية من [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_single(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_single {#provider}

يحول إلى عدد عائم.

```python
def to_single(self, provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| provider | `System.IFormatProvider` | مزود تنسيق البيانات للاستخدام مع عمليات تحويل البيانات. |

**Returns:** float: The Metadata Signature value as float.

### انظر أيضًا
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
