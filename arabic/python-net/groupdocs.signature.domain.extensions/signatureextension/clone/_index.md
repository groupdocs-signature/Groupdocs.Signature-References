---
title: "طريقة clone"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحصل على نسخة من هذا الكائن."
type: docs
url: /ar/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/
is_root: false
weight: 1010
---


## clone

يحصل على نسخة من هذا الكائن.

```python
def clone(self):
    ...
```

### مثال

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    # استنساخ توقيع بيانات التعريف بقيمة جديدة
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    options.signatures.add(author_sig)
```

### انظر أيضًا
* class [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)
