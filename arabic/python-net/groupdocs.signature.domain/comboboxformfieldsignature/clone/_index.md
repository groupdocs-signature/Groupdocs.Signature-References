---
title: "طريقة clone"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "ينسخ نسخة من كائن التوقيع FormField."
type: docs
url: /ar/python-net/groupdocs.signature.domain/comboboxformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

ينسخ نسخة من كائن التوقيع FormField.

```python
def clone(self):
    ...
```

**Returns:** A cloned FormField signature instance.

### مثال

```python
from groupdocs.signature.domain import ComboboxFormFieldSignature

# إنشاء توقيع حقل نموذج صندوق اختيار أصلي
original = ComboboxFormFieldSignature()

# استنساخ التوقيع
cloned = original.clone()
```

### انظر أيضًا
* class [`ComboboxFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/)
