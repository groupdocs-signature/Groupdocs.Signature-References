---
title: "Kelas ImageSearchOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili opsi pencarian untuk tanda tangan Gambar."
type: docs
url: /id/python-net/groupdocs.signature.options/imagesearchoptions/
is_root: false
weight: 240
---


## ImageSearchOptions class

Mewakili opsi pencarian untuk tanda tangan Gambar.

Pelajari lebih lanjut:
- Basic usage of search for Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures
- Advanced usage of settings of search for Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures

Tipe ImageSearchOptions menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesearchoptions/__init__/) | Menginisialisasi instance baru dari kelas ImageSearchOptions dengan nilai default. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [max_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/max_content_size/) | Ukuran maksimum gambar untuk kriteria pencarian, dalam byte. |
| [min_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/min_content_size/) | Ukuran minimal data gambar, dalam byte, yang akan dipertimbangkan selama pencarian. Nilai non‑nol menentukan ukuran minimal; defaultnya adalah nol, yang tidak memengaruhi hasil pencarian. |
| [return_content](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content/) | Bendera yang menentukan apakah konten gambar dari tanda tangan dikembalikan. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/) | Tipe file dari konten gambar yang dikembalikan ketika properti `return_content` diaktifkan. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Bendera yang menunjukkan apakah akan mencari pada setiap halaman dokumen. Secara default nilai ini adalah True. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Nomor halaman dokumen untuk pencarian (opsional). (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Opsi untuk menentukan halaman untuk pencarian tanda tangan. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Bendera yang menunjukkan apakah mengembalikan posisi bentuk dalam tata letak dokumen. Hanya tersedia untuk dokumen Word. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Bendera untuk mengembalikan hanya tanda tangan yang ditandai sebagai `IsSignature`. Secara default nilai adalah `False`, yang menunjukkan bahwa semua tanda tangan yang cocok dengan kriteria yang ditentukan dikembalikan. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSearchOptions

def extract_image_signatures():
    with Signature("signed.pdf") as signature:
        options = ImageSearchOptions()
        options.all_pages = False          # search the first page only
        options.page_number = 1
        options.min_content_size = 1024   # skip images smaller than 1 KB
        options.return_content = True
        options.return_content_type = FileType.PNG

        result = signature.search([options])
        for i, image in enumerate(result.signatures, start=1):
            file_name = f"image_signature_{i}.png"
            with open(file_name, "wb") as out:
                out.write(image.content)
```

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
