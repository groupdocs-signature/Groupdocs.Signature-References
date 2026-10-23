---
title: "طريقة to_string"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحوّل توقيع البيانات الوصفية إلى سلسلة باستخدام الطريقة ToString المعاد تعريفها."
type: docs
url: /ar/python-net/groupdocs.signature.domain/certificatemetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

يحوّل توقيع البيانات الوصفية إلى سلسلة باستخدام الطريقة ToString المعاد تعريفها.

يقوم بتحويل خاصية منطقية إلى "True" أو "False". بالنسبة لأنواع البيانات الأخرى يتم استخدام موفر تنسيق البيانات الافتراضي.

```python
def to_string(self):
    ...
```

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

**Returns:** The metadata signature value as a string.

### انظر أيضًا
* class [`CertificateMetadataSignature`](/signature/python-net/groupdocs.signature.domain/certificatemetadatasignature/)
