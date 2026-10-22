---
title: "ImageSignature"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Berisi properti Image signature."
type: docs
weight: 14
url: /id/nodejs-java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

Berisi properti Image signature.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | Inisialisasi objek ImageSignature dengan pengidentifikasi tanda tangan yang diperoleh setelah proses pencarian. |
| [ImageSignature()](#ImageSignature--) | Inisialisasi ImageSignature dengan parameter default. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSize()](#getSize--) | Menentukan ukuran dalam byte gambar tanda tangan. |
| [setSize(int value)](#setSize-int-) | Menentukan ukuran dalam byte gambar tanda tangan. |
| [getFormat()](#getFormat--) | Menentukan format gambar tanda tangan. |
| [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | Menentukan format gambar tanda tangan. |
| [getContent()](#getContent--) | Menentukan konten data biner gambar dengan tipe Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
| [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
| [deepClone()](#deepClone--) | Klon instance Tanda Tangan Barcode. |
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


Inisialisasi objek ImageSignature dengan pengidentifikasi tanda tangan yang diperoleh setelah proses pencarian. Pengidentifikasi unik ini digunakan untuk menemukan properti tambahan untuk tanda tangan ini dari lapisan informasi tanda tangan dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signatureId | java.lang.String | Pengidentifikasi tanda tangan unik yang diperoleh melalui metode Sign atau Search dari kelas Signature [Signature](../../com.groupdocs.signature/signature). |

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


Inisialisasi ImageSignature dengan parameter default.

### getSize() {#getSize--}
```
public final int getSize()
```


Menentukan ukuran dalam byte gambar tanda tangan.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Menentukan ukuran dalam byte gambar tanda tangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Menentukan format gambar tanda tangan.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFormat(FileType value)
```


Menentukan format gambar tanda tangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getContent() {#getContent--}
```
public final byte[] getContent()
```


Menentukan konten data biner gambar dengan tipe Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). Secara default properti ini tidak akan diatur. Gunakan properti ImageSearchOptions.ReturnContent (\{ ImageSearchOptions\#getReturnContent\}/\{ ImageSearchOptions\#setReturnContent(boolean)\}) untuk mengaktifkan fitur ini.

**Returns:**
byte[]
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Menimpa metode Equals untuk membandingkan properti tanda tangan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tanda tangan | java.lang.Object | Objek tanda tangan untuk dibandingkan. |

**Returns:**
boolean - Mengembalikan true jika objek tanda tangan yang diberikan memiliki tipe yang sama dan semua propertinya sama dengan properti instance ini.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Menimpa metode GetHashCode

**Returns:**
int - Kode hash tanda tangan
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Klon instance Tanda Tangan Barcode.

**Returns:**
java.lang.Object - Mengembalikan instance Barcode Signature yang dikloning.
