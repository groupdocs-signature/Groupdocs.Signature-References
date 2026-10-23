---
title: "metode add"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Tambahkan instance MetadataSignature yang ada ke koleksi."
type: docs
url: /id/python-net/groupdocs.signature.options/metadatasignoptions/add/
is_root: false
weight: 1010
---


## add {#metadata_signature}

Tambahkan instance MetadataSignature yang ada ke koleksi.

```python
def add(self, metadata_signature):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| metadata_signature | `MetadataSignature` | Instansi MetadataSignature yang sudah ada untuk ditambahkan. |

**Returns:** The MetadataSignOptions instance.

### Contoh

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

### Lihat Juga
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
