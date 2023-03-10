---
title: Signature
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Mewakili kelas utama yang mengontrol proses penandatanganan dokumen.
type: docs
weight: 1880
url: /id/net/groupdocs.signature/signature/
---
## Signature class

Mewakili kelas utama yang mengontrol proses penandatanganan dokumen.

```csharp
public class Signature : IDisposable
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Menginisialisasi instance baru[`Signature`](../signature) kelas dengan dokumen yang disediakan oleh aliran. |
| [Signature](signature#constructor_4)(string) | Menginisialisasi instance baru[`Signature`](../signature) instance kelas dengan dokumen yang disediakan oleh file path. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Menginisialisasi instance baru[`Signature`](../signature) kelas dengan dokumen yang disediakan oleh opsi streaming dan muatLoadOptions . |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Menginisialisasi instance baru[`Signature`](../signature)instance kelas dengan dokumen yang disediakan oleh aliran dan[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_5)(string, LoadOptions) | Menginisialisasi instance baru[`Signature`](../signature) instance kelas dengan dokumen yang disediakan oleh jalur file danLoadOptions . |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Menginisialisasi instance baru[`Signature`](../signature) instance kelas dengan dokumen yang disediakan oleh jalur file dan[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Menginisialisasi instance baru[`Signature`](../signature) instance kelas dengan dokumen yang disediakan oleh aliran, memuat opsiLoadOptions dan pengaturan[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Menginisialisasi instance baru[`Signature`](../signature) instance kelas dengan dokumen yang disediakan oleh jalur file,LoadOptions Dan[`SignatureSettings`](../signaturesettings) . |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Menghapus tanda tangan yang diberikan[`BaseSignature`](../../groupdocs.signature.domain/basesignature) dari dokumen. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Menghapus daftar tanda tangan yang lulus[`BaseSignature`](../../groupdocs.signature.domain/basesignature) dari dokumen. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Menghapus tanda tangan dari daftar jenis tertentu[`SignatureType`](../../groupdocs.signature.domain/signaturetype) dari dokumen. Hanya tanda tangan yang ditambahkan dengan metode Sign dan ditandai sebagai Tanda Tangan[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) akan dihapus. Jenis tanda tangan berikut didukung: Teks, Gambar, Digital, Kode Batang, Kode QR |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Menghapus daftar tanda tangan yang lulus[`BaseSignature`](../../groupdocs.signature.domain/basesignature) dari dokumen. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Menghapus tanda tangan dari jenis tertentu[`SignatureType`](../../groupdocs.signature.domain/signaturetype) dari dokumen. Hanya tanda tangan yang ditambahkan dengan metode Sign dan ditandai sebagai Tanda Tangan[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) akan dihapus. Jenis tanda tangan berikut didukung: Teks, Gambar, Digital, Kode Batang, Kode QR |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Menghapus tanda tangan dengan ID tanda tangan spesifiknya dari dokumen. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Terapkan antarmuka IDisposable untuk membersihkan sumber daya internal |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Menghasilkan pratinjau halaman dokumen. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Mendapat informasi tentang halaman dokumen: ukurannya, tinggi halaman maksimum, lebar halaman dengan tinggi maksimum. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Mencari tanda tangan dalam dokumen menurut[`SearchOptions`](../../groupdocs.signature.options/searchoptions) daftar. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Mencari jenis tanda tangan tertentu dalam dokumen menurut[`SignatureType`](../../groupdocs.signature.domain/signaturetype) nilai. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_3)(SearchOptions) | Mencari tanda tangan dalam dokumen menurut[`SearchOptions`](../../groupdocs.signature.options/searchoptions) opsi. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_2)(SignatureType) | Mencari jenis tanda tangan yang tepat dalam dokumen menurut[`SignatureType`](../../groupdocs.signature.domain/signaturetype) nilai. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Menandatangani dokumen dengan koleksi[`SignOptions`](../../groupdocs.signature.options/signoptions) dan simpan hasilnya ke aliran. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Menandatangani dokumen dengan[`SignOptions`](../../groupdocs.signature.options/signoptions) dan simpan hasilnya ke aliran. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Menandatangani dokumen dengan koleksi[`SignOptions`](../../groupdocs.signature.options/signoptions) dan simpan hasilnya ke jalur file yang ditentukan. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Menandatangani dokumen dengan[`SignOptions`](../../groupdocs.signature.options/signoptions) dan simpan hasilnya ke jalur file yang ditentukan. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Menandatangani dokumen dengan koleksi[`SignOptions`](../../groupdocs.signature.options/signoptions)dan menyimpan hasil ke aliran dengan standar[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Menandatangani dokumen dengan[`SignOptions`](../../groupdocs.signature.options/signoptions)dan menyimpan hasil ke aliran dengan standar[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Menandatangani dokumen dengan koleksi[`SignOptions`](../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke jalur file yang ditentukan dengan yang telah ditentukan sebelumnya[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Menandatangani dokumen dengan[`SignOptions`](../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke jalur file yang ditentukan dengan yang telah ditentukan sebelumnya[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Pembaruan melewati tanda tangan[`BaseSignature`](../../groupdocs.signature.domain/basesignature) dalam dokumen. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Pembaruan melewati tanda tangan[`BaseSignature`](../../groupdocs.signature.domain/basesignature) dalam dokumen. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Memverifikasi tanda tangan dokumen dengan daftar data VerifyOptions. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Memverifikasi tanda tangan dokumen dengan data VerifyOptions yang diberikan. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Menghasilkan pratinjau Tanda Tangan berdasarkan SignOptions yang diberikan.[`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Acara

| Nama | Keterangan |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Terjadi saat proses pencarian signature selesai. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Terjadi saat progres proses pencarian tanda tangan berubah. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Terjadi saat proses pencarian tanda tangan dimulai. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Terjadi saat proses penandatanganan dokumen selesai. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Terjadi saat progres proses penandatanganan dokumen berubah. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Terjadi saat proses penandatanganan dokumen dimulai. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Terjadi saat proses verifikasi tanda tangan selesai. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Terjadi saat progres proses verifikasi tanda tangan berubah. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Terjadi saat proses verifikasi tanda tangan dimulai. |

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang fitur GroupDocs.Signature: [Panduan Pengembang GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Lihat juga

* ruang nama [GroupDocs.Signature](../../groupdocs.signature)
* perakitan [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
