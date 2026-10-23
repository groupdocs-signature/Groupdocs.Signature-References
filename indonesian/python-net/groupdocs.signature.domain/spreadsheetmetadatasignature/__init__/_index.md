---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi Spreadsheet Metadata Signature dengan nama yang telah ditentukan dan nilai kosong."
type: docs
url: /id/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Menginisialisasi Spreadsheet Metadata Signature dengan nama yang telah ditentukan dan nilai kosong.

```python
def __init__(self, name):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| name | `str` | Nama Spreadsheet Metadata Signature. |

## __init__ {#name-value}

Menginisialisasi Spreadsheet Metadata Signature dengan nilai-nilai yang telah ditentukan.

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
from groupdocs.signature.domain import SpreadsheetMetadataSignature

# Buat tanda tangan metadata untuk spreadsheet
author_sig = SpreadsheetMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = SpreadsheetMetadataSignature("DateCreated", datetime.now())
id_sig = SpreadsheetMetadataSignature("DocumentId", 123456)
float_sig = SpreadsheetMetadataSignature("SignatureId", 123.456)
```

### Lihat Juga
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
