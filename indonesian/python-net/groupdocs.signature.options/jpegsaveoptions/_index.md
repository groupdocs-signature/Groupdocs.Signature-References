---
title: "Kelas JpegSaveOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili opsi penyimpanan JPEG untuk dokumen gambar."
type: docs
url: /id/python-net/groupdocs.signature.options/jpegsaveoptions/
is_root: false
weight: 290
---


## JpegSaveOptions class

Mewakili opsi penyimpanan JPEG untuk dokumen gambar.

Tipe JpegSaveOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/__init__/) | Menginisialisasi JpegSaveOptions dengan nilai default. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [bits_per_channel](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/bits_per_channel/) | Jumlah bit per kanal untuk gambar JPEG lossless. Nilai yang didukung adalah dari 2 hingga 8 bit per kanal. |
| [color_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/color_type/) | Tipe warna untuk gambar JPEG. |
| [comment](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/comment/) | Komentar file JPEG. |
| [compression_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/compression_type/) | Tipe kompresi. |
| [quality](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/quality/) | Kualitas gambar. |
| [sample_rounding_mode](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/sample_rounding_mode/) | Mode pembulatan sampel yang digunakan untuk menyesuaikan nilai 8-bit ke nilai n-bit dari `JpegOptions.BitsPerChannel`. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Bendera yang menentukan apakah secara otomatis menambahkan ekstensi ketika tidak ada dalam jalur file output. Nilai default adalah False. (diturunkan dari [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Format file dokumen yang ditandatangani. (diturunkan dari [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Bendera yang menunjukkan apakah menimpa file yang ada dengan file output baru. (diturunkan dari [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Kata sandi yang digunakan untuk melindungi dokumen yang ditandatangani yang disimpan. Tidak didukung untuk dokumen Gambar. (diturunkan dari [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Bendera yang menunjukkan apakah menggunakan kata sandi dari [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) saat menyimpan dokumen yang ditandatangani sebagai terlindungi. Nilai default adalah True. Tidak didukung untuk dokumen Gambar. (diturunkan dari [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
