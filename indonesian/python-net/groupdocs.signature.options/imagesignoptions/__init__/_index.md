---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi instance baru dari kelas ImageSignOptions dengan nilai default."
type: docs
url: /id/python-net/groupdocs.signature.options/imagesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari kelas ImageSignOptions dengan nilai default.

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.signature.options import ImageSignOptions

# Buat opsi tanda tangan gambar menggunakan jalur file gambar
options = ImageSignOptions("signature.jpg")
```

## __init__ {#image_file_path}

Menginisialisasi ImageSignOptions dengan file gambar.

```python
def __init__(self, image_file_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_file_path | `str` | Jalur file gambar. |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    options = ImageSignOptions("signature.jpg")
    # konfigurasikan opsi tambahan di sini, misalnya posisi, ukuran, dll.
    result = signature.sign("signed_image.pdf", options)
    print(f"Signed with {len(result.succeeded)} image signature(s)")
```

## __init__ {#image_stream}

Menginisialisasi instance baru ImageSignOptions dengan aliran gambar.

```python
def __init__(self, image_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | Aliran gambar. |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    with open("signature.jpg", "rb") as image_stream:
        options = ImageSignOptions(image_stream)
        options.left = 100
        options.top = 400
        result = signature.sign("signed_image_stream.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Lihat Juga
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)
