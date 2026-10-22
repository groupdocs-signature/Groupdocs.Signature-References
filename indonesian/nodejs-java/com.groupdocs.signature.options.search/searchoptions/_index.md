---
title: "SearchOptions"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Mewakili opsi ekstraksi tanda tangan dari dokumen."
type: docs
weight: 17
url: /id/nodejs-java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)
```
public abstract class SearchOptions extends OptionsExtensions
```

Mewakili opsi ekstraksi tanda tangan dari dokumen.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | Mendapatkan atau mengatur nomor halaman Dokumen untuk pencarian. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Mendapatkan atau mengatur nomor halaman Dokumen untuk pencarian. |
| [getPagesSetup()](#getPagesSetup--) | Opsi untuk menentukan halaman untuk pencarian Tanda Tangan. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Opsi untuk menentukan halaman untuk pencarian Tanda Tangan. |
| [getAllPages()](#getAllPages--) | Penanda untuk mencari pada setiap halaman Dokumen. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | Penanda untuk mencari pada setiap halaman Dokumen. |
| [getSkipExternal()](#getSkipExternal--) | Penanda untuk mengembalikan hanya tanda tangan yang ditandai sebagai IsSignature. |
| [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | Penanda untuk mengembalikan hanya tanda tangan yang ditandai sebagai IsSignature. |
| [getSearchPages(int totalPages)](#getSearchPages-int-) | Metode virtual untuk mendapatkan daftar halaman untuk ekstraksi Tanda Tangan. |
| [toString()](#toString--) | Timpa konversi string. |
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Mendapatkan atau mengatur nomor halaman Dokumen untuk pencarian. Nilai bersifat opsional.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Mendapatkan atau mengatur nomor halaman Dokumen untuk pencarian. Nilai bersifat opsional.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Opsi untuk menentukan halaman untuk pencarian Tanda Tangan.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Opsi untuk menentukan halaman untuk pencarian Tanda Tangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Penanda untuk mencari pada setiap halaman Dokumen. Secara default nilai ini diatur ke true.

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Penanda untuk mencari pada setiap halaman Dokumen. Secara default nilai ini diatur ke true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


Penanda untuk mengembalikan hanya tanda tangan yang ditandai sebagai IsSignature. Secara default nilai adalah false yang menunjukkan untuk mengembalikan semua tanda tangan yang cocok dengan kriteria yang ditentukan.

**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


Penanda untuk mengembalikan hanya tanda tangan yang ditandai sebagai IsSignature. Secara default nilai adalah false yang menunjukkan untuk mengembalikan semua tanda tangan yang cocok dengan kriteria yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


Metode virtual untuk mendapatkan daftar halaman untuk ekstraksi Tanda Tangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| totalPages | int | Jumlah total halaman |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Daftar nomor halaman
### toString() {#toString--}
```
public String toString()
```


Timpa konversi string.

**Returns:**
java.lang.String -
