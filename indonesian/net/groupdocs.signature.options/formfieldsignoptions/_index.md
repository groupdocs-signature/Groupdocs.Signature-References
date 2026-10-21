---
title: "FormFieldSignOptions"
second_title: "Referensi API GroupDocs.Signature untuk .NET"
description: "Mewakili kelas opsi tanda tangan FormField untuk dokumen Pdf."
type: docs
weight: 1600
url: /id/net/groupdocs.signature.options/formfieldsignoptions/
---
## FormFieldSignOptions class

Mewakili kelas opsi tanda tangan FormField untuk dokumen Pdf.

```csharp
public sealed class FormFieldSignOptions : TextSignOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [FormFieldSignOptions](formfieldsignoptions#constructor)() | Menginisialisasi instance baru dari kelas PdfFormFieldSignOptions dengan nilai default. |
| [FormFieldSignOptions](formfieldsignoptions#constructor_1)(FormFieldSignature) | Menginisialisasi instance baru dari kelas PdfFormFieldSignOptions dengan tanda tangan FormField. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Menempatkan tanda tangan pada semua halaman dokumen. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Penampilan tanda tangan tambahan. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Mengambil atau mengatur pengaturan latar belakang tanda tangan. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Tentukan pengaturan batas |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Dapatkan atau atur Tipe Dokumen dari Opsi Tanda Tangan [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Ekstensi Tanda Tangan. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Mengambil atau mengatur font tanda tangan. |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | Mendapatkan atau mengatur warna depan tanda tangan. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Mengambil atau mengatur judul bidang formulir teks untuk menempatkan tanda tangan teks di dalamnya. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Mengambil atau mengatur tipe bidang formulir untuk menempatkan tanda tangan teks di dalamnya. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextToFormField. Nilai default adalah AllTextTypes. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Mendapatkan atau mengatur algoritma hash yang akan digunakan untuk operasi kriptografi. Didukung secara eksklusif untuk tanda tangan digital dalam file PDF. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Tinggi Tanda Tangan pada Halaman Dokumen dalam nilai Pengukuran (piksel, persen, atau milimeter lihat [`MeasureType`](../../groupdocs.signature.domain/measuretype) properti SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Perataan horizontal tanda tangan pada halaman dokumen. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Posisi X kiri dari Tanda Tangan pada Halaman Dokumen dalam nilai Pengukuran (piksel, persentase atau milimeter lihat [`MeasureType`](../../groupdocs.signature.domain/measuretype) properti LocationMeasureType). (berfungsi jika perataan horizontal tidak ditentukan). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Jenis pengukuran (piksel, persen atau milimeter) untuk properti Left dan Top. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Mendapatkan atau mengatur ruang antara Tanda dan tepi Dokumen. (berfungsi HANYA jika perataan horizontal atau vertikal ditentukan). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Mendapatkan atau mengatur jenis ukuran (piksel, persen atau milimeter) untuk Margin. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Mendapatkan atau mengatur atribut native. Jika diatur, tanda tangan khusus dokumen dapat digunakan. Watermark teks native untuk dokumen WordProcessing berbeda dari yang biasa, misalnya. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Mendapatkan atau mengatur nomor halaman dokumen untuk penandatanganan. Nilai minimal dan default adalah 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opsi untuk menentukan halaman yang akan ditandatangani. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Sudut rotasi tanda tangan pada halaman dokumen (searah jarum jam). |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | Mendefinisikan di mana bentuk harus ditampilkan dalam tata letak dokumen. Tersedia hanya untuk dokumen Word. |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Mendapatkan atau mengatur jenis bentuk untuk menempatkan teks. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextStamp. Nilai default adalah Rectangle. |
| [Signature](../../groupdocs.signature.options/formfieldsignoptions/signature) { get; set; } | Mendapatkan atau mengatur FormField dari tanda tangan. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Mendapatkan atau mengatur ID unik dari tanda tangan. Ini dapat digunakan dalam opsi verifikasi tanda tangan. Properti ini hanya didukung untuk dokumen Pdf. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Mendapatkan atau mengatur jenis implementasi tanda tangan teks. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Dapatkan Tipe Tanda Tangan [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Tipe ukuran (piksel, persen atau milimeter) untuk properti Width dan Height. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Mode peregangan pada Halaman Dokumen. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Mendapatkan atau mengatur teks tanda tangan. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Perataan horizontal teks di dalam tanda tangan. Fitur ini hanya didukung untuk implementasi tanda tangan Image dan Annotation (lihat [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) properti SignatureImplementation). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Perataan vertikal teks di dalam tanda tangan. Fitur ini hanya didukung untuk implementasi tanda tangan Image (lihat [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) properti SignatureImplementation). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Posisi Y atas dari Tanda Tangan pada Halaman Dokumen dalam nilai Pengukuran (piksel, persentase atau milimeter lihat [`MeasureType`](../../groupdocs.signature.domain/measuretype) properti SizeMeasureType). (berfungsi jika perataan vertikal tidak ditentukan). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Mendapatkan atau mengatur transparansi tanda tangan (nilai dari 0.0 (buram) hingga 1.0 (jernih)). Nilai default adalah 0 (buram). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Perataan vertikal tanda tangan pada halaman dokumen. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Lebar Tanda Tangan pada Halaman Dokumen dalam nilai Pengukuran (piksel, persentase atau milimeter lihat [`MeasureType`](../../groupdocs.signature.domain/measuretype) properti SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Mendapatkan atau mengatur posisi Z-order dari tanda tangan teks. Menentukan urutan tampilan tanda tangan yang tumpang tindih. |

### Catatan

**Learn more**

* Basic usage of creating FormField electronic signature by GroupDocs.Signature: [How to eSign document with FormField signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature)
* Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with FormField signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced)

### Lihat Juga

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
