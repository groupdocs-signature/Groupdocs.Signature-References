---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُنشئ مثيلاً جديدًا من فئة MetadataSignOptions بالقيم الافتراضية."
type: docs
url: /ar/python-net/groupdocs.signature.options/metadatasignoptions/__init__/
is_root: false
weight: 10
---


## __init__

يُنشئ مثيلاً جديدًا من فئة MetadataSignOptions بالقيم الافتراضية.

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    options.signatures.add(
        WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
    )
    result = signature.sign("signed.docx", options)
```

## __init__ {#signatures}

يُنشئ مثيلاً جديدًا من [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) مع البيانات الوصفية.

```python
def __init__(self, signatures):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| signatures | `Iterable[MetadataSignature]` | مجموعة من توقيعات البيانات الوصفية `MetadataSignature`. |

### مثال

```python
from datetime import datetime
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

signatures = [
    WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes"),
    WordProcessingMetadataSignature("DateCreated", datetime.now()),
]

options = MetadataSignOptions(signatures=signatures)
```

### انظر أيضًا
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
