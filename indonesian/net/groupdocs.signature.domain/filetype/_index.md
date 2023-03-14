---
title: FileType
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Mewakili jenis file.
type: docs
weight: 450
url: /id/net/groupdocs.signature.domain/filetype/
---
## FileType class

Mewakili jenis file.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | Akhiran nama file (termasuk titik ".") misalnya ".doc". |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | Nama jenis file misalnya "Dokumen Microsoft Word". |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | Memetakan ekstensi file ke jenis file. |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | Menentukan apakah arus[`FileType`](../filetype)adalah sama dengan yang ditentukan[`FileType`](../filetype) objek. |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | Menentukan apakah arus[`FileType`](../filetype) sama dengan objek yang ditentukan. |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | Mengembalikan kode hash untuk saat ini[`FileType`](../filetype) objek. |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | Mengembalikan string yang mewakili objek saat ini. |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | Mengambil jenis file yang didukung |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | Menentukan apakah dua[`FileType`](../filetype) objeknya sama. |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | Menentukan apakah dua[`FileType`](../filetype) objek tidak sama. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | File Gambar Bitmap (.bmp) digunakan untuk menyimpan gambar digital bitmap. Gambar-gambar ini tidak tergantung pada adaptor grafis dan disebut juga format file device independent bitmap (DIB). Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/bmp) . |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) adalah file gambar gambar vektor yang dibuat secara asli dengan CorelDRAW untuk menyimpan gambar digital yang disandikan dan dikompresi. File gambar seperti itu berisi teks, garis, bentuk, gambar, warna, dan efek untuk representasi vektor dari konten gambar. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/cdr) . |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | Metafile Grafik Komputer (.cgm) adalah format metafile standar internasional yang bebas platform dan independen untuk menyimpan dan bertukar grafik vektor (2D), grafik raster, dan teks. CGM menggunakan pendekatan berorientasi objek dan banyak ketentuan fungsi untuk produksi gambar. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/page-description-language/cgm) . |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | CorelDRAW Metafile Exchange Image File (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | File Nilai yang Dipisahkan Koma (.csv) mewakili file teks biasa yang berisi rekaman data dengan nilai yang dipisahkan koma. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | DICOM Image (.dcm) merupakan citra digital yang menyimpan informasi medis pasien seperti MRI, CT scan dan USG. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/dcm) . |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | Gambar DjVu (.djvu) adalah format file grafik yang ditujukan untuk dokumen dan buku yang dipindai terutama yang berisi kombinasi teks, gambar, gambar, dan foto. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/djvu) . |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Dokumen Microsoft Word (.doc) mewakili dokumen yang dihasilkan oleh Microsoft Word atau dokumen pengolah kata lainnya dalam format file biner. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm) adalah dokumen yang dibuat Microsoft Word 2007 atau lebih tinggi dengan kemampuan untuk menjalankan makro. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) adalah format terkenal untuk dokumen Microsoft Word. Diperkenalkan dari tahun 2007 dengan dirilisnya Microsoft Office 2007, struktur format Dokumen baru ini diubah dari biner biasa menjadi kombinasi file XML dan biner. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Word Document Template (.dot) adalah file template yang dibuat oleh Microsoft Word untuk memiliki pengaturan yang telah diformat sebelumnya untuk membuat file DOC atau DOCX lebih lanjut. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) mewakili file template yang dibuat dengan Microsoft Word 2007 atau lebih tinggi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Word Open XML Document Template (.dotx) adalah file template yang dibuat oleh Microsoft Word untuk memiliki pengaturan yang telah diformat sebelumnya untuk pembuatan file DOCX lebih lanjut. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | Metafile Windows yang Disempurnakan (.emf) mewakili gambar grafis perangkat secara mandiri. File-meta EMF terdiri dari catatan panjang variabel dalam urutan kronologis yang dapat merender gambar yang disimpan setelah diuraikan pada perangkat keluaran apa pun. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/emf) . |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | Encapsulated PostScript File (.eps) mendeskripsikan program bahasa Encapsulated PostScript yang mendeskripsikan tampilan halaman tunggal. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/page-description-language/eps) . |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | Graphical Interchange Format File (.gif) adalah jenis gambar yang sangat terkompresi. Untuk setiap gambar, GIF biasanya mengizinkan hingga 8 bit per piksel dan hingga 256 warna diperbolehkan di seluruh gambar. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/gif) . |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | Gambar JPEG (.jpeg) adalah jenis format gambar yang disimpan menggunakan metode kompresi lossy. Gambar keluaran, sebagai hasil kompresi, merupakan trade-off antara ukuran penyimpanan dan kualitas gambar. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | JPEG Image (.jpg) adalah jenis format gambar yang disimpan dengan menggunakan metode kompresi lossy. Gambar keluaran, sebagai hasil kompresi, merupakan trade-off antara ukuran penyimpanan dan kualitas gambar. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | OpenDocument Graphic File (.odg) digunakan oleh aplikasi Draw Apache OpenOffice untuk menyimpan elemen gambar sebagai gambar vektor. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/odg) . |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | OpenDocument Presentation (.odp) mewakili format file presentasi yang digunakan oleh OpenOffice.org dalam standar OASISOpen. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) adalah singkatan dari format Dokumen OpenDocument Spreadsheet yang dapat diedit oleh pengguna. Data disimpan di dalam file ODF ke dalam baris dan kolom. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | OpenDocument Text Document (.odt) adalah jenis dokumen yang dibuat dengan aplikasi pengolah kata yang berbasis format OpenDocument Text File. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | Template Presentasi OpenDocument (.otp) mewakili file template presentasi yang dibuat oleh aplikasi dalam format standar OpenDocument OASIS. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | Templat Spreadsheet OpenDocument (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | Templat Dokumen OpenDocument (.ott) mewakili dokumen templat yang dibuat oleh aplikasi sesuai dengan format standar OpenDocument OASIS. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | Dokumen Bahasa Perintah Printer (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | File Format Dokumen Portabel (.pdf) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan dari format file ini adalah untuk memperkenalkan standar representasi dokumen dan bahan referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras maupun Sistem Operasi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/view/pdf) . |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | Scalable Vector Graphics File (.svg) adalah file Grafik Vektor Skalar yang menggunakan format teks berbasis XML untuk mendeskripsikan tampilan gambar. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | Portable Network Graphic (.png) adalah jenis format file gambar raster yang menggunakan kompresi lossless. Format file ini dibuat sebagai pengganti Graphics Interchange Format (GIF) dan tidak memiliki batasan hak cipta. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/png) . |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | Template PowerPoint (.pot) mewakili file template Microsoft PowerPoint yang dibuat dengan versi PowerPoint 97-2003. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) adalah file template Microsoft PowerPoint dengan dukungan untuk Macro. File POTM dibuat dengan PowerPoint 2007 atau lebih tinggi dan berisi pengaturan default yang dapat digunakan untuk membuat file presentasi lebih lanjut. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint Open XML Presentation Template (.potx) mewakili template presentasi Microsoft PowerPoint yang dibuat dengan Microsoft PowerPoint 2007 dan yang lebih baru. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | PowerPoint Slide Show (.pps) dibuat menggunakan Microsoft PowerPoint untuk keperluan Slide Show. Pembacaan dan pembuatan file PPS didukung oleh Microsoft PowerPoint 97-2003. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) mewakili format file Peragaan Slide dengan Makro yang dibuat dengan Microsoft PowerPoint 2007 atau lebih tinggi. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | File PowerPoint Open XML Slide Show (.ppsx) dibuat menggunakan Microsoft PowerPoint 2007 dan yang lebih baru untuk keperluan Slide Show. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | PowerPoint Presentation (.ppt) merupakan file PowerPoint yang terdiri dari kumpulan slide untuk ditampilkan sebagai SlideShow. Ini menentukan Format File Biner yang digunakan oleh Microsoft PowerPoint 97-2003. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation adalah file Presentasi dengan Macro-enabled yang dibuat dengan Microsoft PowerPoint 2007 atau versi yang lebih tinggi. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) adalah file presentasi yang dibuat dengan aplikasi Microsoft PowerPoint yang populer. Berbeda dengan versi sebelumnya dari format file presentasi PPT yang biner, format PPTX didasarkan pada format file presentasi terbuka XML Microsoft PowerPoint. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | Berkas PostScript (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Adobe Photoshop Document (.psd) mewakili format file asli Adobe Photoshop yang digunakan untuk desain dan pengembangan grafis. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/psd) . |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | File Format Teks Kaya (.rtf) mewakili metode pengkodean teks dan grafik yang diformat untuk digunakan dalam aplikasi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | Scalable Vector Graphics File (.svg) adalah file Grafik Vektor Skalar yang menggunakan format teks berbasis XML untuk mendeskripsikan tampilan gambar. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | File Gambar Tagged (.tif) mewakili gambar raster yang dimaksudkan untuk digunakan pada berbagai perangkat yang mematuhi standar format file ini. Itu mampu menggambarkan data gambar bilevel, skala abu-abu, warna palet dan penuh warna di beberapa ruang warna. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | Tagged Image File Format (.tiff) mewakili gambar raster yang dimaksudkan untuk digunakan pada berbagai perangkat yang sesuai dengan standar format file ini. Itu mampu menggambarkan data gambar bilevel, skala abu-abu, warna palet dan penuh warna di beberapa ruang warna. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | File Nilai Terpisah Tab (.tsv) mewakili data yang dipisahkan dengan tab dalam format teks biasa. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | Plain Text File (.txt) merupakan dokumen teks yang berisi teks biasa dalam bentuk garis. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | Mewakili jenis file yang tidak diketahui. |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | File vCard (.vcf) adalah format file digital untuk menyimpan informasi kontak. Format ini banyak digunakan untuk pertukaran data di antara aplikasi pertukaran informasi populer. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/email/vcf) . |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | WebP Image (.webp) adalah format file gambar web raster modern yang didasarkan pada kompresi lossless dan lossy. Ini memberikan kualitas gambar yang sama sambil sangat mengurangi ukuran gambar. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/webp) . |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | Windows Metafile (.wmf) mewakili Microsoft Windows Metafile (WMF) untuk menyimpan vektor serta data gambar berformat bitmap. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/wmf) . |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | Dokumen WordPerfect (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | Excel Spreadsheet (.xls) mewakili Format File Biner Excel. File tersebut dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | Excel Binary Spreadsheet (.xlsb) menentukan Format File Biner Excel, yang merupakan kumpulan rekaman dan struktur yang menentukan konten buku kerja Excel. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) adalah jenis file Spreadsheet yang mendukung makro. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) adalah format terkenal untuk dokumen Microsoft Excel yang diperkenalkan oleh Microsoft dengan rilis Microsoft Office 2007. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | Excel binary Template (.xlt) mewakili Format File Template Excel. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | Templat file Excel Office OpenXML (.xltm) mewakili Format File Templat Excel. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/xltm) . |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Signature: [Format dokumen didukung oleh GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* Lebih lanjut tentang cara mendapatkan daftar format yang didukung di C#: [Cara mendapatkan format file yang didukung dalam kode C#](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### Lihat juga

* ruang nama [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* perakitan [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
