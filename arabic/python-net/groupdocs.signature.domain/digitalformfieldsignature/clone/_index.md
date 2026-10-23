---
title: "طريقة clone"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "ينسخ نسخة من كائن FormField Signature."
type: docs
url: /ar/python-net/groupdocs.signature.domain/digitalformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

ينسخ نسخة من كائن FormField Signature.

```python
def clone(self):
    ...
```

**Returns:** DigitalFormFieldSignature: Cloned FormField Signature instance.

### مثال

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# استنساخ توقيع بيانات التعريف بقيمة جديدة
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### انظر أيضًا
* class [`DigitalFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/digitalformfieldsignature/)
