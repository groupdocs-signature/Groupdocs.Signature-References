---
title: "Kelas SaveOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menentukan opsi tambahan (seperti kata sandi) saat menyimpan dokumen untuk ditandatangani."
type: docs
url: /id/python-net/groupdocs.signature.options/saveoptions/
is_root: false
weight: 520
---


## SaveOptions class

Menentukan opsi tambahan (seperti kata sandi) saat menyimpan dokumen untuk ditandatangani.

Tipe SaveOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/) | Menginisialisasi instance baru dari kelas SaveOptions dengan nilai default. |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/#overwrite_existing_file) | Menginisialisasi instance baru dari kelas SaveOptions dengan tipe output yang ditentukan dan flag timpa. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Flag yang menentukan apakah secara otomatis menambahkan ekstensi ketika tidak ada dalam jalur file output. Nilai default adalah False. |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Flag yang menunjukkan apakah akan menimpa file yang ada dengan file output baru. |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Kata sandi yang digunakan untuk melindungi dokumen yang ditandatangani yang disimpan. Tidak didukung untuk dokumen Gambar. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Bendera yang menunjukkan apakah akan menggunakan kata sandi dari [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) saat menyimpan dokumen yang ditandatangani sebagai terlindungi. Nilai default adalah True. Tidak didukung untuk dokumen Gambar. |

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
