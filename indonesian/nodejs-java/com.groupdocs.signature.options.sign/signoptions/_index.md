---
title: "SignOptions"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Mewakili opsi tanda tangan."
type: docs
weight: 16
url: /id/nodejs-java/com.groupdocs.signature.options.sign/signoptions/
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
| [getPageNumber()](#getPageNumber--) | Mendapatkan atau mengatur nomor halaman dokumen untuk penandatanganan. |
| [setPageNumber(int value)](#setPageNumber-int-) | Mendapatkan atau mengatur nomor halaman dokumen untuk penandatanganan. |
| [getAllPages()](#getAllPages--) | Menempatkan tanda tangan pada semua halaman dokumen. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | Menempatkan tanda tangan pada semua halaman dokumen. |
| [getAppearance()](#getAppearance--) | Penampilan tanda tangan tambahan. |
| [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | Penampilan tanda tangan tambahan. |
| [getExtensions()](#getExtensions--) | Ekstensi Tanda Tangan. |
| [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | Ekstensi Tanda Tangan. |
| [getPagesSetup()](#getPagesSetup--) | Opsi untuk menentukan halaman yang akan ditandatangani. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Opsi untuk menentukan halaman yang akan ditandatangani. |
| [getSignatureType()](#getSignatureType--) | Dapatkan Tipe Tanda Tangan [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
| [getDocumentType()](#getDocumentType--) | Dapatkan atau atur Tipe Dokumen dari Opsi Tanda Tangan [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
| [setDocumentType(int value)](#setDocumentType-int-) | Dapatkan atau atur Tipe Dokumen dari Opsi Tanda Tangan [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
| [getZOrder()](#getZOrder--) | Mendapatkan atau mengatur posisi Z-order dari tanda tangan teks. |
| [setZOrder(int value)](#setZOrder-int-) | Mendapatkan atau mengatur posisi Z-order dari tanda tangan teks. |
| [toString()](#toString--) | Timpa konversi string. |
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Mendapatkan atau mengatur nomor halaman dokumen untuk penandatanganan. Nilai minimal dan default adalah 1.

**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Mendapatkan atau mengatur nomor halaman dokumen untuk penandatanganan. Nilai minimal dan default adalah 1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


Menempatkan tanda tangan pada semua halaman dokumen.

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


Menempatkan tanda tangan pada semua halaman dokumen.

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


Mendapatkan atau mengatur posisi Z-order tanda teks. Menentukan urutan tampilan tanda yang tumpang tindih.

**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


Mendapatkan atau mengatur posisi Z-order tanda teks. Menentukan urutan tampilan tanda yang tumpang tindih.

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
