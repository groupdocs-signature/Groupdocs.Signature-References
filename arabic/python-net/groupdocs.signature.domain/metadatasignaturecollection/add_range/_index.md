---
title: "طريقة add_range"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يضيف مجموعة من توقيعات البيانات الوصفية."
type: docs
url: /ar/python-net/groupdocs.signature.domain/metadatasignaturecollection/add_range/
is_root: false
weight: 1030
---


## add_range {#signatures}

يضيف مجموعة من توقيعات البيانات الوصفية.

```python
def add_range(self, signatures):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| signatures | `Iterable[MetadataSignature]` | مجموعة التواقيع للإضافة. |

### مثال

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

def sign_docx():
    with Signature("sample.docx") as signature:
        options = MetadataSignOptions()
        signatures = [
            WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
            WordProcessingMetadataSignature("DateCreated", datetime.now()),
            WordProcessingMetadataSignature("DocumentId", 123456),
            WordProcessingMetadataSignature("SignatureId", 123.456),
        ]
        options.signatures.add_range(signatures)
        result = signature.sign("signed.docx", options)
        print(f"Signed with {len(result.succeeded)} metadata signature(s):")
        for item in result.succeeded:
            print(f"  {item.name}")
```

### انظر أيضًا
* class [`MetadataSignatureCollection`](/signature/python-net/groupdocs.signature.domain/metadatasignaturecollection/)
