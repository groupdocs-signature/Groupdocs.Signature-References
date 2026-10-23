---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan nilai default."
type: docs
url: /id/python-net/groupdocs.signature.options/barcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan nilai default.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan teks.

```python
def __init__(self, text):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | `str` | Teks Barcode. |

### Contoh

```python
from groupdocs.signature.options import BarcodeSignOptions

# Buat opsi tanda tangan barcode dengan teks yang diinginkan
options = BarcodeSignOptions("JohnSmith")
```

## __init__ {#text-encode_type}

Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan teks.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | `str` | Teks Barcode. |
| encode_type | `BarcodeType` | Tipe enkode Barcode. |

### Contoh

```python
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

# Buat opsi tanda tangan barcode dengan teks dan tipe
options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
```

### Lihat Juga
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
