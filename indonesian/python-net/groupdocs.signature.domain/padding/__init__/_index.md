---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi instance baru dari kelas Padding dengan nilai nol."
type: docs
url: /id/python-net/groupdocs.signature.domain/padding/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari kelas Padding dengan nilai nol.

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.signature.domain import Padding

# Buat objek padding dengan nilai default (nol)
default_padding = Padding()
```

## __init__ {#all}

Menginisialisasi instance baru dari kelas Padding menggunakan ukuran padding yang diberikan untuk semua sisi.

```python
def __init__(self, all):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| all | `int` | Jumlah satuan ukuran yang akan digunakan untuk padding pada semua tepi. |

### Contoh

```python
# Padding seragam sebesar 5 unit pada semua sisi
margin = Padding(5)
```

## __init__ {#left-right-top-bottom}

Menginisialisasi instance baru dari kelas Padding menggunakan ukuran padding yang diberikan.

```python
def __init__(self, left, right, top, bottom):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| left | `int` | Ukuran padding kiri. |
| right | `int` | Ukuran padding kanan. |
| top | `int` | Ukuran padding atas. |
| bottom | `int` | Ukuran padding bawah. |

### Contoh

```python
from groupdocs.signature.domain import Padding

# Buat padding dengan offset kanan dan bawah
margin = Padding(right=40, bottom=60)
```

### Lihat Juga
* class [`Padding`](/signature/python-net/groupdocs.signature.domain/padding/)
