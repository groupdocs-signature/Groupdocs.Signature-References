---
title: "طريقة clone"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "نسخ نسخة التوقيع."
type: docs
url: /ar/python-net/groupdocs.signature.domain/basesignature/clone/
is_root: false
weight: 1010
---


## clone

نسخ نسخة التوقيع.

```python
def clone(self):
    ...
```

**Returns:** The cloned `Signature` instance.

### مثال

```python
    from datetime import datetime
    from groupdocs.signature.domain import PdfMetadataSignatures

    # استنساخ توقيع بيانات التعريف بقيمة جديدة
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### انظر أيضًا
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)
