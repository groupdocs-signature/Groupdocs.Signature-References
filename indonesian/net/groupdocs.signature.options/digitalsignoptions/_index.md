---
title: "DigitalSignOptions"
second_title: "Referensi API GroupDocs.Signature untuk .NET"
description: "Mewakili opsi tanda tangan Digital."
type: docs
weight: 1560
url: /id/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Mewakili opsi tanda tangan Digital.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan nilai default. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan aliran sertifikat. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan file sertifikat. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan aliran sertifikat dan aliran gambar. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan aliran sertifikat dan file gambar. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan file sertifikat dan aliran gambar. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan file sertifikat dan file gambar. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AllowExpired](../../groupdocs.signature.options/digitalsignoptions/allowexpired) { get; set; } | Mendapatkan atau mengatur flag yang memungkinkan penandatanganan dengan sertifikat yang masa berlakunya telah berakhir. Nilai default adalah false: penandatanganan dengan sertifikat yang kedaluwarsa melempar [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception), dan dokumen tidak ditandatangani. |
| [AllowNotYetValid](../../groupdocs.signature.options/digitalsignoptions/allownotyetvalid) { get; set; } | Mendapatkan atau mengatur flag yang memungkinkan penandatanganan dengan sertifikat yang masa berlakunya belum dimulai. Nilai default adalah false: penandatanganan dengan sertifikat semacam itu melempar [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception), dan dokumen tidak ditandatangani. |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Menempatkan tanda tangan pada semua halaman dokumen. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Penampilan tanda tangan tambahan. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Tentukan pengaturan batas |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Mendapatkan atau mengatur jalur file sertifikat digital. Properti ini hanya digunakan jika CertificateStream tidak ditentukan. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Mendapatkan atau mengatur aliran sertifikat digital. Jika properti ini ditentukan, selalu digunakan menggantikan CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Mendapatkan atau mengatur kontak tanda tangan. |
| [CustomSignHash](../../groupdocs.signature.options/digitalsignoptions/customsignhash) { get; set; } | Mendapatkan atau mengatur fungsi penandatanganan hash khusus, memungkinkan pengguna mengimplementasikan logika penandatanganan digital mereka sendiri. Ini memungkinkan penandatanganan dengan sertifikat eksternal dan mendukung berbagai algoritma hash. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Dapatkan atau atur Tipe Dokumen dari Opsi Tanda Tangan [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Ekstensi Tanda Tangan. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Mendapatkan atau mengatur algoritma hash yang akan digunakan untuk operasi kriptografi. Didukung secara eksklusif untuk tanda tangan digital dalam file PDF. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Tinggi Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen atau milimeter lihat [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Perataan horizontal tanda tangan pada halaman dokumen. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Mendapatkan atau mengatur jalur file gambar tanda tangan. Properti ini hanya digunakan jika ImageStream tidak ditentukan. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Mendapatkan atau mengatur aliran gambar tanda tangan. Jika properti ini ditentukan, selalu digunakan menggantikan ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Posisi X kiri dari Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen atau milimeter lihat [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (berfungsi jika perataan horizontal tidak ditentukan). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Mendapatkan atau mengatur lokasi tanda tangan. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Jenis pengukuran (piksel, persen atau milimeter) untuk properti Left dan Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Mendapatkan atau mengatur ruang antara Tanda dan tepi Dokumen. (berfungsi HANYA jika perataan horizontal atau vertikal ditentukan). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Mendapatkan atau mengatur jenis ukuran (piksel, persen atau milimeter) untuk Margin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Mendapatkan atau mengatur nomor halaman dokumen untuk penandatanganan. Nilai minimal dan default adalah 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opsi untuk menentukan halaman yang akan ditandatangani. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Mendapatkan atau mengatur kata sandi sertifikat digital. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Mendapatkan atau mengatur alasan tanda tangan. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Persegi panjang area untuk menempatkan gambar pada dokumen. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Sudut rotasi tanda tangan pada halaman dokumen (searah jarum jam). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Mendefinisikan di mana bentuk harus ditampilkan dalam tata letak dokumen. Tersedia hanya untuk dokumen Word. |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Mendapatkan atau mengatur properti tanda tangan digital dokumen. Untuk menandatangani dokumen Pdf, dimungkinkan mengatur properti lanjutan dengan menggunakan instance dari [`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Dapatkan Tipe Tanda Tangan [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Tipe ukuran (piksel, persen atau milimeter) untuk properti Width dan Height. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Mode peregangan pada Halaman Dokumen. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Posisi Y atas dari Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen atau milimeter lihat [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (berfungsi jika perataan vertikal tidak ditentukan). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Mendapatkan atau mengatur transparansi tanda tangan (nilai dari 0.0 (buram) hingga 1.0 (jernih)). Nilai default adalah 0 (buram). |
| [UseLtv](../../groupdocs.signature.options/digitalsignoptions/useltv) { get; set; } | Mendapatkan/mengatur flag validasi ltv (Long Term Validation). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Perataan vertikal tanda tangan pada halaman dokumen. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Mendapatkan atau mengatur visibilitas tanda tangan. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Lebar Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen atau milimeter [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | Tipe XAdES [`XAdESType`](./xadestype). Nilai default adalah None (XAdES dimatikan). Saat ini tipe tanda tangan XAdES hanya didukung untuk dokumen Spreadsheet. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Mendapatkan atau mengatur posisi Z-order dari tanda tangan teks. Menentukan urutan tampilan tanda tangan yang tumpang tindih. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Membersihkan sumber daya internal |

### Catatan

**Learn more**

* Basic usage of creating Digital electronic signature by GroupDocs.Signature: [How to eSign document with Digital signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Digital signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Lihat Juga

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
