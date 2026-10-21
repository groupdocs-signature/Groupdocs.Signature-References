---
title: "PdfDigitalSignature"
second_title: "Referensi API GroupDocs.Signature untuk .NET"
description: "Berisi properti Pdf Digital signature."
type: docs
weight: 840
url: /id/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Berisi properti Pdf Digital signature.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Inisialisasi Tanda Tangan Digital Pdf tanpa sertifikat. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Buat Tanda Tangan Digital Pdf dengan sertifikat yang ditentukan. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Inisialisasi Tanda Tangan Digital Pdf berdasarkan penyimpanan X509 yang ditentukan. Sertifikat pertama dari penyimpanan yang ditentukan akan digunakan. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Buat Tanda Tangan Digital Pdf berdasarkan Penyimpanan X509 yang ditentukan dan indeks sertifikat. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Mendapatkan atau mengatur sertifikat X509. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Menentukan nama penyimpanan khusus untuk sertifikat. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Menentukan lokasi penyimpanan sertifikat |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Menentukan nama penyimpanan sertifikat. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Mendapatkan atau mengatur komentar tujuan penandatanganan. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Informasi yang diberikan oleh penandatangan untuk memungkinkan penerima menghubungi penandatangan guna memverifikasi tanda tangan, misalnya nomor telepon. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Dapatkan atau atur tanggal pembuatan tanda tangan. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Dapatkan flag yang menunjukkan apakah tanda tangan ini telah dihapus dari dokumen. Properti ini hanya digunakan untuk catatan log riwayat dokumen guna menyimpan daftar tanda tangan yang dihapus. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Menentukan tinggi tanda tangan. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Dapatkan atau atur flag untuk menunjukkan apakah komponen ini adalah Tanda Tangan atau konten dokumen. Properti ini digunakan dengan metode Update untuk menetapkan elemen sebagai tanda tangan (true) atau elemen dokumen (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Menjaga nilai true jika tanda tangan digital ini valid dan dokumen tidak diubah. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Menentukan posisi kiri tanda tangan. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | Nama host CPU atau lokasi fisik penandatanganan. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Dapatkan atau atur tanggal modifikasi tanda tangan. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Menentukan halaman tempat tanda tangan ditemukan. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | Alasan penandatanganan, seperti (Saya setuju). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Paksa untuk menampilkan/menyembunyikan properti tanda tangan. Jika ShowProperties bernilai true, bidang tanda tangan memiliki format tampilan yang telah ditentukan: Ditandatangani secara digital oleh {[`ContactInfo`](./contactinfo)} Tanggal: {Date} Alasan: {[`Reason`](./reason)} Lokasi: {[`Location`](./location)} ShowProperties bernilai true secara default. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Pengidentifikasi tanda tangan unik untuk memodifikasi tanda tangan dalam dokumen melalui metode Update atau Delete. Properti ini akan diatur secara otomatis setelah metode Sign atau Search dipanggil. Jika properti ini telah disimpan sebelumnya, dapat diatur secara manual untuk memanipulasi tanda tangan. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Menentukan tipe tanda tangan. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Mendapatkan atau mengatur waktu dokumen ditandatangani. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Mendapatkan sidik jari sertifikat. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Stempel waktu untuk tanda tangan digital Pdf. Nilai default adalah null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Menentukan posisi atas tanda tangan. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Jenis tanda tangan digital Pdf. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Menentukan lebar tanda tangan. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | Jenis XAdES [`XAdESType`](../digitalsignature/xadestype). Nilai default adalah None (XAdES dimatikan). Saat ini jenis tanda tangan XAdES hanya didukung untuk dokumen Spreadsheet. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Klon instansi Tanda Tangan Barcode. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Menimpa metode GetHashCode |

### Lihat Juga

* class [DigitalSignature](../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
