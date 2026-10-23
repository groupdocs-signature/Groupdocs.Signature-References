---
title: "save_document_on_empty_delete خاصية"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "العلم الذي يحدد ما إذا كان يتم حفظ المستند الأصلي مرة أخرى عندما لا يحتوي أسلوب Delete على توقيعات متأثرة لإزالتها."
type: docs
url: /ar/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 2050
---


## save_document_on_empty_delete property

العلم الذي يحدد ما إذا كان يتم حفظ المستند الأصلي مرة أخرى عندما لا يحتوي أسلوب Delete على توقيعات متأثرة لإزالتها.

عند True (الافتراضي)، يتم حفظ المستند بسجل تاريخي (التاريخ ونوع العملية) حتى إذا لم تُحذف أي توقيعات؛ عند False، يظل المستند الأصلي دون تغيير.

### Definition:
```python
@property
def save_document_on_empty_delete(self):
    ...
@save_document_on_empty_delete.setter
def save_document_on_empty_delete(self, value):
    ...
```

### انظر أيضًا
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
