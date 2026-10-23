---
title: "Kelas Padding"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili informasi padding atau margin yang terkait dengan elemen."
type: docs
url: /id/python-net/groupdocs.signature.domain/padding/
is_root: false
weight: 400
---


## Padding class

Mewakili informasi padding atau margin yang terkait dengan elemen.

Tipe Padding menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/) | Menginisialisasi instance baru dari kelas Padding dengan nilai nol. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#all) | Menginisialisasi instance baru dari kelas Padding menggunakan ukuran padding yang diberikan untuk semua sisi. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#left-right-top-bottom) | Menginisialisasi instance baru dari kelas Padding menggunakan ukuran padding yang diberikan. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/padding/clone/) | Mendapatkan salinan objek ini. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [all](/signature/python-net/groupdocs.signature.domain/padding/all/) | Nilai padding untuk semua sisi. |
| [bottom](/signature/python-net/groupdocs.signature.domain/padding/bottom/) | Nilai padding untuk sisi bawah. |
| [horizontal](/signature/python-net/groupdocs.signature.domain/padding/horizontal/) | Padding gabungan untuk sisi kanan dan kiri. |
| [left](/signature/python-net/groupdocs.signature.domain/padding/left/) | Nilai padding untuk sisi kiri. |
| [right](/signature/python-net/groupdocs.signature.domain/padding/right/) | Nilai padding untuk sisi kanan. |
| [top](/signature/python-net/groupdocs.signature.domain/padding/top/) | Nilai padding untuk sisi atas. |
| [vertical](/signature/python-net/groupdocs.signature.domain/padding/vertical/) | Padding gabungan untuk sisi atas dan bawah. |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [EMPTY](/signature/python-net/groupdocs.signature.domain/padding/empty/) | Menyediakan objek Padding tanpa padding. |

### Contoh

```python
from groupdocs.signature.domain import Padding

# Padding seragam sebesar 5 unit pada semua sisi
uniform = Padding(5)

# Padding khusus pada kanan dan bawah
custom = Padding(right=40, bottom=60)
```

### Guides
Panduan tugas yang menggunakan `Padding`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Lihat Juga
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
