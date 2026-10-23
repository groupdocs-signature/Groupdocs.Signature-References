---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi Image Metadata Signature dengan pengenal dan nilai yang ditentukan."
type: docs
url: /id/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#id-value}

Menginisialisasi Image Metadata Signature dengan pengenal dan nilai yang ditentukan.

```python
def __init__(self, id, value):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| id | `System.UInt16` | Pengidentifikasi unik untuk Tanda Tangan Metadata Gambar. Lihat referensi untuk spesifikasi tag EXIF untuk nilai id yang mungkin. |
| value | `Any` | Nilai metadata. |

### Contoh

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import ImageMetadataSignature

with Signature("sample.png") as signature:
    options = MetadataSignOptions()
    metadata_id = 41996
    options.add(ImageMetadataSignature(metadata_id, "Mr. Sherlock Holmes"))  # text
    options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
    options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # integer
    options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # float
    result = signature.sign("signed.png", options)
```

### Lihat Juga
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
