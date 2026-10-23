---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi opsi verifikasi default untuk tanda tangan barcode."
type: docs
url: /id/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi opsi verifikasi default untuk tanda tangan barcode.

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.signature.options import BarcodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

options = BarcodeVerifyOptions()
options.text = "12345"
options.match_type = TextMatchType.CONTAINS
```

## __init__ {#text}

Menginisialisasi opsi verifikasi default dengan teks verifikasi.

```python
def __init__(self, text):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | `str` | Teks barcode untuk diverifikasi. |

## __init__ {#encode_type}

Menginisialisasi opsi verifikasi default dengan verifikasi tipe barcode.

```python
def __init__(self, encode_type):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| encode_type | `BarcodeType` | Verifikasi tipe barcode. |

## __init__ {#text-encode_type}

Menginisialisasi opsi verifikasi default dengan verifikasi tipe barcode dan teks.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | `str` | Teks barcode untuk diverifikasi. |
| encode_type | `BarcodeType` | Verifikasi tipe barcode. |

### Lihat Juga
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/)
