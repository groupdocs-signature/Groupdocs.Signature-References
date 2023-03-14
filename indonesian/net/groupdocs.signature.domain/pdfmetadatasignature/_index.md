---
title: PdfMetadataSignature
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Berisi properti tanda tangan Metadata Pdf.
type: docs
weight: 680
url: /id/net/groupdocs.signature.domain/pdfmetadatasignature/
---
## PdfMetadataSignature class

Berisi properti tanda tangan Metadata Pdf.

```csharp
public sealed class PdfMetadataSignature : MetadataSignature
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [PdfMetadataSignature](pdfmetadatasignature#constructor)(string) | Membuat tanda tangan Metadata Pdf dengan nama yang telah ditentukan dan nilai kosong |
| [PdfMetadataSignature](pdfmetadatasignature#constructor_1)(string, object) | Membuat tanda tangan Metadata Pdf dengan nilai yang telah ditentukan |
| [PdfMetadataSignature](pdfmetadatasignature#constructor_2)(string, object, string) | Membuat tanda tangan Metadata Pdf dengan nilai yang telah ditentukan |

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
| [TagPrefix](../../groupdocs.signature.domain/pdfmetadatasignature/tagprefix) { get; set; } | Tag awalan nama tanda tangan Metadata Pdf. Secara default properti ini disetel ke "xmp". Nilai yang mungkin adalah |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Menentukan posisi teratas tanda tangan. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Menentukan jenis nilai metadata. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Menentukan objek metadata. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Menentukan lebar tanda tangan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfmetadatasignature/clone#clone_1)() | Contoh Tanda Tangan Metadata Kloning. |
| override [Clone](../../groupdocs.signature.domain/pdfmetadatasignature/clone#clone)(object) | Clone Pdf Metadata Signature instance dengan nilai yang diberikan. |
| override [Equals](../../groupdocs.signature.domain/pdfmetadatasignature/equals)(object) | Menimpa metode Sama dengan untuk membandingkan properti tanda tangan |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Dapatkan objek dari Nilai Tanda Tangan Metadata melalui deserialisasi. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Dapatkan objek dari Teks Tanda Tangan Metadata melalui deserialisasi. |
| override [GetHashCode](../../groupdocs.signature.domain/pdfmetadatasignature/gethashcode)() | Menimpa metode GetHashCode |
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
| override [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)() | Mengonversi ke String dengan mengganti metode ToString() |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Konversi ke String dengan format yang ditentukan |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string, IFormatProvider) | Konversi ke String dengan format yang ditentukan |

### Lihat juga

* class [MetadataSignature](../metadatasignature)
* ruang nama [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* perakitan [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
