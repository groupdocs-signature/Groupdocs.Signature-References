---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi tanda tangan metadata PDF dengan nama yang telah ditentukan dan nilai kosong."
type: docs
url: /id/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Menginisialisasi tanda tangan metadata PDF dengan nama yang telah ditentukan dan nilai kosong.

```python
def __init__(self, name):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| name | `str` | Nama tanda tangan metadata PDF. |

## __init__ {#name-value}

Menginisialisasi tanda tangan metadata PDF dengan nilai yang telah ditentukan.

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
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr. Sherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
```

## __init__ {#name-value-tag}

Menginisialisasi tanda tangan metadata PDF dengan nilai yang telah ditentukan.

```python
def __init__(self, name, value, tag):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| name | `str` | Nama objek tanda tangan metadata. |
| value | `Any` | Nilai tanda tangan metadata. |
| tag | `str` | Tag awalan tanda tangan metadata. |

### Contoh

```python
from groupdocs.signature.domain import PdfMetadataSignature

# Buat tanda tangan metadata untuk penulis PDF
author_sig = PdfMetadataSignature("Author", "Mr. Sherlock Holmes")

# Buat tanda tangan metadata untuk tanggal pembuatan
from datetime import datetime
created_sig = PdfMetadataSignature("CreatedOn", datetime.now())

# Buat tanda tangan metadata untuk pengidentifikasi numerik
id_sig = PdfMetadataSignature("DocumentId", 123456)

# Buat tanda tangan metadata untuk nilai floating‑point
float_sig = PdfMetadataSignature("SignatureId", 123.456)
```

### Lihat Juga
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
