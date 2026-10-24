---
title: "метод add"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Добавить существующий экземпляр MetadataSignature в коллекцию."
type: docs
url: /ru/python-net/groupdocs.signature.options/metadatasignoptions/add/
is_root: false
weight: 1010
---


## add {#metadata_signature}

Добавить существующий экземпляр MetadataSignature в коллекцию.

```python
def add(self, metadata_signature):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| metadata_signature | `MetadataSignature` | Существующий экземпляр MetadataSignature, который будет добавлен. |

**Returns:** The MetadataSignOptions instance.

### Пример

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr.Scherlock Holmes"))
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s)")
```

### См. также
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
