---
title: "ImageMetadataSignature"
second_title: "Referensi API GroupDocs.Signature untuk .NET"
description: "Berisi properti signature Image Metadata."
type: docs
weight: 740
url: /id/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Berisi properti signature Image Metadata.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Membuat Image Metadata Signature dengan Id dan nilai. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Dapatkan atau atur tanggal pembuatan tanda tangan. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Mendapatkan atau mengatur implementasi antarmuka [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) untuk mengenkripsi dan mendekripsi properti Nilai tanda tangan. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Dapatkan flag yang menunjukkan apakah tanda tangan ini telah dihapus dari dokumen. Properti ini hanya digunakan untuk catatan log riwayat dokumen guna menyimpan daftar tanda tangan yang dihapus. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Nilai baca-saja untuk mendapatkan deskripsi bagi Image Metadata signature standar. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Menentukan tinggi tanda tangan. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | Pengidentifikasi tanda tangan Image Metadata. Lihat kelas ImageMetadataSignatures yang berisi Signature standar dengan nilai Id yang telah ditentukan. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Dapatkan atau atur flag untuk menunjukkan apakah komponen ini adalah Tanda Tangan atau konten dokumen. Properti ini digunakan dengan metode Update untuk menetapkan elemen sebagai tanda tangan (true) atau elemen dokumen (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Menentukan posisi kiri tanda tangan. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Dapatkan atau atur tanggal modifikasi tanda tangan. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Menentukan nama metadata unik. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Menentukan halaman tempat tanda tangan ditemukan. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Pengidentifikasi tanda tangan unik untuk memodifikasi tanda tangan dalam dokumen melalui metode Update atau Delete. Properti ini akan diatur secara otomatis setelah metode Sign atau Search dipanggil. Jika properti ini telah disimpan sebelumnya, dapat diatur secara manual untuk memanipulasi tanda tangan. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Menentukan tipe tanda tangan. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Nilai hanya-baca untuk mendapatkan ukuran nilai Metadata |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Menentukan posisi atas tanda tangan. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Menentukan tipe nilai metadata. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Menentukan objek metadata. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Menentukan lebar tanda tangan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Menggandakan instance Tanda Tangan Metadata. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Kloning instance Image Metadata Signature dengan nilai yang diberikan. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Mendapatkan objek dari Nilai Tanda Tangan Metadata melalui deserialisasi. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Mendapatkan objek dari Teks Tanda Tangan Metadata melalui deserialisasi. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | Menimpa metode GetHashCode |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Mengonversi ke boolean. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Mengonversi ke DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Mengonversi ke DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Mengonversi ke Decimal. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Mengonversi ke Decimal. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Mengonversi ke Double. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Mengonversi ke Double. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Mengonversi ke integer. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Mengonversi ke long. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Mengonversi ke float. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Mengonversi ke float. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Mengonversi ke String dengan metode override ToString() |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Mengonversi ke String dengan format yang ditentukan |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Mengonversi ke String dengan format yang ditentukan |

### Lihat Juga

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
