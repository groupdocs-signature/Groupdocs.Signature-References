---
title: "ImageSearchOptions"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Mewakili opsi pencarian untuk tanda tangan Gambar."
type: docs
weight: 14
url: /id/nodejs-java/com.groupdocs.signature.options.search/imagesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class ImageSearchOptions extends SearchOptions
```

Mewakili opsi pencarian untuk tanda tangan Gambar.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ImageSearchOptions()](#ImageSearchOptions--) | Menginisialisasi instance baru dari kelas ImageSearchOptions dengan nilai default. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getReturnContent()](#getReturnContent--) | Mendapatkan atau mengatur flag untuk mengambil konten gambar tanda tangan pada halaman dokumen. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Mendapatkan atau mengatur flag untuk mengambil konten gambar tanda tangan pada halaman dokumen. |
| [getMinContentSize()](#getMinContentSize--) | Untuk nilai bukan nol, flag ini menentukan ukuran minimal gambar untuk kriteria pencarian. |
| [setMinContentSize(long value)](#setMinContentSize-long-) | Untuk nilai bukan nol, flag ini menentukan ukuran minimal gambar untuk kriteria pencarian. |
| [getMaxContentSize()](#getMaxContentSize--) | Untuk nilai bukan nol, flag ini menentukan ukuran maksimal gambar untuk kriteria pencarian. |
| [setMaxContentSize(long value)](#setMaxContentSize-long-) | Untuk nilai bukan nol, flag ini menentukan ukuran maksimal gambar untuk kriteria pencarian. |
| [getReturnContentType()](#getReturnContentType--) | Menentukan tipe file dari konten yang dikembalikan dari tanda tangan gambar ketika properti ReturnContent diaktifkan. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Menentukan tipe file dari konten yang dikembalikan dari tanda tangan gambar ketika properti ReturnContent diaktifkan. |
### ImageSearchOptions() {#ImageSearchOptions--}
```
public ImageSearchOptions()
```


Menginisialisasi instance baru dari kelas ImageSearchOptions dengan nilai default.

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Mendapatkan atau mengatur flag untuk mengambil konten gambar tanda tangan pada halaman dokumen. Jika flag ini diatur ke true, konten tanda tangan gambar akan mempertahankan data gambar mentah dengan format yang diperlukan ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Secara default opsi ini dinonaktifkan.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Mendapatkan atau mengatur flag untuk mengambil konten gambar tanda tangan pada halaman dokumen. Jika flag ini diatur ke true, konten tanda tangan gambar akan mempertahankan data gambar mentah dengan format yang diperlukan ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Secara default opsi ini dinonaktifkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getMinContentSize() {#getMinContentSize--}
```
public final long getMinContentSize()
```


Untuk nilai bukan nol, flag ini menentukan ukuran minimal gambar untuk kriteria pencarian. Secara default flag ini diatur ke nol dan tidak memengaruhi hasil pencarian.

**Returns:**
long
### setMinContentSize(long value) {#setMinContentSize-long-}
```
public final void setMinContentSize(long value)
```


Untuk nilai bukan nol, flag ini menentukan ukuran minimal gambar untuk kriteria pencarian. Secara default flag ini diatur ke nol dan tidak memengaruhi hasil pencarian.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### getMaxContentSize() {#getMaxContentSize--}
```
public final long getMaxContentSize()
```


Untuk nilai bukan nol, flag ini menentukan ukuran maksimal gambar untuk kriteria pencarian. Secara default flag ini diatur ke nol dan tidak memengaruhi hasil pencarian.

**Returns:**
long
### setMaxContentSize(long value) {#setMaxContentSize-long-}
```
public final void setMaxContentSize(long value)
```


Untuk nilai bukan nol, flag ini menentukan ukuran maksimal gambar untuk kriteria pencarian. Secara default flag ini diatur ke nol dan tidak memengaruhi hasil pencarian.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Menentukan tipe file dari konten yang dikembalikan dari tanda tangan gambar ketika properti ReturnContent diaktifkan. Secara default diatur ke Null. Itu berarti mengembalikan konten gambar dalam format asli. Format gambar ini ditentukan pada ImageSignature.Format. Nilai yang didukung antara lain: FileType.JPEG, FileType.PNG, FileType.BMP. Jika format yang diberikan tidak didukung, maka konten gambar dalam format asli akan dikembalikan.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Menentukan tipe file dari konten yang dikembalikan dari tanda tangan gambar ketika properti ReturnContent diaktifkan. Secara default diatur ke Null. Itu berarti mengembalikan konten gambar dalam format asli. Format gambar ini ditentukan pada ImageSignature.Format. Nilai yang didukung antara lain: FileType.JPEG, FileType.PNG, FileType.BMP. Jika format yang diberikan tidak didukung, maka konten gambar dalam format asli akan dikembalikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

