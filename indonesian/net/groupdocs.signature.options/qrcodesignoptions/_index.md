---
title: QrCodeSignOptions
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Mewakili opsi tanda tangan QRCode.
type: docs
weight: 1630
url: /id/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

Mewakili opsi tanda tangan QR-Code.

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | Menginisialisasi instance baru dari kelas QRCodeSignOptions dengan nilai default. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | Menginisialisasi instance baru dari kelas QRCodeSignOptions dengan text. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan text. |

## Properti

| Nama | Keterangan |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Beri tanda tangan pada semua halaman dokumen. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Tampilan tanda tangan tambahan. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Mendapat atau menyetel pengaturan latar belakang tanda tangan. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Tentukan pengaturan batas |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | Mendapat atau menyetel perataan teks pada hasil gambar kode QR. Nilai defaultnya adalah Tidak ada. |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | Mendapatkan atau menyetel objek khusus untuk diserialisasikan ke konten QR-Code. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | Mendapatkan atau menetapkan implementasi dari[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) antarmuka untuk menyandikan dan mendekode properti QR-Code Signature Text atau Data. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Dapatkan atau atur Jenis Dokumen dari Opsi Tanda Tangan[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | Mendapat atau menyetel jenis QR-Code. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Ekstensi Tanda Tangan. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Mendapat atau menyetel font tanda tangan. |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | Mendapat atau menyetel warna Depan bilah Kode QR Menggunakan properti ini dapat menyebabkan masalah dengan verifikasi. Gunakan dengan hati-hati. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Mendapat atau menetapkan judul bidang formulir teks untuk memasukkan tanda tangan teks ke dalamnya. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Mendapat atau menyetel jenis bidang formulir untuk memasukkan tanda tangan teks ke dalamnya. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextToFormField. Nilai secara default adalah AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Tinggi Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen, atau milimeter lihat[`MeasureType`](../../groupdocs.signature.domain/measuretype) Properti SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Penjajaran tanda tangan secara horizontal pada halaman dokumen. |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | Mendapat atau mengatur spasi antara elemen QR-Code dan batas gambar hasil. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Posisi X Kiri Tanda Tangan pada Halaman Dokumen dalam nilai Ukur (piksel, persen, atau milimeter lihat[`MeasureType`](../../groupdocs.signature.domain/measuretype) Properti LocationMeasureType). (berfungsi jika perataan horizontal tidak ditentukan). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Jenis pengukuran (piksel, persen, atau milimeter) untuk properti Kiri dan Atas. |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | Mendapat atau menyetel nama file gambar logo kode QR. Properti ini hanya digunakan jika LogoStream tidak ditentukan. Penggunaan properti ini dapat menyebabkan masalah verifikasi. Gunakan dengan hati-hati. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | Mendapat atau menyetel aliran gambar logo kode QR. Jika properti ini ditentukan, properti ini selalu digunakan sebagai gantinya LogoFilePath. Penggunaan properti ini dapat menyebabkan masalah dengan verifikasi. Gunakan dengan hati-hati. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Mendapat atau mengatur spasi antara tepi Tanda dan Dokumen. (HANYA berfungsi jika perataan horizontal atau vertikal ditentukan). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Mendapat atau menetapkan jenis pengukuran (piksel, persen, atau milimeter) untuk Margin. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Mendapat atau menetapkan atribut asli. Jika sudah diatur, tanda tangan khusus dokumen dapat digunakan. Tanda air teks asli untuk dokumen Pemrosesan Kata berbeda dari biasanya, misalnya. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Mendapat atau menetapkan nomor halaman dokumen untuk ditandatangani. Minimal dan nilai standarnya adalah 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opsi untuk menentukan halaman yang akan ditandatangani. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | Mengambil atau menyetel flag untuk mendapatkan konten gambar QR-Code dari tanda tangan yang diletakkan di halaman dokumen. Jika flag ini disetel true, konten gambar tanda tangan QR-Code akan menyimpan data gambar mentah dengan format yang diperlukan[`ReturnContentType`](./returncontenttype) . Secara default opsi ini dinonaktifkan. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | Menentukan jenis file konten gambar yang dikembalikan dari tanda tangan QR-Code saat properti ReturnContent diaktifkan. Secara default diatur ke Null. Itu berarti mengembalikan konten gambar QR-Code dalam format aslinya. Format gambar ini ditentukan di[`Format`](../../groupdocs.signature.domain/qrcodesignature/format) Kemungkinan nilai yang didukung adalah: FileType.JPEG, FileType.PNG, FileType.BMP. Jika format yang diberikan tidak didukung maka konten gambar QR-Code dalam format .png akan dikembalikan. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Sudut rotasi tanda tangan pada halaman dokumen (searah jarum jam). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Mendapat atau mengatur jenis bentuk untuk meletakkan teks. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextStamp. Nilai defaultnya adalah Rectangle. |
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

* Penggunaan dasar pembuatan tanda tangan elektronik QR-Code oleh GroupDocs.Signature: [Bagaimana cara menandatangani dokumen dengan tanda tangan QR-Code](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* Penggunaan lanjutan pengaturan tanda tangan elektronik QR-Code dengan GroupDocs.Signature: [Penggunaan tingkat lanjut untuk menandatangani dokumen dengan tanda tangan QR-Code dan pengaturan tambahan](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### Lihat juga

* class [TextSignOptions](../textsignoptions)
* ruang nama [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* perakitan [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
