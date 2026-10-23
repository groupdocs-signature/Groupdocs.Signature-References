---
title: "include_standard_metadata_signatures خاصية"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "العلم الذي يشير إلى ما إذا كانت توقيعات بيانات التعريف القياسية للمستند مثل المؤلف، المالك، تاريخ الإنشاء، وتاريخ التعديل مُدرجة في قائمة بيانات التعريف."
type: docs
url: /ar/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/
is_root: false
weight: 2020
---


## include_standard_metadata_signatures property

العلم الذي يشير إلى ما إذا كانت توقيعات بيانات التعريف القياسية للمستند مثل المؤلف، المالك، تاريخ الإنشاء، وتاريخ التعديل مُدرجة في قائمة بيانات التعريف.

إذا تم تعيينه إلى False (الافتراضي)، فإن GetDocumentInfo لن يتضمن هذه التواقيع الوصفية. عندما يتم تعيينه إلى True، ستتضمن معلومات المستند التواقيع الوصفية القياسية.

### Definition:
```python
@property
def include_standard_metadata_signatures(self):
    ...
@include_standard_metadata_signatures.setter
def include_standard_metadata_signatures(self, value):
    ...
```

### انظر أيضًا
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
