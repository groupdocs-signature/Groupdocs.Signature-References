---
title: "save_document_on_empty_update خاصية"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "العلم الذي يحدد ما إذا كان سيتم إعادة حفظ المستند الأصلي عندما لا يحتوي أسلوب Update على توقيعات لتحديثها."
type: docs
url: /ar/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 2060
---


## save_document_on_empty_update property

العلم الذي يحدد ما إذا كان يتم حفظ المستند الأصلي مرة أخرى عندما لا يحتوي أسلوب `Update` على توقيعات لتحديثها.

إذا تم تعيينه إلى `True` (الافتراضي)، يتم حفظ المستند بسجل عملية تاريخية مقابلة (التاريخ ونوع العملية) حتى عندما لا يتم تحديث أي توقيعات. عندما يتم تعيينه إلى `False`، لا يتم تعديل المستند الأصلي على الإطلاق.

### Definition:
```python
@property
def save_document_on_empty_update(self):
    ...
@save_document_on_empty_update.setter
def save_document_on_empty_update(self, value):
    ...
```

### انظر أيضًا
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
