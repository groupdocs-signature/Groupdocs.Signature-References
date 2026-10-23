---
title: "طريقة to_decimal"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحول قيمة توقيع البيانات الوصفية إلى عدد عشري."
type: docs
url: /ar/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/
is_root: false
weight: 1110
---


## to_decimal

يحول قيمة توقيع البيانات الوصفية إلى عدد عشري.

يرفع استثناءً إذا تعذر تحويل قيمة البيانات الوصفية. إذا كانت القيمة الأصلية نصية، سيتم استخدام معلومات خاصية الثقافة الافتراضية من [`SignatureSettings.DefaultCulture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_decimal(self):
    ...
```

**Returns:** The metadata signature value as Decimal.

## to_decimal {#provider}

يحول قيمة توقيع البيانات الوصفية إلى عدد عشري.

```python
def to_decimal(self, provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| provider | `System.IFormatProvider` | مزود تنسيق البيانات للاستخدام مع عمليات تحويل البيانات. |

**Returns:** The metadata signature value as Decimal.

### انظر أيضًا
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
