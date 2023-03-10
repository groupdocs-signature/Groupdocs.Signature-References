---
title: FormFieldSignOptions
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Mewakili kelas opsi tanda tangan FormField untuk dokumen Pdf.
type: docs
weight: 1380
url: /id/net/groupdocs.signature.options/formfieldsignoptions/
---
## FormFieldSignOptions class

Mewakili kelas opsi tanda tangan FormField untuk dokumen Pdf.

```csharp
public sealed class FormFieldSignOptions : TextSignOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [FormFieldSignOptions](formfieldsignoptions#constructor)() | Menginisialisasi instance baru dari kelas PdfFormFieldSignOptions dengan nilai default. |
| [FormFieldSignOptions](formfieldsignoptions#constructor_1)(FormFieldSignature) | Menginisialisasi instance baru dari kelas PdfFormFieldSignOptions dengan tanda tangan FormField. |

## Properti

| Nama | Keterangan |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Beri tanda tangan pada semua halaman dokumen. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Tampilan tanda tangan tambahan. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Mendapat atau menyetel pengaturan latar belakang tanda tangan. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Tentukan pengaturan batas |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Dapatkan atau atur Jenis Dokumen dari Opsi Tanda Tangan[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Ekstensi Tanda Tangan. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Mendapat atau menyetel font tanda tangan. |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | Mendapat atau menyetel warna depan tanda tangan. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Mendapat atau menetapkan judul bidang formulir teks untuk memasukkan tanda tangan teks ke dalamnya. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Mendapat atau menyetel jenis bidang formulir untuk memasukkan tanda tangan teks ke dalamnya. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextToFormField. Nilai secara default adalah AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Tinggi Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen, atau milimeter lihat[`MeasureType`](../../groupdocs.signature.domain/measuretype) Properti SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Penjajaran tanda tangan secara horizontal pada halaman dokumen. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Posisi X Kiri Tanda Tangan pada Halaman Dokumen dalam nilai Ukur (piksel, persen, atau milimeter lihat[`MeasureType`](../../groupdocs.signature.domain/measuretype) Properti LocationMeasureType). (berfungsi jika perataan horizontal tidak ditentukan). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Jenis pengukuran (piksel, persen, atau milimeter) untuk properti Kiri dan Atas. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Mendapat atau mengatur spasi antara tepi Tanda dan Dokumen. (HANYA berfungsi jika perataan horizontal atau vertikal ditentukan). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Mendapat atau menetapkan jenis pengukuran (piksel, persen, atau milimeter) untuk Margin. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Mendapat atau menetapkan atribut asli. Jika sudah diatur, tanda tangan khusus dokumen dapat digunakan. Tanda air teks asli untuk dokumen Pemrosesan Kata berbeda dari biasanya, misalnya. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Mendapat atau menetapkan nomor halaman dokumen untuk ditandatangani. Minimal dan nilai standarnya adalah 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opsi untuk menentukan halaman yang akan ditandatangani. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Sudut rotasi tanda tangan pada halaman dokumen (searah jarum jam). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Mendapat atau mengatur jenis bentuk untuk meletakkan teks. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextStamp. Nilai defaultnya adalah Rectangle. |
| [Signature](../../groupdocs.signature.options/formfieldsignoptions/signature) { get; set; } | Mendapat atau menyetel FormField tanda tangan. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Mendapat atau menyetel ID unik tanda tangan. Ini dapat digunakan dalam opsi verifikasi tanda tangan. Properti hanya didukung untuk dokumen Pdf. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Mendapat atau menetapkan jenis implementasi tanda tangan teks. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Dapatkan Jenis Tanda Tangan[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Mengukur jenis (piksel, persen, atau milimeter) untuk properti Lebar dan Tinggi. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Mode peregangan di Halaman Dokumen. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Mendapat atau menyetel teks tanda tangan. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Perataan horizontal teks di dalam tanda tangan. Fitur ini hanya didukung untuk implementasi tanda tangan Gambar dan Anotasi (lihat[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) Properti SignatureImplementation). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Perataan vertikal teks di dalam tanda tangan. Fitur ini hanya didukung untuk implementasi Tanda tangan gambar (lihat[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) properti SignatureImplementation). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Posisi Y Atas Tanda Tangan pada Halaman Dokumen dalam nilai Ukur (piksel, persen, atau milimeter lihat[`MeasureType`](../../groupdocs.signature.domain/measuretype)Properti LocationMeasureType). (berfungsi jika perataan vertikal tidak ditentukan). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Mendapat atau menyetel transparansi tanda tangan (nilai dari 0,0 (buram) hingga 1,0 (jelas)). Nilai default adalah 0 (buram). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Perataan vertikal tanda tangan pada halaman dokumen. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Lebar Tanda Tangan pada Halaman Dokumen dalam Nilai ukuran (piksel, persen, atau milimeter lihat[`MeasureType`](../../groupdocs.signature.domain/measuretype) Properti SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Mendapat atau mengatur posisi Z-order dari tanda tangan teks. Menentukan urutan tampilan tanda tangan yang tumpang tindih. |

### Perkataan

**Belajarlah lagi**

* Penggunaan dasar pembuatan tanda tangan elektronik FormField oleh GroupDocs.Signature: [Bagaimana cara menandatangani dokumen dengan tanda tangan FormField](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature)
* Penggunaan lanjutan pengaturan tanda tangan elektronik FormField dengan GroupDocs.Signature: [Penggunaan tingkat lanjut untuk menandatangani dokumen dengan tanda tangan FormField dan pengaturan tambahan](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced)

### Lihat juga

* class [TextSignOptions](../textsignoptions)
* ruang nama [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* perakitan [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
