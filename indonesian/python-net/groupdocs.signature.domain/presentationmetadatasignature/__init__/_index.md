---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi PresentationMetadataSignature dengan nama yang ditentukan dan nilai kosong."
type: docs
url: /id/python-net/groupdocs.signature.domain/presentationmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Menginisialisasi PresentationMetadataSignature dengan nama yang ditentukan dan nilai kosong.

```python
def __init__(self, name):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| name | `str` | Nama Signature Metadata Presentasi. |

## __init__ {#name-value}

Menginisialisasi PresentationMetadataSignature dengan nilai yang telah ditentukan.

```python
def __init__(self, name, value):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| name | `str` | Nama objek tanda tangan metadata. |
| value | `Any` | Nilai tanda tangan metadata. |

### Contoh

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PresentationMetadataSignature

with Signature("sample.ppsx") as signature:
    options = MetadataSignOptions()
    signatures = [
        PresentationMetadataSignature("Author", "Mr. Sherlock Holmes"),
        PresentationMetadataSignature("DateCreated", datetime.now()),
        PresentationMetadataSignature("DocumentId", 123456),
        PresentationMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.ppsx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### Lihat Juga
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
