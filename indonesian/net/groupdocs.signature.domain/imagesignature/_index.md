---
title: ImageSignature
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Berisi properti tanda tangan Gambar.
type: docs
weight: 590
url: /id/net/groupdocs.signature.domain/imagesignature/
---
## ImageSignature class

Berisi properti tanda tangan Gambar.

```csharp
public class ImageSignature : BaseSignature
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [ImageSignature](imagesignature)(string) | Inisialisasi objek ImageSignature dengan pengenal tanda tangan yang diperoleh setelah proses pencarian. Pengenal unik ini digunakan untuk menemukan properti tambahan untuk tanda tangan ini dari lapisan informasi tanda tangan dokumen. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Content](../../groupdocs.signature.domain/imagesignature/content) { get; } | Menentukan jenis konten data biner gambar[`Format`](./format) . Secara default properti ini tidak akan disetel. Gunakan properti[`ReturnContent`](../../groupdocs.signature.options/imagesearchoptions/returncontent) untuk mengaktifkan fitur ini. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Dapatkan atau tetapkan tanggal pembuatan tanda tangan. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Dapatkan bendera yang menunjukkan jika tanda tangan ini telah dihapus dari dokumen. Properti ini hanya digunakan untuk catatan log riwayat dokumen untuk menyimpan daftar tanda tangan yang dihapus. |
| [Format](../../groupdocs.signature.domain/imagesignature/format) { get; } | Menentukan format gambar tanda tangan. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Menentukan ketinggian tanda tangan. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Dapatkan atau setel tanda untuk menunjukkan apakah komponen ini adalah Tanda Tangan atau konten dokumen. Properti ini digunakan dengan metode Pembaruan untuk menetapkan elemen sebagai tanda tangan (benar) atau elemen dokumen (salah). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Menentukan posisi tanda tangan kiri. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Dapatkan atau tetapkan tanggal modifikasi tanda tangan. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Menentukan tanda tangan halaman ditemukan di. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Pengidentifikasi tanda tangan unik untuk mengubah tanda tangan dalam dokumen melalui metode Perbarui atau Hapus. Properti ini akan disetel secara otomatis setelah metode Tanda Tangan atau Cari dipanggil. Jika properti ini disimpan sebelum dapat disetel secara manual untuk memanipulasi tanda tangan. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Menentukan jenis tanda tangan. |
| [Size](../../groupdocs.signature.domain/imagesignature/size) { get; } | Menentukan ukuran dalam byte gambar tanda tangan. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Menentukan posisi teratas tanda tangan. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Menentukan lebar tanda tangan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagesignature/clone)() | Contoh Tanda Tangan Kode Batang Kloning. |
| override [Equals](../../groupdocs.signature.domain/imagesignature/equals)(object) | Menimpa metode Sama dengan untuk membandingkan properti tanda tangan |
| override [GetHashCode](../../groupdocs.signature.domain/imagesignature/gethashcode)() | Menimpa metode GetHashCode |

### Lihat juga

* class [BaseSignature](../basesignature)
* ruang nama [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* perakitan [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
