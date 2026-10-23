---
title: "طريقة to_double"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحول قيمة توقيع البيانات الوصفية إلى عدد عائم."
type: docs
url: /ar/python-net/groupdocs.signature.domain/metadatasignature/to_double/
is_root: false
weight: 1130
---


## to_double

يحول قيمة توقيع البيانات الوصفية إلى عدد عائم.

يرفع استثناءً إذا تعذر تحويل قيمة البيانات الوصفية. إذا كانت القيمة الأصلية نصية، يتم استخدام الثقافة الافتراضية من [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_double(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_double {#provider}

يحول إلى مزدوج.

```python
def to_double(self, provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| provider | `System.IFormatProvider` | مزود تنسيق البيانات للاستخدام مع عمليات تحويل البيانات. |

**Returns:** float: The metadata signature value as a float.

### انظر أيضًا
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
