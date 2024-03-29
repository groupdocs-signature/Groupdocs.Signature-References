---
title: ExportImageSaveOptions
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Menyimpan opsi untuk mengekspor dokumen ke gambar.
type: docs
weight: 1360
url: /id/net/groupdocs.signature.options/exportimagesaveoptions/
---
## ExportImageSaveOptions class

Menyimpan opsi untuk mengekspor dokumen ke gambar.

```csharp
public class ExportImageSaveOptions : ImageSaveOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [ExportImageSaveOptions](exportimagesaveoptions#constructor)() | Menginisialisasi instance baru kelas ExportAsImageSaveOptions dengan nilai default. |
| [ExportImageSaveOptions](exportimagesaveoptions#constructor_1)(ImageSaveFileFormat) | Menginisialisasi instance baru dari kelas ExportAsImageSaveOptions dengan format file yang ditentukan. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Mendapat atau menyetel bendera untuk menambahkan ekstensi secara otomatis ketika tidak ada di jalur file keluaran Nilai default adalah false. |
| [Border](../../groupdocs.signature.options/exportimagesaveoptions/border) { get; set; } | Mendapat atau mengatur pengaturan batas gambar. Secara default nilai ini tidak disetel. |
| [ExportAllPages](../../groupdocs.signature.options/exportimagesaveoptions/exportallpages) { get; set; } | Tandai untuk mengekspor setiap halaman. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Mendapat atau mengatur format file dari dokumen yang ditandatangani. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Mendapat atau mengatur apakah akan menimpa file yang ada dengan file keluaran baru. Jika tidak, file baru akan dibuat dengan angka sebagai akhiran. Secara default nilai ini disetel ke true yang berarti file akan ditimpa. |
| [PageColumns](../../groupdocs.signature.options/exportimagesaveoptions/pagecolumns) { get; set; } | Mendapat atau menetapkan jumlah kolom untuk gambar yang diekspor. Gunakan properti ini jika Anda perlu meletakkan gambar dalam satu baris. |
| [PageNumber](../../groupdocs.signature.options/exportimagesaveoptions/pagenumber) { get; set; } | Mendapat atau menetapkan nomor halaman dokumen untuk ekspor. Nilai minimal adalah 1. |
| [PagesSetup](../../groupdocs.signature.options/exportimagesaveoptions/pagessetup) { get; set; } | Opsi untuk menentukan halaman yang akan ditandatangani. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Mendapatkan atau menyetel kata sandi untuk menyimpan dokumen yang ditandatangani dengan proteksi kata sandi. Properti ini tidak didukung untuk dokumen Gambar. |
| [TiffMultipage](../../groupdocs.signature.options/exportimagesaveoptions/tiffmultipage) { get; set; } | Letakkan halaman dokumen pada bingkai yang berbeda di gambar Tiff. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Mendapat atau menyetel apakah akan menggunakan kata sandi dari LoadOptions untuk menyimpan dokumen yang ditandatangani sebagai dilindungi. Nilai default adalah true. Properti ini tidak didukung untuk dokumen Gambar. |

### Lihat juga

* class [ImageSaveOptions](../imagesaveoptions)
* ruang nama [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* perakitan [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
