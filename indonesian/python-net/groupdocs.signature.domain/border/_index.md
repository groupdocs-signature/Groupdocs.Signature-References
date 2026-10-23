---
title: "Kelas Border"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili tampilan batas."
type: docs
url: /id/python-net/groupdocs.signature.domain/border/
is_root: false
weight: 60
---


## Border class

Mewakili tampilan batas.

Tipe Border menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/border/__init__/) |  |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/border/clone/) | Mengimplementasikan antarmuka IClonable. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [color](/signature/python-net/groupdocs.signature.domain/border/color/) | Warna batas tanda tangan. |
| [dash_style](/signature/python-net/groupdocs.signature.domain/border/dash_style/) | Gaya batas tanda tangan. |
| [transparency](/signature/python-net/groupdocs.signature.domain/border/transparency/) | Transparansi batas tanda tangan, berkisar dari 0,0 (tidak tembus) hingga 1,0 (tembus), default 0 (tidak tembus). |
| [visible](/signature/python-net/groupdocs.signature.domain/border/visible/) | Visibilitas batas. |
| [weight](/signature/python-net/groupdocs.signature.domain/border/weight/) | Ketebalan batas tanda tangan. |

### Contoh

```python
from groupdocs.signature.domain import Border, DashStyle
from groupdocs.pydrawing import Color

border = Border()
border.color = Color.dark_green
border.dash_style = DashStyle.DASH
border.weight = 2
border.visible = True
```

### Guides
Panduan tugas yang menggunakan `Border`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)

### Lihat Juga
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
