---
title: "PdfMetadataSignature"
second_title: "Referensi API GroupDocs.Signature untuk .NET"
description: "Berisi properti Pdf Metadata signature."
type: docs
weight: 860
url: /id/net/groupdocs.signature.domain/pdfmetadatasignature/
---
## PdfMetadataSignature class

Berisi properti Pdf Metadata signature.

```csharp
public sealed class PdfMetadataSignature : MetadataSignature
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfMetadataSignature](pdfmetadatasignature#constructor)(string) | Membuat tanda tangan Metadata Pdf dengan nama yang telah ditentukan dan nilai kosong |
| [PdfMetadataSignature](pdfmetadatasignature#constructor_1)(string, object) | Membuat tanda tangan Metadata Pdf dengan nilai yang telah ditentukan |
| [PdfMetadataSignature](pdfmetadatasignature#constructor_2)(string, object, string) | Membuat tanda tangan Metadata Pdf dengan nilai yang telah ditentukan |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Dapatkan atau atur tanggal pembuatan tanda tangan. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Mendapatkan atau mengatur implementasi antarmuka [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) untuk mengenkripsi dan mendekripsi properti Nilai tanda tangan. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Dapatkan flag yang menunjukkan apakah tanda tangan ini telah dihapus dari dokumen. Properti ini hanya digunakan untuk catatan log riwayat dokumen guna menyimpan daftar tanda tangan yang dihapus. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Menentukan tinggi tanda tangan. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Dapatkan atau atur flag untuk menunjukkan apakah komponen ini adalah Tanda Tangan atau konten dokumen. Properti ini digunakan dengan metode Update untuk menetapkan elemen sebagai tanda tangan (true) atau elemen dokumen (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Menentukan posisi kiri tanda tangan. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Dapatkan atau atur tanggal modifikasi tanda tangan. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Menentukan nama metadata unik. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Menentukan halaman tempat tanda tangan ditemukan. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Pengidentifikasi tanda tangan unik untuk memodifikasi tanda tangan dalam dokumen melalui metode Update atau Delete. Properti ini akan diatur secara otomatis setelah metode Sign atau Search dipanggil. Jika properti ini telah disimpan sebelumnya, dapat diatur secara manual untuk memanipulasi tanda tangan. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Menentukan tipe tanda tangan. |
| [TagPrefix](../../groupdocs.signature.domain/pdfmetadatasignature/tagprefix) { get; set; } | Tag awalan nama tanda tangan Metadata Pdf. Secara default properti ini diatur ke \"xmp\". Nilai yang mungkin adalah |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Menentukan posisi atas tanda tangan. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Menentukan tipe nilai metadata. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Menentukan objek metadata. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Menentukan lebar tanda tangan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfmetadatasignature/clone#clone_1)() | Menggandakan instance Tanda Tangan Metadata. |
| override [Clone](../../groupdocs.signature.domain/pdfmetadatasignature/clone#clone)(object) | Menggandakan instance Tanda Tangan Metadata Pdf dengan nilai yang diberikan. |
| override [Equals](../../groupdocs.signature.domain/pdfmetadatasignature/equals)(object) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Mendapatkan objek dari Nilai Tanda Tangan Metadata melalui deserialisasi. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Mendapatkan objek dari Teks Tanda Tangan Metadata melalui deserialisasi. |
| override [GetHashCode](../../groupdocs.signature.domain/pdfmetadatasignature/gethashcode)() | Menimpa metode GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Mengonversi ke boolean. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Mengonversi ke DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Mengonversi ke DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Mengonversi ke Decimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Mengonversi ke Decimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Mengonversi ke Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Mengonversi ke Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Mengonversi ke integer. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Mengonversi ke float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Mengonversi ke float. |
| override [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)() | Mengonversi ke String dengan metode override ToString() |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Mengonversi ke String dengan format yang ditentukan |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string, IFormatProvider) | Mengonversi ke String dengan format yang ditentukan |

### Lihat Juga

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
