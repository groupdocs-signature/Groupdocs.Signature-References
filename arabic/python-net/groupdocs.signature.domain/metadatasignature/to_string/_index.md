---
title: "طريقة to_string"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحول توقيع البيانات الوصفية إلى سلسلة نصية."
type: docs
url: /ar/python-net/groupdocs.signature.domain/metadatasignature/to_string/
is_root: false
weight: 1180
---


## to_string

يحول توقيع البيانات الوصفية إلى سلسلة نصية.

يقوم بتحويل خاصية منطقية إلى "True" أو "False". بالنسبة لأنواع البيانات الأخرى سيتم استخدام مزود تنسيق البيانات الافتراضي.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format}

يحول توقيع البيانات الوصفية إلى سلسلة نصية باستخدام التنسيق المحدد.

يقوم بتحويل خاصية منطقية إلى "True" أو "False". سيتم استخدام معلومات خاصية الثقافة الافتراضية من خصائص SignatureSettings [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_string(self, format):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| format | `str` | سلسلة تنسيق البيانات. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

يحول إلى سلسلة نصية بالتنسيق المحدد.

يقوم بتحويل خاصية منطقية إلى "True" أو "False".

```python
def to_string(self, format, provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| format | `str` | سلسلة تنسيق البيانات. |
| provider | `System.IFormatProvider` | مزود تنسيق البيانات للاستخدام مع عمليات تحويل البيانات. |

**Returns:** The metadata signature value as a string.

### انظر أيضًا
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
