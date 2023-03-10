---
title: DigitalSignOptions
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Mewakili opsi Tanda tangan digital.
type: docs
weight: 1340
url: /id/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Mewakili opsi Tanda tangan digital.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan nilai default. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Menginisialisasi instance baru kelas DigitalSignOptions dengan aliran sertifikat. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan file sertifikat. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Menginisialisasi instance baru kelas DigitalSignOptions dengan aliran sertifikat dan aliran gambar. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Menginisialisasi instance baru kelas DigitalSignOptions dengan aliran sertifikat dan file gambar. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Menginisialisasi instance baru kelas DigitalSignOptions dengan file sertifikat dan aliran gambar. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Menginisialisasi instance baru kelas DigitalSignOptions dengan file sertifikat dan file gambar. |

## Properti

| Nama | Keterangan |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Beri tanda tangan pada semua halaman dokumen. Properti ini hanya dapat digunakan untuk format gambar multi-frame (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Tampilan tanda tangan tambahan. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Tentukan pengaturan batas |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Mendapat atau menyetel jalur file sertifikat digital. Properti ini hanya digunakan jika CertificateStream tidak ditentukan. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Mendapat atau menyetel aliran sertifikat digital. Jika properti ini ditentukan, properti ini selalu digunakan sebagai ganti CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Mendapat atau menyetel kontak tanda tangan. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Dapatkan atau atur Jenis Dokumen dari Opsi Tanda Tangan[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Ekstensi Tanda Tangan. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Tinggi Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen, atau milimeter lihat[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Penjajaran tanda tangan secara horizontal pada halaman dokumen. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Mendapat atau menyetel jalur file gambar tanda tangan. Properti ini hanya digunakan jika ImageStream tidak ditentukan. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Mendapat atau menyetel aliran gambar tanda tangan. Jika properti ini ditentukan, properti ini selalu digunakan sebagai ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Posisi X Kiri Tanda Tangan pada Halaman Dokumen dalam nilai Ukur (piksel, persen, atau milimeter lihat[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (berfungsi jika perataan horizontal tidak ditentukan). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Mendapat atau menyetel lokasi tanda tangan. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Jenis pengukuran (piksel, persen, atau milimeter) untuk properti Kiri dan Atas. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Mendapat atau mengatur spasi antara tepi Tanda dan Dokumen. (HANYA berfungsi jika perataan horizontal atau vertikal ditentukan). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Mendapat atau menetapkan jenis pengukuran (piksel, persen, atau milimeter) untuk Margin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Mendapat atau menetapkan nomor halaman dokumen untuk ditandatangani. Minimal dan nilai standarnya adalah 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opsi untuk menentukan halaman yang akan ditandatangani. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Mendapat atau menyetel kata sandi sertifikat digital. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Mendapat atau menyetel alasan tanda tangan. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Persegi panjang area untuk menempatkan gambar pada dokumen. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Sudut rotasi tanda tangan pada halaman dokumen (searah jarum jam). |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Mendapat atau mengatur properti tanda tangan digital dokumen. Untuk menandatangani dokumen Pdf dimungkinkan untuk mengatur properti tingkat lanjut dengan menggunakan turunan dari[`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Dapatkan Jenis Tanda Tangan[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Mengukur jenis (piksel, persen, atau milimeter) untuk properti Lebar dan Tinggi. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Mode peregangan di Halaman Dokumen. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Posisi Y Atas Tanda Tangan pada Halaman Dokumen dalam nilai Ukur (piksel, persen, atau milimeter lihat[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (berfungsi jika perataan vertikal tidak ditentukan). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Mendapat atau menyetel transparansi tanda tangan (nilai dari 0,0 (buram) hingga 1,0 (jelas)). Nilai default adalah 0 (buram). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Perataan vertikal tanda tangan pada halaman dokumen. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Mendapat atau menyetel visibilitas tanda tangan. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Lebar Tanda Tangan pada Halaman Dokumen dalam Nilai ukuran (piksel, persen, atau milimeter[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | tipe XAdES[`XAdESType`](./xadestype) . Nilai defaultnya adalah Tidak Ada (XAdES tidak aktif). Saat ini jenis tanda tangan XAdES hanya didukung untuk dokumen Spreadsheet. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Mendapat atau mengatur posisi Z-order dari tanda tangan teks. Menentukan urutan tampilan tanda tangan yang tumpang tindih. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Menghapus sumber daya internal |

### Perkataan

**Belajarlah lagi**

* Penggunaan dasar pembuatan tanda tangan elektronik digital oleh GroupDocs.Signature: [Cara menandatangani dokumen elektronik dengan tanda tangan digital](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Penggunaan lanjutan pengaturan tanda tangan elektronik digital dengan GroupDocs.Signature: [Penggunaan tingkat lanjut untuk menandatangani dokumen dengan tanda tangan digital dan pengaturan tambahan](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Lihat juga

* class [ImageSignOptions](../imagesignoptions)
* ruang nama [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* perakitan [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
