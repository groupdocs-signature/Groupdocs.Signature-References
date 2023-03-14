---
title: StampSignOptions
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Mewakili opsi Tanda tangan stempel.
type: docs
weight: 1710
url: /id/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

Mewakili opsi Tanda tangan stempel.

```csharp
public class StampSignOptions : ImageSignOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | Menginisialisasi instance baru dari kelas StampSignOptions dengan nilai default. |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | Menginisialisasi instance baru dari kelas StampSignOptions dengan opsi perataan. |

## Properti

| Nama | Keterangan |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Beri tanda tangan pada semua halaman dokumen. Properti ini hanya dapat digunakan untuk format gambar multi-frame (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Tampilan tanda tangan tambahan. |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | Mendapat atau menyetel latar belakang Stempel. |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | Mendapat atau menyetel jenis tanda tangan warna latar belakang yang dipotong. |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | Mendapat atau menyetel jenis tanda tangan pemotongan gambar latar belakang. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Tentukan pengaturan batas |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Dapatkan atau atur Jenis Dokumen dari Opsi Tanda Tangan[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Ekstensi Tanda Tangan. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Tinggi Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen, atau milimeter lihat[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Penjajaran tanda tangan secara horizontal pada halaman dokumen. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Mendapat atau menyetel jalur file gambar tanda tangan. Properti ini hanya digunakan jika ImageStream tidak ditentukan. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Mendapat atau menyetel aliran gambar tanda tangan. Jika properti ini ditentukan, properti ini selalu digunakan sebagai ImageFilePath. |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | Daftar Garis Dalam yang dirender sebagai kumpulan persegi panjang. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Posisi X Kiri Tanda Tangan pada Halaman Dokumen dalam nilai Ukur (piksel, persen, atau milimeter lihat[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (berfungsi jika perataan horizontal tidak ditentukan). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Jenis pengukuran (piksel, persen, atau milimeter) untuk properti Kiri dan Atas. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Mendapat atau mengatur spasi antara tepi Tanda dan Dokumen. (HANYA berfungsi jika perataan horizontal atau vertikal ditentukan). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Mendapat atau menetapkan jenis pengukuran (piksel, persen, atau milimeter) untuk Margin. |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | Daftar Garis Luar yang dirender sebagai lingkaran konsentris. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Mendapat atau menetapkan nomor halaman dokumen untuk ditandatangani. Minimal dan nilai standarnya adalah 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opsi untuk menentukan halaman yang akan ditandatangani. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Persegi panjang area untuk menempatkan gambar pada dokumen. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Sudut rotasi tanda tangan pada halaman dokumen (searah jarum jam). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Dapatkan Jenis Tanda Tangan[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Mengukur jenis (piksel, persen, atau milimeter) untuk properti Lebar dan Tinggi. |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | Mendapat atau menyetel jenis stempel. Nilai defaultnya adalah Round. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Mode peregangan di Halaman Dokumen. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Posisi Y Atas Tanda Tangan pada Halaman Dokumen dalam nilai Ukur (piksel, persen, atau milimeter lihat[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (berfungsi jika perataan vertikal tidak ditentukan). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Mendapat atau menyetel transparansi tanda tangan (nilai dari 0,0 (buram) hingga 1,0 (jelas)). Nilai default adalah 0 (buram). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Perataan vertikal tanda tangan pada halaman dokumen. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Lebar Tanda Tangan pada Halaman Dokumen dalam Nilai ukuran (piksel, persen, atau milimeter[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Mendapat atau mengatur posisi Z-order dari tanda tangan teks. Menentukan urutan tampilan tanda tangan yang tumpang tindih. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Menghapus sumber daya internal |

### Perkataan

**Belajarlah lagi**

* Penggunaan dasar untuk membuat tanda tangan elektronik Stempel oleh GroupDocs.Signature: [Bagaimana cara menandatangani dokumen dengan tanda tangan Stempel](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* Penggunaan lanjutan pengaturan tanda tangan elektronik Cap dengan GroupDocs.Signature: [Penggunaan tingkat lanjut untuk menandatangani dokumen dengan Tanda tangan stempel dan pengaturan tambahan](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### Lihat juga

* class [ImageSignOptions](../imagesignoptions)
* ruang nama [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* perakitan [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
