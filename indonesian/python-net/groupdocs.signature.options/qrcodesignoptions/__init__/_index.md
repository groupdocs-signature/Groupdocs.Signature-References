---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi instance baru dari kelas QRCodeSignOptions dengan nilai default."
type: docs
url: /id/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari kelas QRCodeSignOptions dengan nilai default.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Menginisialisasi instance opsi tanda tangan kode QR dengan teks yang ditentukan.

```python
def __init__(self, text):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | `str` | Teks tanda tangan. |

### Contoh

```python
from groupdocs.signature.options import QrCodeSignOptions

# Buat opsi tanda tangan kode QR dengan teks yang diinginkan
options = QrCodeSignOptions("Approved by John Smith")
```

## __init__ {#text-encode_type}

Menginisialisasi instance baru dari kelas QrCodeSignOptions dengan teks.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | `str` | Teks QRCode. |
| encode_type | `QrCodeType` | Tipe enkode QRCode. |

### Contoh

```python
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeSignOptions(
    "https://www.example.com/verify-document",
    QrCodeTypes.QR
)
```

### Lihat Juga
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
