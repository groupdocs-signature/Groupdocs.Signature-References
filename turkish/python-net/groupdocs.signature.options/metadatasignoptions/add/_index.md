---
title: "add yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Mevcut MetadataSignature örneğini koleksiyona ekle."
type: docs
url: /tr/python-net/groupdocs.signature.options/metadatasignoptions/add/
is_root: false
weight: 1010
---


## add {#metadata_signature}

Mevcut MetadataSignature örneğini koleksiyona ekle.

```python
def add(self, metadata_signature):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| metadata_signature | `MetadataSignature` | Eklenecek mevcut MetadataSignature örneği. |

**Returns:** The MetadataSignOptions instance.

### Örnek

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

### Ayrıca Bakınız
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
