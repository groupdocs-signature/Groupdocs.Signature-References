---
title: "StampLine kelas"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Tentukan properti garis Stempel."
type: docs
url: /id/python-net/groupdocs.signature.domain/stampline/
is_root: false
weight: 680
---


## StampLine class

Tentukan properti garis Stempel.

Tipe StampLine menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/stampline/__init__/) | Menginisialisasi StampLine dengan nilai default. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [background_color](/signature/python-net/groupdocs.signature.domain/stampline/background_color/) | Warna latar belakang tanda tangan. |
| [font](/signature/python-net/groupdocs.signature.domain/stampline/font/) | Font teks baris stempel. |
| [height](/signature/python-net/groupdocs.signature.domain/stampline/height/) | Tinggi baris pada stempel. |
| [inner_border](/signature/python-net/groupdocs.signature.domain/stampline/inner_border/) | Batas internal baris stempel. |
| [outer_border](/signature/python-net/groupdocs.signature.domain/stampline/outer_border/) | Batas luar baris cap. |
| [text](/signature/python-net/groupdocs.signature.domain/stampline/text/) | Teks baris cap. |
| [text_bottom_intent](/signature/python-net/groupdocs.signature.domain/stampline/text_bottom_intent/) | Niat bawah teks. |
| [text_color](/signature/python-net/groupdocs.signature.domain/stampline/text_color/) | Warna teks tanda tangan. |
| [text_repeat_type](/signature/python-net/groupdocs.signature.domain/stampline/text_repeat_type/) | Tipe pengulangan teks. |
| [visible](/signature/python-net/groupdocs.signature.domain/stampline/visible/) | Visibilitas baris cap. |

### Contoh

```python
from groupdocs.signature.domain import StampLine
from groupdocs.pydrawing import Color

# Buat baris cap
line = StampLine()
line.text = " * European Union *"
line.font.size = 12
line.height = 22
line.text_bottom_intent = 6
line.text_color = Color.white_smoke
line.background_color = Color.dark_slate_blue
```

### Lihat Juga
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
