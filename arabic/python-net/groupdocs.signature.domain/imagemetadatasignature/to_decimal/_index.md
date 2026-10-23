---
title: "طريقة to_decimal"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحوّل إلى Decimal."
type: docs
url: /ar/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/
is_root: false
weight: 1090
---


## to_decimal

يحوّل إلى Decimal.

يرفع استثناءً إذا تعذر تحويل قيمة البيانات الوصفية. إذا كانت القيمة الأصلية نصية، يتم استخدام الثقافة الافتراضية من [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_decimal(self):
    ...
```

**Returns:** decimal.Decimal: The Image Metadata Signature value as Decimal.

## to_decimal {#provider}

يحوّل قيمة توقيع البيانات الوصفية إلى عدد عشري.

يثير استثناءً إذا تعذر تحويل قيمة البيانات الوصفية.

```python
def to_decimal(self, provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| provider | `System.IFormatProvider` | مزود تنسيق البيانات للاستخدام مع عمليات تحويل البيانات. |

**Returns:** float: The metadata signature value as a decimal.

### انظر أيضًا
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
