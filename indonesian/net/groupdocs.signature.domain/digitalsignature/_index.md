---
title: DigitalSignature
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Berisi properti tanda tangan digital.
type: docs
weight: 150
url: /id/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

Berisi properti tanda tangan digital.

```csharp
public class DigitalSignature : BaseSignature
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Inisialisasi tanda tangan digital dengan parameter default. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Inisialisasi Tanda Tangan Digital dengan SignatureId yang diketahui. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Buat tanda tangan digital dengan sertifikat tertentu. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Membuat tanda tangan digital berdasarkan penyimpanan X509 yang ditentukan. Sertifikat pertama dari toko tertentu akan digunakan. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Membuat tanda tangan digital berdasarkan X509 Store dan indeks sertifikat yang ditentukan. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Mendapat atau menyetel sertifikat X509. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Menentukan lokasi penyimpanan sertifikat |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Menentukan nama toko sertifikat. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Mendapat atau menyetel komentar tujuan penandatanganan. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Dapatkan atau tetapkan tanggal pembuatan tanda tangan. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Dapatkan bendera yang menunjukkan jika tanda tangan ini telah dihapus dari dokumen. Properti ini hanya digunakan untuk catatan log riwayat dokumen untuk menyimpan daftar tanda tangan yang dihapus. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Menentukan ketinggian tanda tangan. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Dapatkan atau setel tanda untuk menunjukkan apakah komponen ini adalah Tanda Tangan atau konten dokumen. Properti ini digunakan dengan metode Pembaruan untuk menetapkan elemen sebagai tanda tangan (benar) atau elemen dokumen (salah). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Benar jika tanda tangan digital ini valid dan dokumen tidak dirusak. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Menentukan posisi tanda tangan kiri. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Dapatkan atau tetapkan tanggal modifikasi tanda tangan. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Menentukan tanda tangan halaman ditemukan di. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Pengidentifikasi tanda tangan unik untuk mengubah tanda tangan dalam dokumen melalui metode Perbarui atau Hapus. Properti ini akan disetel secara otomatis setelah metode Tanda Tangan atau Cari dipanggil. Jika properti ini disimpan sebelum dapat disetel secara manual untuk memanipulasi tanda tangan. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Menentukan jenis tanda tangan. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Mendapatkan atau mengatur waktu penandatanganan dokumen. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Mendapat cap jempol sertifikat. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Menentukan posisi teratas tanda tangan. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Menentukan lebar tanda tangan. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | tipe XAdES[`XAdESType`](./xadestype) . Nilai defaultnya adalah Tidak Ada (XAdES tidak aktif). Saat ini jenis tanda tangan XAdES hanya didukung untuk dokumen Spreadsheet. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Contoh Tanda Tangan Kode Batang Kloning. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Menimpa metode Sama dengan untuk membandingkan properti tanda tangan |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Menimpa metode GetHashCode |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Memuat tanda tangan digital dari semua Penyimpanan Sertifikat X509 sistem. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Memuat tanda tangan digital dari Penyimpanan Sertifikat X509. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Memuat tanda tangan digital dari Penyimpanan Sertifikat X509. |

### Lihat juga

* class [BaseSignature](../basesignature)
* ruang nama [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* perakitan [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
