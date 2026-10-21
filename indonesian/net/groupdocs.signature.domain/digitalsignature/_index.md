---
title: "DigitalSignature"
second_title: "Referensi API GroupDocs.Signature untuk .NET"
description: "Berisi properti Digital signature."
type: docs
weight: 150
url: /id/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

Berisi properti Digital signature.

```csharp
public class DigitalSignature : BaseSignature
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Inisialisasi tanda tangan Digital dengan parameter default. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Inisialisasi tanda tangan Digital dengan SignatureId yang diketahui. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Buat tanda tangan Digital dengan sertifikat yang ditentukan. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Buat tanda tangan Digital berdasarkan penyimpanan X509 yang ditentukan. Sertifikat pertama dari penyimpanan yang ditentukan akan digunakan. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Buat tanda tangan Digital berdasarkan Penyimpanan X509 yang ditentukan dan indeks sertifikat. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Mendapatkan atau mengatur sertifikat X509. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Menentukan nama penyimpanan khusus untuk sertifikat. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Menentukan lokasi penyimpanan sertifikat |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Menentukan nama penyimpanan sertifikat. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Mendapatkan atau mengatur komentar tujuan penandatanganan. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Dapatkan atau atur tanggal pembuatan tanda tangan. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Dapatkan flag yang menunjukkan apakah tanda tangan ini telah dihapus dari dokumen. Properti ini hanya digunakan untuk catatan log riwayat dokumen guna menyimpan daftar tanda tangan yang dihapus. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Menentukan tinggi tanda tangan. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Dapatkan atau atur flag untuk menunjukkan apakah komponen ini adalah Tanda Tangan atau konten dokumen. Properti ini digunakan dengan metode Update untuk menetapkan elemen sebagai tanda tangan (true) atau elemen dokumen (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Menjaga nilai true jika tanda tangan digital ini valid dan dokumen tidak diubah. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Menentukan posisi kiri tanda tangan. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Dapatkan atau atur tanggal modifikasi tanda tangan. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Menentukan halaman tempat tanda tangan ditemukan. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Pengidentifikasi tanda tangan unik untuk memodifikasi tanda tangan dalam dokumen melalui metode Update atau Delete. Properti ini akan diatur secara otomatis setelah metode Sign atau Search dipanggil. Jika properti ini telah disimpan sebelumnya, dapat diatur secara manual untuk memanipulasi tanda tangan. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Menentukan tipe tanda tangan. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Mendapatkan atau mengatur waktu dokumen ditandatangani. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Mendapatkan sidik jari sertifikat. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Menentukan posisi atas tanda tangan. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Menentukan lebar tanda tangan. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | Tipe XAdES [`XAdESType`](./xadestype). Nilai default adalah None (XAdES dimatikan). Saat ini tipe tanda tangan XAdES hanya didukung untuk dokumen Spreadsheet. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Klon instansi Tanda Tangan Barcode. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Menimpa metode GetHashCode |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Muat tanda tangan Digital dari semua Penyimpanan Sertifikat X509 sistem. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Muat tanda tangan Digital dari penyimpanan sertifikat. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_3)(string) | Muat tanda tangan Digital dari penyimpanan sertifikat. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Muat tanda tangan Digital dari penyimpanan sertifikat digital yang ditempatkan di lokasi tertentu. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_4)(string, StoreLocation) | Muat tanda tangan Digital dari penyimpanan sertifikat digital yang ditempatkan di lokasi tertentu. |

### Lihat Juga

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
