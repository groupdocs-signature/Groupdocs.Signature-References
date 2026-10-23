---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi WordProcessingMetadataSignature dengan nama yang ditentukan dan nilai kosong."
type: docs
url: /id/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Menginisialisasi WordProcessingMetadataSignature dengan nama yang ditentukan dan nilai kosong.

```python
def __init__(self, name):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| name | `str` | Nama WordProcessing Metadata Signature. |

### Contoh

```python
from datetime import datetime
from groupdocs.signature.domain import WordProcessingMetadataSignature

# Buat tanda tangan metadata dengan nama dan nilai
author_sig = WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = WordProcessingMetadataSignature("DateCreated", datetime.now())
id_sig = WordProcessingMetadataSignature("DocumentId", 123456)
float_sig = WordProcessingMetadataSignature("SignatureId", 123.456)
```

## __init__ {#name-value}

Menginisialisasi tanda tangan metadata WordProcessing dengan nilai-nilai yang telah ditentukan.

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
from groupdocs.signature.domain import WordProcessingMetadataSignature

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

### Lihat Juga
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
