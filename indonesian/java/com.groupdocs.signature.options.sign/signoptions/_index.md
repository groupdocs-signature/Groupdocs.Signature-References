---
title: "SignOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mewakili opsi tanda tangan."
type: docs
weight: 16
url: /id/java/com.groupdocs.signature.options.sign/signoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SignOptions
```

Mewakili opsi tanda tangan.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Mengambil atau mengatur nomor halaman dokumen untuk penandatanganan. |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Mengambil atau mengatur nomor halaman dokumen untuk penandatanganan. |
|
|  | [getAllPages()](#getAllPages--) | Letakkan tanda tangan pada semua halaman dokumen. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Letakkan tanda tangan pada semua halaman dokumen. |
|
|  | [getAppearance()](#getAppearance--) | Penampilan tanda tangan tambahan. |
|
|  | [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | Penampilan tanda tangan tambahan. |
|
|  | [getExtensions()](#getExtensions--) | Ekstensi Tanda Tangan. |
|
|  | [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | Ekstensi Tanda Tangan. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Opsi untuk menentukan halaman yang akan ditandatangani. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Opsi untuk menentukan halaman yang akan ditandatangani. |
|
|  | [getSignatureType()](#getSignatureType--) | Dapatkan Tipe Tanda Tangan [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
|
|  | [getDocumentType()](#getDocumentType--) | Dapatkan atau atur Tipe Dokumen dari Opsi Tanda Tangan [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [setDocumentType(int value)](#setDocumentType-int-) | Dapatkan atau atur Tipe Dokumen dari Opsi Tanda Tangan [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [getZOrder()](#getZOrder--) | Mengambil atau mengatur posisi Z-order dari tanda tangan teks. |
|
|  | [setZOrder(int value)](#setZOrder-int-) | Mengambil atau mengatur posisi Z-order dari tanda tangan teks. |
|
|  | [getHashAlgorithm()](#getHashAlgorithm--) | Mendapatkan atau mengatur algoritma hash yang akan digunakan untuk operasi kriptografi. |
|
|  | [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | Mendapatkan atau mengatur algoritma hash yang akan digunakan untuk operasi kriptografi. |
|
|  | [toString()](#toString--) | Timpa konversi string. |
|
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Mengambil atau mengatur nomor halaman dokumen untuk penandatanganan.
Nilai minimal dan default adalah 1.


**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Mengambil atau mengatur nomor halaman dokumen untuk penandatanganan.
Nilai minimal dan default adalah 1.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


Letakkan tanda tangan pada semua halaman dokumen.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


Letakkan tanda tangan pada semua halaman dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


Penampilan tanda tangan tambahan.


**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


Penampilan tanda tangan tambahan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


Ekstensi Tanda Tangan.


**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


Ekstensi Tanda Tangan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Opsi untuk menentukan halaman yang akan ditandatangani.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Opsi untuk menentukan halaman yang akan ditandatangani.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Dapatkan Tipe Tanda Tangan [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)


**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


Dapatkan atau atur Tipe Dokumen dari Opsi Tanda Tangan [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


Dapatkan atau atur Tipe Dokumen dari Opsi Tanda Tangan [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


Mengambil atau mengatur posisi Z-order dari tanda tangan teks.
Menentukan urutan tampilan tanda tangan yang tumpang tindih.


**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


Mengambil atau mengatur posisi Z-order dari tanda tangan teks.
Menentukan urutan tampilan tanda tangan yang tumpang tindih.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getHashAlgorithm() {#getHashAlgorithm--}
```
public final int getHashAlgorithm()
```


Mendapatkan atau mengatur algoritma hash yang akan digunakan untuk operasi kriptografi.
Didukung secara eksklusif untuk tanda tangan digital dalam file PDF.
Nilai adalah salah satu konstanta pada [HashAlgorithm](../../com.groupdocs.signature.domain.enums/hashalgorithm).


**Returns:**
int
### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


Mendapatkan atau mengatur algoritma hash yang akan digunakan untuk operasi kriptografi.
Didukung secara eksklusif untuk tanda tangan digital dalam file PDF.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### toString() {#toString--}
```
public String toString()
```


Timpa konversi string.


**Returns:**
java.lang.String -
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
