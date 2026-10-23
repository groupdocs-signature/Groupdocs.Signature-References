---
title: "Kelas ExportImageSaveOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menunjukkan opsi penyimpanan untuk mengekspor dokumen ke gambar."
type: docs
url: /id/python-net/groupdocs.signature.options/exportimagesaveoptions/
is_root: false
weight: 160
---


## ExportImageSaveOptions class

Menunjukkan opsi penyimpanan untuk mengekspor dokumen ke gambar.

Tipe ExportImageSaveOptions menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/) | Menginisialisasi instance baru dari kelas ExportAsImageSaveOptions dengan nilai default. |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/#file_format) | Menginisialisasi instance baru dari ExportAsImageSaveOptions dengan format file yang ditentukan. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/border/) | Pengaturan batas gambar. Secara default nilai ini tidak diatur. |
| [export_all_pages](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/export_all_pages/) | Bendera untuk mengekspor setiap halaman. |
| [page_columns](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_columns/) | Jumlah kolom untuk gambar yang diekspor. Gunakan properti ini jika Anda perlu menempatkan gambar dalam satu baris. |
| [page_number](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_number/) | Nomor halaman dokumen untuk ekspor (nilai minimum adalah 1). |
| [pages_setup](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/pages_setup/) | Opsi untuk menentukan halaman yang akan ditandatangani. |
| [tiff_multipage](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/tiff_multipage/) | Halaman dokumen ditempatkan pada frame yang berbeda dalam gambar TIFF. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Bendera yang menentukan apakah secara otomatis menambahkan ekstensi ketika tidak ada dalam jalur file output. Nilai default adalah False. (diturunkan dari [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Format file dokumen yang ditandatangani. (diturunkan dari [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Bendera yang menunjukkan apakah menimpa file yang ada dengan file output baru. (diturunkan dari [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Kata sandi yang digunakan untuk melindungi dokumen yang ditandatangani yang disimpan. Tidak didukung untuk dokumen Gambar. (diturunkan dari [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Bendera yang menunjukkan apakah menggunakan kata sandi dari [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) saat menyimpan dokumen yang ditandatangani sebagai terlindungi. Nilai default adalah True. Tidak didukung untuk dokumen Gambar. (diturunkan dari [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
