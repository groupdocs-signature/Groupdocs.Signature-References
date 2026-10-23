---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi opsi verifikasi untuk tanda tangan QR-Code."
type: docs
url: /id/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi opsi verifikasi untuk tanda tangan QR-Code.

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions

with Signature("signed.pdf") as signature:
    options = QrCodeVerifyOptions()
    options.text = "John"
    result = signature.verify(options)
    print(f"Verified: {result.is_valid}")
```

## __init__ {#text}

Menginisialisasi opsi verifikasi untuk tanda tangan QR-Code dengan teks QR-code yang ditentukan.

```python
def __init__(self, text):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | `str` | Teks QR-code untuk diverifikasi. |

### Contoh

```python
from groupdocs.signature.options import QrCodeVerifyOptions

# Buat opsi dan atur teks QR-code untuk diverifikasi
options = QrCodeVerifyOptions()
options.text = "Approved by John Smith"
```

## __init__ {#text-encode_type}

Menginisialisasi opsi verifikasi untuk tanda tangan QR-Code dengan teks dan tipe enkode QR-Code untuk diverifikasi.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | `str` | Teks yang akan diverifikasi. |
| encode_type | `QrCodeType` | Jenis enkoding. |

### Contoh

```python
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeVerifyOptions(text="John Smith", encode_type=QrCodeTypes.QR)
```

### Lihat Juga
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/)
