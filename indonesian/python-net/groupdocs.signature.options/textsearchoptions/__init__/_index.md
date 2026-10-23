---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi instance baru dari kelas TextSearchOptions dengan nilai default."
type: docs
url: /id/python-net/groupdocs.signature.options/textsearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari kelas TextSearchOptions dengan nilai default.

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    # Cari tanda tangan teks menggunakan opsi default
    result = signature.search([TextSearchOptions()])
    for text_signature in result.signatures:
        print(f"Found text signature: {text_signature.text}")
```

## __init__ {#text}

Menginisialisasi instance baru dari kelas TextSearchOptions dengan nilai teks.

```python
def __init__(self, text):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | `str` | Teks dari tanda tangan teks. |

### Lihat Juga
* class [`TextSearchOptions`](/signature/python-net/groupdocs.signature.options/textsearchoptions/)
