---
title: "Kelas ImageSignature"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Kelas ini berisi properti tanda tangan gambar."
type: docs
url: /id/python-net/groupdocs.signature.domain/imagesignature/
is_root: false
weight: 340
---


## ImageSignature class

Kelas ini berisi properti tanda tangan gambar.

Tipe ImageSignature menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagesignature/__init__/#signature_id) | Menginisialisasi objek ImageSignature dengan pengidentifikasi tanda tangan unik yang diperoleh dari metode Sign atau Search pada kelas [`GroupDocs.Signature`](/signature/python-net/groupdocs.signature/signature/). |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagesignature/clone/) | Klon instance ImageSignature. |
| [equals](/signature/python-net/groupdocs.signature.domain/imagesignature/equals/#obj) | Menentukan apakah tanda tangan yang ditentukan sama dengan instance ini. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagesignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagesignature/get_hash_code/) | Mengembalikan kode hash untuk tanda tangan. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/imagesignature/content/) | Data gambar biner tanda tangan, dalam format yang ditentukan oleh [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). |
| [format](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) | Format gambar tanda tangan. |
| [size](/signature/python-net/groupdocs.signature.domain/imagesignature/size/) | Ukuran dalam byte gambar tanda tangan. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Tanggal pembuatan tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Bendera yang menunjukkan apakah tanda tangan ini telah dihapus dari dokumen. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Tinggi tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Bendera yang menunjukkan apakah komponen ini mewakili tanda tangan (`True`) atau konten dokumen (`False`). (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Posisi kiri tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Tanggal modifikasi tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Nomor halaman tempat tanda tangan ditemukan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Pengidentifikasi unik tanda tangan, digunakan untuk memodifikasi tanda tangan dalam dokumen melalui operasi pembaruan atau penghapusan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Jenis tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Posisi atas tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Lebar tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([ImageSearchOptions()])
    for image in result.signatures:
        print(
            f"Page {image.page_number}: {image.size} bytes at ({image.left}, {image.top}), "
            f"size {image.width}x{image.height}"
        )
```

### Lihat Juga
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
