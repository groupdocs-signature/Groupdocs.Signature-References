---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi sebuah instance baru dari kelas QRCodeSearchOptions dengan nilai default."
type: docs
url: /id/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi sebuah instance baru dari kelas QRCodeSearchOptions dengan nilai default.

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

## __init__ {#encode_type}

Menginisialisasi sebuah instance baru dari kelas QRCodeSearchOptions dengan nilai tipe enkode.

```python
def __init__(self, encode_type):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| encode_type | `QrCodeType` | Menentukan jenis enkode QR-Code. |

## __init__ {#encode_type-text}

Menginisialisasi sebuah instance baru dari kelas QRCodeSearchOptions dengan tipe enkode dan nilai teks.

```python
def __init__(self, encode_type, text):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| encode_type | `QrCodeType` | Menentukan jenis enkode QR-Code. |
| text | `str` | Atur teks tanda tangan QR-Code. |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

### Lihat Juga
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
