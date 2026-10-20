---
title: "VerifyOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Menyimpan opsi untuk memverifikasi dokumen."
type: docs
weight: 15
url: /id/java/com.groupdocs.signature.options.verify/verifyoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class VerifyOptions
```

Menyimpan opsi untuk memverifikasi dokumen.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isValid()](#isValid--) | Bendera properti yang valid. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Bendera properti yang valid. |
|
|  | [getPageNumber()](#getPageNumber--) | Nomor Halaman Dokumen yang akan diverifikasi. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Nomor Halaman Dokumen yang akan diverifikasi. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Opsi Halaman untuk menentukan halaman yang akan diverifikasi. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Opsi Halaman untuk menentukan halaman yang akan diverifikasi. |
|
|  | [getAllPages()](#getAllPages--) | Bendera untuk memverifikasi setiap halaman dokumen. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Bendera untuk memverifikasi setiap halaman dokumen. |
|
|  | [getExtensions()](#getExtensions--) | Ekstensi tambahan untuk verifikasi opsi tanda tangan alternatif. |
|
|  | [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | Ekstensi tambahan untuk verifikasi opsi tanda tangan alternatif. |
|
|  | [toString()](#toString--) | Timpa konversi string. |
|
### isValid() {#isValid--}
```
public final boolean isValid()
```


Bendera properti yang valid.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Bendera properti yang valid.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Nomor Halaman Dokumen yang akan diverifikasi. Jika properti tidak diatur - semua Halaman dari
Dokumen akan diverifikasi untuk kemunculan pertama.
Nilai minimal adalah 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


Nomor Halaman Dokumen yang akan diverifikasi. Jika properti tidak diatur - semua Halaman dari
Dokumen akan diverifikasi untuk kemunculan pertama.
Nilai minimal adalah 1.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Opsi Halaman untuk menentukan halaman yang akan diverifikasi.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Opsi Halaman untuk menentukan halaman yang akan diverifikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Bendera untuk memverifikasi setiap halaman dokumen. Secara default nilai adalah true.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Bendera untuk memverifikasi setiap halaman dokumen. Secara default nilai adalah true.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


Ekstensi tambahan untuk verifikasi opsi tanda tangan alternatif.


**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


Ekstensi tambahan untuk verifikasi opsi tanda tangan alternatif.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


Timpa konversi string.


**Returns:**
java.lang.String -
