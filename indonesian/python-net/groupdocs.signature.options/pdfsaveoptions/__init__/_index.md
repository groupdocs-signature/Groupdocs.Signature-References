---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi instance baru dari PdfSaveOptions dengan nilai default."
type: docs
url: /id/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari PdfSaveOptions dengan nilai default.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

Menginisialisasi instance baru dari PdfSaveOptions dengan format file output yang ditentukan.

```python
def __init__(self, file_format):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Tipe file output `PdfSaveFileFormat`. |

## __init__ {#overwrite_existing_file}

Menginisialisasi instance baru dari PdfSaveOptions dengan bendera timpa.

```python
def __init__(self, overwrite_existing_file):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| overwrite_existing_file | `bool` | Flag apakah menimpa file yang ditandatangani dengan file yang sama. |

## __init__ {#file_format-overwrite_existing_file}

Menginisialisasi instance baru dari PdfSaveOptions dengan format file output yang ditentukan dan bendera timpa.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Tipe file output. |
| overwrite_existing_file | `bool` | Flag apakah menimpa file yang ditandatangani dengan file yang sama. |

### Contoh

```python
from groupdocs.signature.options import PdfSaveOptions
from groupdocs.signature.domain import PdfSaveFileFormat

# Buat opsi penyimpanan dengan format PDF dan izinkan menimpa file yang ada
save_options = PdfSaveOptions(fileFormat=PdfSaveFileFormat.PDF, overwriteExistingFile=True)
```

### Lihat Juga
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/)
