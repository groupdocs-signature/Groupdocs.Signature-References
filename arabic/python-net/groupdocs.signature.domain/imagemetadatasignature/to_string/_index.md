---
title: "طريقة to_string"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحوّل قيمة توقيع البيانات الوصفية إلى سلسلة نصية."
type: docs
url: /ar/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/
is_root: false
weight: 1170
---


## to_string

يحوّل قيمة توقيع البيانات الوصفية إلى سلسلة نصية.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value.

## to_string {#format}

يحوّل قيمة توقيع البيانات الوصفية إلى سلسلة نصية باستخدام التنسيق المحدد.

يقوم بتحويل خاصية منطقية إلى "True" أو "False". يتم استخدام معلومات الثقافة الافتراضية من [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_string(self, format):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| format | `str` | سلسلة تنسيق البيانات. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

يحوِّل إلى سلسلة بالتنسيق المحدد.

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
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
