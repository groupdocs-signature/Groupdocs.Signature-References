---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi instance baru dari kelas MetadataSignOptions dengan nilai default."
type: docs
url: /id/python-net/groupdocs.signature.options/metadatasignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari kelas MetadataSignOptions dengan nilai default.

```python
def __init__(self):
    ...
```

### Contoh

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

Menginisialisasi instance baru dari [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) dengan metadata.

```python
def __init__(self, signatures):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| signatures | `Iterable[MetadataSignature]` | Koleksi tanda tangan metadata `MetadataSignature`. |

### Contoh

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

### Lihat Juga
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
