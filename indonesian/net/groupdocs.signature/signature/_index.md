---
title: "Signature"
second_title: "Referensi API GroupDocs.Signature untuk .NET"
description: "Mewakili kelas utama yang mengontrol proses penandatanganan dokumen."
type: docs
weight: 2170
url: /id/net/groupdocs.signature/signature/
---
## Signature class

Mewakili kelas utama yang mengontrol proses penandatanganan dokumen.

```csharp
public class Signature : IDisposable
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Menginisialisasi instance baru dari kelas [`Signature`](../signature) dengan dokumen yang disediakan melalui stream. |
| [Signature](signature#constructor_4)(string) | Menginisialisasi instance baru dari kelas [`Signature`](../signature) dengan dokumen yang disediakan melalui jalur file. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Menginisialisasi instance baru dari kelas [`Signature`](../signature) dengan dokumen yang disediakan melalui stream dan opsi pemuatan LoadOptions. |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Menginisialisasi instance baru dari kelas [`Signature`](../signature) dengan dokumen yang disediakan melalui stream dan [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_5)(string, LoadOptions) | Menginisialisasi instance baru dari kelas [`Signature`](../signature) dengan dokumen yang disediakan melalui jalur file dan LoadOptions. |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Menginisialisasi instance baru dari kelas [`Signature`](../signature) dengan dokumen yang disediakan melalui jalur file dan [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Menginisialisasi instance baru dari kelas [`Signature`](../signature) dengan dokumen yang disediakan melalui stream, opsi pemuatan LoadOptions, dan pengaturan [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Menginisialisasi instance baru dari kelas [`Signature`](../signature) dengan dokumen yang disediakan melalui jalur file, LoadOptions, dan [`SignatureSettings`](../signaturesettings). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Menghapus signature [`BaseSignature`](../../groupdocs.signature.domain/basesignature) yang diberikan dari dokumen. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Menghapus daftar signature [`BaseSignature`](../../groupdocs.signature.domain/basesignature) yang diberikan dari dokumen. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Menghapus tanda tangan dari daftar tipe tertentu [`SignatureType`](../../groupdocs.signature.domain/signaturetype) dari dokumen. Hanya tanda tangan yang ditambahkan oleh metode Sign dan ditandai sebagai Signature [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) yang akan dihapus. Tipe tanda tangan yang didukung: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Menghapus daftar signature [`BaseSignature`](../../groupdocs.signature.domain/basesignature) yang diberikan dari dokumen. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Menghapus tanda tangan dari tipe tertentu [`SignatureType`](../../groupdocs.signature.domain/signaturetype) dari dokumen. Hanya tanda tangan yang ditambahkan oleh metode Sign dan ditandai sebagai Signature [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) yang akan dihapus. Tipe tanda tangan yang didukung: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Menghapus tanda tangan berdasarkan Id tanda tangan spesifiknya dari dokumen. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Mengimplementasikan antarmuka IDisposable untuk membersihkan sumber daya internal |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Menghasilkan pratinjau halaman dokumen. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Mendapatkan informasi tentang halaman dokumen: ukuran mereka, tinggi maksimum halaman, lebar halaman dengan tinggi maksimum. |
| [Search](../../groupdocs.signature/signature/search#search_3)(Func&lt;BaseSignature, bool&gt;) | Mencari tanda tangan dalam dokumen menggunakan semua opsi pencarian yang tersedia dan menyaring hasil berdasarkan predikat yang ditentukan. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Mencari tanda tangan dalam dokumen dengan daftar [`SearchOptions`](../../groupdocs.signature.options/searchoptions). |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Mencari jenis tanda tangan yang ditentukan dalam dokumen berdasarkan nilai [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Search](../../groupdocs.signature/signature/search#search_2)(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Mencari tanda tangan dalam dokumen menggunakan opsi pencarian yang disediakan dan menyaring hasil berdasarkan predikat yang ditentukan. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_5)(SearchOptions) | Mencari tanda tangan dalam dokumen dengan opsi [`SearchOptions`](../../groupdocs.signature.options/searchoptions). |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_4)(SignatureType) | Mencari tipe tepat tanda tangan dalam dokumen berdasarkan nilai [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Menandatangani dokumen dengan kumpulan [`SignOptions`](../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Menandatangani dokumen dengan [`SignOptions`](../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Menandatangani dokumen dengan kumpulan [`SignOptions`](../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke jalur file yang ditentukan. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Menandatangani dokumen dengan [`SignOptions`](../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke jalur file yang ditentukan. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Menandatangani dokumen dengan kumpulan [`SignOptions`](../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke stream dengan [`SaveOptions`](../../groupdocs.signature.options/saveoptions) yang telah ditentukan sebelumnya. |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Menandatangani dokumen dengan [`SignOptions`](../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke stream dengan [`SaveOptions`](../../groupdocs.signature.options/saveoptions) yang telah ditentukan sebelumnya. |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Menandatangani dokumen dengan kumpulan [`SignOptions`](../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke jalur file yang ditentukan dengan [`SaveOptions`](../../groupdocs.signature.options/saveoptions) yang telah ditentukan sebelumnya. |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Menandatangani dokumen dengan [`SignOptions`](../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke jalur file yang ditentukan dengan [`SaveOptions`](../../groupdocs.signature.options/saveoptions) yang telah ditentukan sebelumnya. |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Memperbarui tanda tangan [`BaseSignature`](../../groupdocs.signature.domain/basesignature) yang diberikan dalam dokumen. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Memperbarui tanda tangan [`BaseSignature`](../../groupdocs.signature.domain/basesignature) yang diberikan dalam dokumen. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Memverifikasi tanda tangan dokumen dengan daftar data VerifyOptions. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Memverifikasi tanda tangan dokumen dengan data VerifyOptions yang diberikan. |
| [Verify](../../groupdocs.signature/signature/verify#verify_3)(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Memverifikasi tanda tangan dokumen menggunakan semua opsi verifikasi yang tersedia dan menyaring hasil berdasarkan predikat yang ditentukan. Metode ini pertama mencari tanda tangan yang cocok dengan opsi verifikasi, menyaringnya menggunakan predikat, dan kemudian memverifikasi hanya tanda tangan yang telah disaring tersebut. |
| [Verify](../../groupdocs.signature/signature/verify#verify_2)(VerifyOptions, Func&lt;BaseSignature, bool&gt;) | Memverifikasi tanda tangan dokumen menggunakan opsi verifikasi yang disediakan dan menyaring hasil berdasarkan predikat yang ditentukan. Metode ini pertama mencari tanda tangan yang cocok dengan opsi verifikasi, menyaringnya menggunakan predikat, dan kemudian memverifikasi hanya tanda tangan yang telah disaring tersebut. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Menghasilkan pratinjau Signature berdasarkan SignOptions yang diberikan. [`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Acara

| Nama | Deskripsi |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Terjadi ketika proses pencarian tanda tangan selesai. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Terjadi ketika kemajuan proses pencarian tanda tangan berubah. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Terjadi ketika proses pencarian tanda tangan dimulai. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Terjadi ketika proses penandatanganan dokumen selesai. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Terjadi ketika kemajuan proses penandatanganan dokumen berubah. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Terjadi ketika proses penandatanganan dokumen dimulai. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Terjadi ketika proses verifikasi tanda tangan selesai. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Terjadi ketika kemajuan proses verifikasi tanda tangan berubah. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Terjadi ketika proses verifikasi tanda tangan dimulai. |

### Catatan

**Learn more**

Selengkapnya tentang fitur GroupDocs.Signature: [GroupDocs.Signature Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Lihat Juga

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
