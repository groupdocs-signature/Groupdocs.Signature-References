---
title: "Kelas PngSaveOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Opsi penyimpanan PNG untuk dokumen gambar."
type: docs
url: /id/python-net/groupdocs.signature.options/pngsaveoptions/
is_root: false
weight: 400
---


## PngSaveOptions class

Opsi penyimpanan PNG untuk dokumen gambar.

Tipe PngSaveOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pngsaveoptions/__init__/) | Menginisialisasi PngSaveOptions dengan nilai default. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [bit_depth](/signature/python-net/groupdocs.signature.options/pngsaveoptions/bit_depth/) | Kedalaman bit. |
| [color_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/color_type/) | Jenis `PngColorType`. |
| [compression_level](/signature/python-net/groupdocs.signature.options/pngsaveoptions/compression_level/) | Level kompresi gambar png dalam rentang 0-9, di mana 9 adalah kompresi maksimum dan 0 adalah mode penyimpanan. |
| [filter_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/filter_type/) | Jenis filter `PngFilterType` yang digunakan selama proses penyimpanan file PNG. |
| [progressive](/signature/python-net/groupdocs.signature.options/pngsaveoptions/progressive/) | Flag progresif yang menunjukkan apakah PNG disimpan secara progresif. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Bendera yang menentukan apakah secara otomatis menambahkan ekstensi ketika tidak ada dalam jalur file output. Nilai default adalah False. (diturunkan dari [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Format file dokumen yang ditandatangani. (diturunkan dari [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Bendera yang menunjukkan apakah menimpa file yang ada dengan file output baru. (diturunkan dari [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Kata sandi yang digunakan untuk melindungi dokumen yang ditandatangani yang disimpan. Tidak didukung untuk dokumen Gambar. (diturunkan dari [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Bendera yang menunjukkan apakah menggunakan kata sandi dari [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) saat menyimpan dokumen yang ditandatangani sebagai terlindungi. Nilai default adalah True. Tidak didukung untuk dokumen Gambar. (diturunkan dari [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
