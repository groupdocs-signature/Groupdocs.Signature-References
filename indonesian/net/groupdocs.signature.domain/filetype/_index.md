---
title: "FileType"
second_title: "Referensi API GroupDocs.Signature untuk .NET"
description: "Mewakili tipe file."
type: docs
weight: 610
url: /id/net/groupdocs.signature.domain/filetype/
---
## FileType class

Mewakili tipe file.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | Akhiran nama file (termasuk titik ".") contoh ".doc". |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | Nama tipe file contoh "Microsoft Word Document". |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | Memetakan ekstensi file ke tipe file. |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | Menentukan apakah [`FileType`](../filetype) saat ini sama dengan objek [`FileType`](../filetype) yang ditentukan. |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | Menentukan apakah [`FileType`](../filetype) saat ini sama dengan objek yang ditentukan. |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | Mengembalikan kode hash untuk objek [`FileType`](../filetype) saat ini. |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | Mengembalikan string yang mewakili objek saat ini. |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | Mengambil tipe file yang didukung |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | Menentukan apakah dua objek [`FileType`](../filetype) sama. |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | Menentukan apakah dua objek [`FileType`](../filetype) tidak sama. |

## Fields

| Nama | Deskripsi |
| --- | --- |
| static readonly [APNG](../../groupdocs.signature.domain/filetype/apng) | Animated Portable Network Graphics (.png) adalah format file gambar raster yang menggunakan kompresi lossless. Format ini dikembangkan sebagai ekstensi PNG untuk mendukung animasi, berfungsi sebagai alternatif format GIF tanpa batasan hak cipta. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/apng). |
| static readonly [AZW3](../../groupdocs.signature.domain/filetype/azw3) | WordPerfect Document (.wpd) |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | Bitmap Image File (.bmp) digunakan untuk menyimpan gambar digital bitmap. Gambar-gambar ini independen dari adaptor grafis dan juga disebut format file device independent bitmap (DIB). Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/bmp). |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) adalah file gambar vektor yang secara native dibuat dengan CorelDRAW untuk menyimpan gambar digital yang dikodekan dan dikompresi. File gambar tersebut berisi teks, garis, bentuk, gambar, warna, dan efek untuk representasi vektor dari isi gambar. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/cdr). |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | Computer Graphics Metafile (.cgm) adalah format metafile standar internasional yang gratis, platform-independen, untuk menyimpan dan menukar grafik vektor (2D), grafik raster, dan teks. CGM menggunakan pendekatan berorientasi objek dan banyak fungsi untuk produksi gambar. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/page-description-language/cgm). |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | CorelDRAW Metafile Exchange Image File (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | Comma Separated Values File (.csv) mewakili file teks biasa yang berisi catatan data dengan nilai yang dipisahkan koma. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | DICOM Image (.dcm) mewakili gambar digital yang menyimpan informasi medis pasien seperti MRI, CT scan, dan gambar ultrasonik. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/dcm). |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | DjVu Image (.djvu) adalah format file grafis yang ditujukan untuk dokumen dan buku yang dipindai, terutama yang mengandung kombinasi teks, gambar, foto, dan ilustrasi. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/djvu). |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Microsoft Word Document (.doc) mewakili dokumen yang dihasilkan oleh Microsoft Word atau program pengolah kata lain dalam format file biner. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm) adalah dokumen yang dihasilkan oleh Microsoft Word 2007 atau yang lebih baru dengan kemampuan menjalankan makro. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) adalah format yang terkenal untuk dokumen Microsoft Word. Diperkenalkan sejak 2007 dengan rilis Microsoft Office 2007, struktur format Dokumen baru ini diubah dari biner biasa menjadi kombinasi file XML dan biner. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Word Document Template (.dot) adalah file templat yang dibuat oleh Microsoft Word dengan pengaturan pra-format untuk menghasilkan file DOC atau DOCX selanjutnya. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) mewakili file templat yang dibuat dengan Microsoft Word 2007 atau yang lebih baru. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Word Open XML Document Template (.dotx) adalah file templat yang dibuat oleh Microsoft Word dengan pengaturan pra-format untuk menghasilkan file DOCX selanjutnya. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | Enhanced Windows Metafile (.emf) mewakili gambar grafis secara device-independen. Meta-file EMF terdiri dari rekaman berukuran variabel dalam urutan kronologis yang dapat menampilkan gambar yang disimpan setelah diparsing pada perangkat output apa pun. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/emf). |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | File Encapsulated PostScript (.eps) menjelaskan program bahasa Encapsulated PostScript yang menggambarkan tampilan satu halaman. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/page-description-language/eps). |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | File Graphical Interchange Format (.gif) adalah jenis gambar yang sangat terkompresi. Untuk setiap gambar, GIF biasanya memungkinkan hingga 8 bit per piksel dan hingga 256 warna diizinkan di seluruh gambar. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/gif). |
| static readonly [GZip](../../groupdocs.signature.domain/filetype/gzip) | Arsip terkompresi GZip (.gz) mengompresi file dengan rasio kompresi tinggi. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/compression/gz). |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | Gambar JPEG (.jpeg) adalah jenis format gambar yang disimpan menggunakan metode kompresi lossy. Gambar output, sebagai hasil kompresi, merupakan kompromi antara ukuran penyimpanan dan kualitas gambar. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/jpeg). |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | Gambar JPEG (.jpg) adalah jenis format gambar yang disimpan menggunakan metode kompresi lossy. Gambar output, sebagai hasil kompresi, merupakan kompromi antara ukuran penyimpanan dan kualitas gambar. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/jpeg). |
| static readonly [LZip](../../groupdocs.signature.domain/filetype/lzip) | Arsip terkompresi LZip (.lz) mengompresi file dengan rasio kompresi tinggi. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/compression/lz). |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | File Grafik OpenDocument (.odg) digunakan oleh aplikasi Draw Apache OpenOffice untuk menyimpan elemen gambar sebagai gambar vektor. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/odg). |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | File Presentasi OpenDocument (.odp) merupakan format file presentasi yang digunakan oleh OpenOffice.org dalam standar OASIS Open. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/odp). |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | Spreadsheet OpenDocument (.ods) merupakan format dokumen Spreadsheet OpenDocument yang dapat diedit oleh pengguna. Data disimpan dalam file ODF dalam baris dan kolom. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | Dokumen Teks OpenDocument (.odt) adalah jenis dokumen yang dibuat dengan aplikasi pengolah kata yang berbasis pada format File Teks OpenDocument. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | Templat Presentasi OpenDocument (.otp) merupakan file templat presentasi yang dibuat oleh aplikasi dalam format standar OpenDocument OASIS. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/otp). |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | Templat Spreadsheet OpenDocument (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | Templat Dokumen OpenDocument (.ott) merupakan dokumen templat yang dihasilkan oleh aplikasi yang mematuhi standar OpenDocument OASIS. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | Dokumen Printer Command Language (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | File Portable Document Format (.pdf) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/view/pdf). |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | File Personal Information Exchange (.pfx) adalah file sertifikat yang dilindungi kata sandi dan biasanya digunakan untuk menandatangani kode aplikasi Anda. Pelajari lebih lanjut tentang format file ini [di sini](https://fileinfo.com/extension/pfx). |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | Grafik Jaringan Portabel (.png) adalah jenis format file gambar raster yang menggunakan kompresi lossless. Format file ini dibuat sebagai pengganti Graphics Interchange Format (GIF) dan tidak memiliki batasan hak cipta. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/png). |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | Templat PowerPoint (.pot) merupakan file templat Microsoft PowerPoint yang dibuat oleh versi PowerPoint 97-2003. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/pot). |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) adalah file templat Microsoft PowerPoint dengan dukungan untuk Makro. File POTM dibuat dengan PowerPoint 2007 atau yang lebih baru dan berisi pengaturan default yang dapat digunakan untuk membuat file presentasi lebih lanjut. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/potm). |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint Open XML Presentation Template (.potx) mewakili templat presentasi Microsoft PowerPoint yang dibuat dengan Microsoft PowerPoint 2007 ke atas. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/potx). |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | PowerPoint Slide Show (.pps) dibuat menggunakan Microsoft PowerPoint untuk tujuan Slide Show. Pembacaan dan pembuatan file PPS didukung oleh Microsoft PowerPoint 97-2003. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/pps). |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) mewakili format file Slide Show yang mendukung Makro yang dibuat dengan Microsoft PowerPoint 2007 atau yang lebih tinggi. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | File PowerPoint Open XML Slide Show (.ppsx) dibuat menggunakan Microsoft PowerPoint 2007 ke atas untuk tujuan Slide Show. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | PowerPoint Presentation (.ppt) mewakili file PowerPoint yang terdiri dari kumpulan slide untuk ditampilkan sebagai SlideShow. File ini menggunakan Binary File Format yang dipakai oleh Microsoft PowerPoint 97-2003. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation adalah file Presentasi yang mendukung Makro yang dibuat dengan Microsoft PowerPoint 2007 atau versi yang lebih tinggi. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) adalah file presentasi yang dibuat dengan aplikasi Microsoft PowerPoint yang populer. Tidak seperti versi sebelumnya dari format file presentasi PPT yang bersifat biner, format PPTX berbasis pada format file presentasi open XML Microsoft PowerPoint. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/pptx). |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | File PostScript (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Adobe Photoshop Document (.psd) mewakili format file asli Adobe Photoshop yang digunakan untuk perancangan dan pengembangan grafis. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/psd). |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | Rich Text Format File (.rtf) mewakili metode pengkodean teks terformat dan grafis untuk digunakan dalam aplikasi. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [SevenZip](../../groupdocs.signature.domain/filetype/sevenzip) | Arsip terkompresi tinggi (.7z) yang mengompresi file dan folder dengan rasio kompresi tinggi. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/page-description-language/7z). |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | Scalable Vector Graphics File (.svg) adalah file Scalable Vector Graphics yang menggunakan format teks berbasis XML untuk mendeskripsikan tampilan sebuah gambar. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/page-description-language/svg). |
| static readonly [TAR](../../groupdocs.signature.domain/filetype/tar) | Utilitas berbasis Unix untuk mengumpulkan satu atau lebih file (.tar) adalah arsip yang dapat menyimpan satu atau lebih file atau direktori. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/tar/). |
| static readonly [TGA](../../groupdocs.signature.domain/filetype/tga) | Truevision TGA (.tga), juga dikenal sebagai TARGA, adalah format file gambar raster yang dikembangkan oleh Truevision Inc. Format ini mendukung berbagai kedalaman warna dan kompresi RLE opsional. File TGA biasanya digunakan dalam video game, alur kerja animasi, dan aplikasi grafis untuk rendering gambar berkualitas tinggi dengan dukungan saluran alfa opsional. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/tga). |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | Tagged Image File (.tif) mewakili gambar raster yang dimaksud untuk digunakan pada berbagai perangkat yang mematuhi standar format file ini. Format ini mampu menggambarkan data gambar bilevel, grayscale, palette-color, dan full-color dalam beberapa ruang warna. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/tiff). |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | Tagged Image File Format (.tiff) mewakili gambar raster yang dimaksud untuk digunakan pada berbagai perangkat yang mematuhi standar format file ini. Format ini mampu menggambarkan data gambar bilevel, grayscale, palette-color, dan full-color dalam beberapa ruang warna. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/tiff). |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | Tab Separated Values File (.tsv) mewakili data yang dipisahkan dengan tab dalam format teks biasa. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | Plain Text File (.txt) mewakili dokumen teks yang berisi teks biasa dalam bentuk baris. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | Mewakili tipe file yang tidak diketahui. |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | vCard File (.vcf) adalah format file digital untuk menyimpan informasi kontak. Format ini banyak digunakan untuk pertukaran data di antara aplikasi pertukaran informasi yang populer. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/email/vcf). |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | WebP Image (.webp) adalah format file gambar web raster modern yang berbasis kompresi lossless dan lossy. Format ini memberikan kualitas gambar yang sama sambil secara signifikan mengurangi ukuran gambar. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/webp). |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | Windows Metafile (.wmf) mewakili Microsoft Windows Metafile (WMF) untuk menyimpan data gambar dalam format vektor maupun bitmap. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/wmf). |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | WordPerfect Document (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | Excel Spreadsheet (.xls) mewakili Excel Binary File Format. File semacam ini dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | Excel Binary Spreadsheet (.xlsb) menentukan Excel Binary File Format, yang merupakan kumpulan catatan dan struktur yang menentukan konten buku kerja Excel. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) adalah jenis file Spreadsheet yang mendukung makro. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) adalah format terkenal untuk dokumen Microsoft Excel yang diperkenalkan oleh Microsoft pada rilis Microsoft Office 2007. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | Excel binary Template (.xlt) mewakili Excel Template File Format. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | Excel Office OpenXML file Template (.xltm) mewakili Excel Template File Format. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [ZIP](../../groupdocs.signature.domain/filetype/zip) | Document ZIP archive (.zip) adalah format file arsip yang mendukung kompresi data lossless. Dapat menyimpan satu atau lebih file atau direktori. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/compression/zip/). |

### Catatan

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* More about how to get supported formats list in C#: [How to get supported file formats in C# code](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### Lihat Juga

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
