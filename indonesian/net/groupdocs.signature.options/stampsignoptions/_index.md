---
title: "StampSignOptions"
second_title: "Referensi API GroupDocs.Signature untuk .NET"
description: "Mewakili opsi tanda tangan Stempel."
type: docs
weight: 2000
url: /id/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

Mewakili opsi tanda tangan Stempel.

```csharp
public class StampSignOptions : ImageSignOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | Menginisialisasi sebuah instance baru dari kelas StampSignOptions dengan nilai default. |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | Menginisialisasi sebuah instance baru dari kelas StampSignOptions dengan opsi penyelarasan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Menempatkan tanda tangan pada semua halaman dokumen. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Penampilan tanda tangan tambahan. |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | Mendapatkan atau mengatur latar belakang Stamp. |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | Mendapatkan atau mengatur jenis pemotongan warna latar belakang tanda tangan. |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | Mendapatkan atau mengatur jenis pemotongan gambar latar belakang tanda tangan. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Tentukan pengaturan batas |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Dapatkan atau atur Tipe Dokumen dari Opsi Tanda Tangan [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Ekstensi Tanda Tangan. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Mendapatkan atau mengatur algoritma hash yang akan digunakan untuk operasi kriptografi. Didukung secara eksklusif untuk tanda tangan digital dalam file PDF. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Tinggi Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen atau milimeter lihat [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Perataan horizontal tanda tangan pada halaman dokumen. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Mendapatkan atau mengatur jalur file gambar tanda tangan. Properti ini hanya digunakan jika ImageStream tidak ditentukan. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Mendapatkan atau mengatur aliran gambar tanda tangan. Jika properti ini ditentukan, selalu digunakan menggantikan ImageFilePath. |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | Daftar Garis Dalam yang dirender sebagai sekumpulan persegi panjang. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Posisi X kiri dari Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen atau milimeter lihat [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (berfungsi jika perataan horizontal tidak ditentukan). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Jenis pengukuran (piksel, persen atau milimeter) untuk properti Left dan Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Mendapatkan atau mengatur ruang antara Tanda dan tepi Dokumen. (berfungsi HANYA jika perataan horizontal atau vertikal ditentukan). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Mendapatkan atau mengatur jenis ukuran (piksel, persen atau milimeter) untuk Margin. |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | Daftar Garis Luar yang dirender sebagai lingkaran konsentris. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Mendapatkan atau mengatur nomor halaman dokumen untuk penandatanganan. Nilai minimal dan default adalah 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opsi untuk menentukan halaman yang akan ditandatangani. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Persegi panjang area untuk menempatkan gambar pada dokumen. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Sudut rotasi tanda tangan pada halaman dokumen (searah jarum jam). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Mendefinisikan di mana bentuk harus ditampilkan dalam tata letak dokumen. Tersedia hanya untuk dokumen Word. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Dapatkan Tipe Tanda Tangan [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Tipe ukuran (piksel, persen atau milimeter) untuk properti Width dan Height. |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | Mendapatkan atau mengatur tipe stempel. Nilai default adalah Bulat. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Mode peregangan pada Halaman Dokumen. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Posisi Y atas dari Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen atau milimeter lihat [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (berfungsi jika perataan vertikal tidak ditentukan). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Mendapatkan atau mengatur transparansi tanda tangan (nilai dari 0.0 (buram) hingga 1.0 (jernih)). Nilai default adalah 0 (buram). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Perataan vertikal tanda tangan pada halaman dokumen. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Lebar Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen atau milimeter [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Mendapatkan atau mengatur posisi Z-order dari tanda tangan teks. Menentukan urutan tampilan tanda tangan yang tumpang tindih. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Membersihkan sumber daya internal |

### Catatan

**Learn more**

* Basic usage of creating Stamp electronic signature by GroupDocs.Signature: [How to eSign document with Stamp signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Stamp signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### Lihat Juga

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
