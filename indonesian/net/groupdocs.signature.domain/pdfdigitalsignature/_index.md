---
title: PdfDigitalSignature
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Berisi properti tanda tangan Digital Pdf.
type: docs
weight: 660
url: /id/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Berisi properti tanda tangan Digital Pdf.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Inisialisasi Tanda Tangan Digital Pdf tanpa sertifikat. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Buat Pdf Digital signature dengan sertifikat tertentu. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Inisialisasi Tanda Tangan Digital Pdf berdasarkan toko X509 yang ditentukan. Sertifikat pertama dari toko tertentu akan digunakan. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Membuat Pdf Digital signature berdasarkan X509 Store yang ditentukan dan indeks sertifikat. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Mendapat atau menyetel sertifikat X509. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Menentukan lokasi penyimpanan sertifikat |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Menentukan nama toko sertifikat. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Mendapat atau menyetel komentar tujuan penandatanganan. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Informasi yang diberikan oleh penanda tangan agar penerima dapat menghubungi penanda tangan untuk memverifikasi tanda tangannya, misalnya nomor telepon. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Dapatkan atau tetapkan tanggal pembuatan tanda tangan. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Dapatkan bendera yang menunjukkan jika tanda tangan ini telah dihapus dari dokumen. Properti ini hanya digunakan untuk catatan log riwayat dokumen untuk menyimpan daftar tanda tangan yang dihapus. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Menentukan ketinggian tanda tangan. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Dapatkan atau setel tanda untuk menunjukkan apakah komponen ini adalah Tanda Tangan atau konten dokumen. Properti ini digunakan dengan metode Pembaruan untuk menetapkan elemen sebagai tanda tangan (benar) atau elemen dokumen (salah). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Benar jika tanda tangan digital ini valid dan dokumen tidak dirusak. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Menentukan posisi tanda tangan kiri. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | Nama host CPU atau lokasi fisik penandatanganan. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Dapatkan atau tetapkan tanggal modifikasi tanda tangan. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Menentukan tanda tangan halaman ditemukan di. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | Alasan penandatanganan, seperti (Saya setujuРІР‚В¦). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Paksa untuk menampilkan/menyembunyikan properti tanda tangan. Jika ShowProperties benar bidang signature memiliki format penampilan yang telah ditentukan Ditandatangani secara digital oleh {[`ContactInfo`](./contactinfo)} Tanggal: {Tanggal} Alasan: {[`Reason`](./reason)} Lokasi: {[`Location`](./location) } ShowProperties benar secara default. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Pengidentifikasi tanda tangan unik untuk mengubah tanda tangan dalam dokumen melalui metode Perbarui atau Hapus. Properti ini akan disetel secara otomatis setelah metode Tanda Tangan atau Cari dipanggil. Jika properti ini disimpan sebelum dapat disetel secara manual untuk memanipulasi tanda tangan. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Menentukan jenis tanda tangan. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Mendapatkan atau mengatur waktu penandatanganan dokumen. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Mendapat cap jempol sertifikat. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Stempel waktu untuk tanda tangan digital Pdf. Nilai default adalah null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Menentukan posisi teratas tanda tangan. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Jenis tanda tangan digital Pdf. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Menentukan lebar tanda tangan. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | tipe XAdES[`XAdESType`](../digitalsignature/xadestype) . Nilai defaultnya adalah Tidak Ada (XAdES tidak aktif). Saat ini jenis tanda tangan XAdES hanya didukung untuk dokumen Spreadsheet. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Contoh Tanda Tangan Kode Batang Kloning. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Menimpa metode Sama dengan untuk membandingkan properti tanda tangan |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Menimpa metode GetHashCode |

### Lihat juga

* class [DigitalSignature](../digitalsignature)
* ruang nama [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* perakitan [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
