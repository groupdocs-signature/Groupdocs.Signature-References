---
title: QrCodeSignature
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Berisi properti tanda tangan kode QR.
type: docs
weight: 790
url: /id/net/groupdocs.signature.domain/qrcodesignature/
---
## QrCodeSignature class

Berisi properti tanda tangan kode QR.

```csharp
public class QrCodeSignature : BaseSignature
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [QrCodeSignature](qrcodesignature)(string) | Inisialisasi objek QrCodeSignature dengan signature identifier yang didapatkan setelah proses pencarian. Unique identifier ini digunakan untuk mencari properti tambahan untuk signature ini dari layer informasi signature dokumen. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Content](../../groupdocs.signature.domain/qrcodesignature/content) { get; } | Menentukan jenis konten gambar data biner kode QR[`Format`](./format) . Secara default properti ini tidak akan disetel. Gunakan properti[`ReturnContent`](../../groupdocs.signature.options/qrcodesearchoptions/returncontent) untuk mengaktifkan fitur ini. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Dapatkan atau tetapkan tanggal pembuatan tanda tangan. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Dapatkan bendera yang menunjukkan jika tanda tangan ini telah dihapus dari dokumen. Properti ini hanya digunakan untuk catatan log riwayat dokumen untuk menyimpan daftar tanda tangan yang dihapus. |
| [EncodeType](../../groupdocs.signature.domain/qrcodesignature/encodetype) { get; } | Menentukan Jenis Enkode kode QR. |
| [Format](../../groupdocs.signature.domain/qrcodesignature/format) { get; } | Menentukan format gambar tanda tangan kode QR. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Menentukan ketinggian tanda tangan. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Dapatkan atau setel tanda untuk menunjukkan apakah komponen ini adalah Tanda Tangan atau konten dokumen. Properti ini digunakan dengan metode Pembaruan untuk menetapkan elemen sebagai tanda tangan (benar) atau elemen dokumen (salah). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Menentukan posisi tanda tangan kiri. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Dapatkan atau tetapkan tanggal modifikasi tanda tangan. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Menentukan tanda tangan halaman ditemukan di. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Pengidentifikasi tanda tangan unik untuk mengubah tanda tangan dalam dokumen melalui metode Perbarui atau Hapus. Properti ini akan disetel secara otomatis setelah metode Tanda Tangan atau Cari dipanggil. Jika properti ini disimpan sebelum dapat disetel secara manual untuk memanipulasi tanda tangan. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Menentukan jenis tanda tangan. |
| [Text](../../groupdocs.signature.domain/qrcodesignature/text) { get; } | Menentukan teks kode QR. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Menentukan posisi teratas tanda tangan. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Menentukan lebar tanda tangan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/qrcodesignature/clone)() | Kloning contoh Tanda Tangan Kode QR. |
| override [Equals](../../groupdocs.signature.domain/qrcodesignature/equals)(object) | Menimpa metode Sama dengan untuk membandingkan properti tanda tangan |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/qrcodesignature/getdata#getdata)() | Dapatkan objek dari Teks Tanda Tangan Kode QR melalui deserialisasi. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/qrcodesignature/getdata#getdata_1)(IDataEncryption) | Dapatkan objek dari Teks Tanda Tangan Kode QR melalui deserialisasi. |
| override [GetHashCode](../../groupdocs.signature.domain/qrcodesignature/gethashcode)() | Menimpa metode GetHashCode |

### Lihat juga

* class [BaseSignature](../basesignature)
* ruang nama [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* perakitan [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
