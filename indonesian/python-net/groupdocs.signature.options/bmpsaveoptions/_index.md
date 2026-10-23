---
title: "Kelas BmpSaveOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menunjukkan opsi penyimpanan BMP untuk dokumen gambar."
type: docs
url: /id/python-net/groupdocs.signature.options/bmpsaveoptions/
is_root: false
weight: 50
---


## BmpSaveOptions class

Menunjukkan opsi penyimpanan BMP untuk dokumen gambar.

Tipe BmpSaveOptions menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/__init__/) | Menginisialisasi BmpSaveOptions dengan nilai default. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [bits_per_pixel](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/bits_per_pixel/) | Jumlah bit per piksel gambar. |
| [compression](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/compression/) | Kompresi. Lihat `BitmapCompression`. |
| [horizontal_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/horizontal_resolution/) | Resolusi horizontal. Perhatikan bahwa karena pembulatan, resolusi yang dihasilkan mungkin sedikit berbeda dari nilai yang ditetapkan. |
| [vertical_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/vertical_resolution/) | Resolusi vertikal; perhatikan bahwa karena pembulatan, resolusi yang dihasilkan mungkin sedikit berbeda dari nilai yang ditetapkan. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Bendera yang menentukan apakah secara otomatis menambahkan ekstensi ketika tidak ada dalam jalur file output. Nilai default adalah False. (diturunkan dari [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Format file dokumen yang ditandatangani. (diturunkan dari [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Bendera yang menunjukkan apakah menimpa file yang ada dengan file output baru. (diturunkan dari [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Kata sandi yang digunakan untuk melindungi dokumen yang ditandatangani yang disimpan. Tidak didukung untuk dokumen Gambar. (diturunkan dari [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Bendera yang menunjukkan apakah menggunakan kata sandi dari [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) saat menyimpan dokumen yang ditandatangani sebagai terlindungi. Nilai default adalah True. Tidak didukung untuk dokumen Gambar. (diturunkan dari [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
