---
title: "Kelas LoadOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Kelas LoadOptions memungkinkan menentukan opsi tambahan (seperti kata sandi) saat membuka dokumen untuk ditandatangani."
type: docs
url: /id/python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 300
---


## LoadOptions class

Kelas LoadOptions memungkinkan menentukan opsi tambahan (seperti kata sandi) saat membuka dokumen untuk ditandatangani.

Setel atribut `password` ke kata sandi dokumen jika file terenkripsi.

Tipe LoadOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/) | Menginisialisasi instance baru dari kelas LoadOptions. |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#file_type) | Menginisialisasi instance baru dari kelas [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) dengan tipe file yang ditentukan. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type/) | Tipe file yang terkait dengan load options, default ke [`FileType.unknown`](/signature/python-net/groupdocs.signature.domain/filetype/unknown/). |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) | Bendera yang menentukan apakah dokumen memuat sumber daya eksternal. Properti ini sudah usang; gunakan [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) sebagai gantinya, yang memiliki arti sebaliknya. |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password/) | Kata sandi yang digunakan untuk membuka dokumen yang dilindungi dan menyimpan dokumen yang ditandatangani sebagai dilindungi. |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions/) | Izin dokumen PDF seperti mencetak, memodifikasi, dan mengekstrak data. Hanya untuk dokumen PDF. |
| [skip_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) | Flag yang menghentikan dokumen dari memuat sumber daya eksternal. Nilai default adalah True; sumber daya eksternal tidak dimuat kecuali yang cocok dengan [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/). |
| [whitelisted_resources](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) | Daftar fragmen alamat sumber daya eksternal yang dimuat bahkan ketika [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) bernilai true. Nilai default adalah daftar kosong. |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions

load_options = LoadOptions()
load_options.password = "1234567890"
with Signature("protected.pdf", load_options) as signature:
    info = signature.get_document_info()
    print(f"{info.file_type.file_format}, {info.page_count} page(s), {info.size} bytes")
```

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
