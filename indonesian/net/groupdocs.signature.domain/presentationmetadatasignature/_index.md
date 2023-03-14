---
title: PresentationMetadataSignature
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Berisi properti tanda tangan metadata Presentation.
type: docs
weight: 740
url: /id/net/groupdocs.signature.domain/presentationmetadatasignature/
---
## PresentationMetadataSignature class

Berisi properti tanda tangan metadata Presentation.

```csharp
public sealed class PresentationMetadataSignature : MetadataSignature
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [PresentationMetadataSignature](presentationmetadatasignature#constructor)(string) | Membuat Tanda Tangan Metadata Presentasi dengan nama yang telah ditentukan dan nilai kosong |
| [PresentationMetadataSignature](presentationmetadatasignature#constructor_1)(string, object) | Membuat Tanda Tangan Metadata Presentasi dengan nilai yang telah ditentukan |

## Properti

| Nama | Keterangan |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Dapatkan atau tetapkan tanggal pembuatan tanda tangan. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Mendapatkan atau menetapkan implementasi dari[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) antarmuka untuk menyandikan dan mendekode properti Nilai tanda tangan. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Dapatkan bendera yang menunjukkan jika tanda tangan ini telah dihapus dari dokumen. Properti ini hanya digunakan untuk catatan log riwayat dokumen untuk menyimpan daftar tanda tangan yang dihapus. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Menentukan ketinggian tanda tangan. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Dapatkan atau setel tanda untuk menunjukkan apakah komponen ini adalah Tanda Tangan atau konten dokumen. Properti ini digunakan dengan metode Pembaruan untuk menetapkan elemen sebagai tanda tangan (benar) atau elemen dokumen (salah). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Menentukan posisi tanda tangan kiri. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Dapatkan atau tetapkan tanggal modifikasi tanda tangan. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Menentukan nama metadata yang unik. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Menentukan tanda tangan halaman ditemukan di. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Pengidentifikasi tanda tangan unik untuk mengubah tanda tangan dalam dokumen melalui metode Perbarui atau Hapus. Properti ini akan disetel secara otomatis setelah metode Tanda Tangan atau Cari dipanggil. Jika properti ini disimpan sebelum dapat disetel secara manual untuk memanipulasi tanda tangan. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Menentukan jenis tanda tangan. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Menentukan posisi teratas tanda tangan. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Menentukan jenis nilai metadata. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Menentukan objek metadata. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Menentukan lebar tanda tangan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/presentationmetadatasignature/clone#clone_1)() | Contoh Tanda Tangan Metadata Kloning. |
| override [Clone](../../groupdocs.signature.domain/presentationmetadatasignature/clone#clone)(object) | Contoh Tanda Tangan Metadata Slide Kloning dengan nilai yang diberikan. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Menimpa metode Sama dengan untuk membandingkan properti tanda tangan |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Dapatkan objek dari Nilai Tanda Tangan Metadata melalui deserialisasi. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Dapatkan objek dari Teks Tanda Tangan Metadata melalui deserialisasi. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Menimpa metode GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Konversi ke boolean. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Konversi ke DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Konversi ke DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Konversi ke Desimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Konversi ke Desimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Ubah menjadi Ganda. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Ubah menjadi Ganda. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Mengonversi ke bilangan bulat. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Ubah menjadi float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Ubah menjadi float. |
| override [ToString](../../groupdocs.signature.domain/presentationmetadatasignature/tostring#tostring)() | Mengonversi ke String dengan mengganti metode ToString() |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Konversi ke String dengan format yang ditentukan |
| override [ToString](../../groupdocs.signature.domain/presentationmetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Konversi ke String dengan format yang ditentukan |

### Lihat juga

* class [MetadataSignature](../metadatasignature)
* ruang nama [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* perakitan [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
