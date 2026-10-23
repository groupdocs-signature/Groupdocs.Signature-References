---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi instance baru dari TextVerifyOptions dengan nilai default."
type: docs
url: /id/python-net/groupdocs.signature.options/textverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari TextVerifyOptions dengan nilai default.

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## __init__ {#text}

Menginisialisasi instance baru dari TextVerifyOptions dengan teks verifikasi.

```python
def __init__(self, text):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | `str` | Teks yang akan diverifikasi. |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

## __init__ {#text-implementation}

Menginisialisasi instance baru TextVerifyOptions dengan teks yang akan diverifikasi dan tipe implementasi tanda tangan.

```python
def __init__(self, text, implementation):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | `str` | Teks yang akan diverifikasi. |
| implementation | `TextSignatureImplementation` | Tipe implementasi tanda tangan. |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

### Lihat Juga
* class [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)
