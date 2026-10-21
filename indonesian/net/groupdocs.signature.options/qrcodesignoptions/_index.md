---
title: "QrCodeSignOptions"
second_title: "Referensi API GroupDocs.Signature untuk .NET"
description: "Mewakili opsi tanda tangan QRCode."
type: docs
weight: 1920
url: /id/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

Mewakili opsi tanda tangan QR-Code.

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | Menginisialisasi instance baru dari kelas QRCodeSignOptions dengan nilai default. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | Menginisialisasi instance baru dari kelas QRCodeSignOptions dengan teks. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan teks. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Menempatkan tanda tangan pada semua halaman dokumen. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Penampilan tanda tangan tambahan. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Mengambil atau mengatur pengaturan latar belakang tanda tangan. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Tentukan pengaturan batas |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | Mendapatkan atau mengatur perataan teks dalam gambar QR-code hasil. Nilai default adalah None. |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | Mendapatkan atau mengatur objek khusus untuk diserialisasi ke konten QR-Code. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | Mendapatkan atau mengatur implementasi antarmuka [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) untuk mengenkripsi dan mendekripsi Properti Teks atau Data Tanda Tangan QR-Code. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Dapatkan atau atur Tipe Dokumen dari Opsi Tanda Tangan [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | Mendapatkan atau mengatur tipe QR-Code. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Ekstensi Tanda Tangan. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Mengambil atau mengatur font tanda tangan. |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | Mendapatkan atau mengatur warna Fore dari batang QR-Code. Penggunaan properti ini dapat menyebabkan masalah pada verifikasi. Gunakan dengan hati-hati. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Mengambil atau mengatur judul bidang formulir teks untuk menempatkan tanda tangan teks di dalamnya. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Mengambil atau mengatur tipe bidang formulir untuk menempatkan tanda tangan teks di dalamnya. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextToFormField. Nilai default adalah AllTextTypes. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Mendapatkan atau mengatur algoritma hash yang akan digunakan untuk operasi kriptografi. Didukung secara eksklusif untuk tanda tangan digital dalam file PDF. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Tinggi Tanda Tangan pada Halaman Dokumen dalam nilai Pengukuran (piksel, persen, atau milimeter lihat [`MeasureType`](../../groupdocs.signature.domain/measuretype) properti SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Perataan horizontal tanda tangan pada halaman dokumen. |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | Mendapatkan atau mengatur jarak antara elemen QR-Code dan batas gambar hasil. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Posisi X kiri dari Tanda Tangan pada Halaman Dokumen dalam nilai Pengukuran (piksel, persentase atau milimeter lihat [`MeasureType`](../../groupdocs.signature.domain/measuretype) properti LocationMeasureType). (berfungsi jika perataan horizontal tidak ditentukan). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Jenis pengukuran (piksel, persen atau milimeter) untuk properti Left dan Top. |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | Mendapatkan atau mengatur nama file gambar logo QR-code. Properti ini hanya digunakan jika LogoStream tidak ditentukan. Penggunaan properti ini dapat menyebabkan masalah pada verifikasi. Gunakan dengan hati-hati. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | Mendapatkan atau mengatur aliran gambar logo QR-code. Jika properti ini ditentukan, selalu digunakan menggantikan LogoFilePath. Penggunaan properti ini dapat menyebabkan masalah pada verifikasi. Gunakan dengan hati-hati. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Mendapatkan atau mengatur ruang antara Tanda dan tepi Dokumen. (berfungsi HANYA jika perataan horizontal atau vertikal ditentukan). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Mendapatkan atau mengatur jenis ukuran (piksel, persen atau milimeter) untuk Margin. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Mendapatkan atau mengatur atribut native. Jika diatur, tanda tangan khusus dokumen dapat digunakan. Watermark teks native untuk dokumen WordProcessing berbeda dari yang biasa, misalnya. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Mendapatkan atau mengatur nomor halaman dokumen untuk penandatanganan. Nilai minimal dan default adalah 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opsi untuk menentukan halaman yang akan ditandatangani. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | Mendapatkan atau mengatur flag untuk memperoleh konten gambar QR-Code dari tanda tangan yang ditempatkan pada halaman dokumen. Jika flag ini diatur ke true, konten gambar tanda tangan QR-Code akan mempertahankan data gambar mentah dengan format yang diperlukan [`ReturnContentType`](./returncontenttype). Secara default opsi ini dinonaktifkan. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | Menentukan jenis file dari konten gambar yang dikembalikan untuk tanda tangan QR-Code ketika properti ReturnContent diaktifkan. Secara default diatur ke Null. Itu berarti mengembalikan konten gambar QR-Code dalam format asli. Format gambar ini ditentukan pada [`Format`](../../groupdocs.signature.domain/qrcodesignature/format). Nilai yang didukung antara lain: FileType.JPEG, FileType.PNG, FileType.BMP. Jika format yang diberikan tidak didukung, maka konten gambar QR-Code dalam format .png akan dikembalikan. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Sudut rotasi tanda tangan pada halaman dokumen (searah jarum jam). |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | Mendefinisikan di mana bentuk harus ditampilkan dalam tata letak dokumen. Tersedia hanya untuk dokumen Word. |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Mendapatkan atau mengatur jenis bentuk untuk menempatkan teks. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextStamp. Nilai default adalah Rectangle. |
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

* Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: [How to eSign document with QR-Code signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with QR-Code signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### Lihat Juga

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
