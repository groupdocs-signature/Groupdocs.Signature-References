---
title: "BarcodeSignature"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Berisi properti Barcode Signature."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

Berisi properti Barcode Signature.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | Inisialisasi objek BarcodeSignature dengan pengidentifikasi tanda tangan yang diperoleh setelah proses pencarian. |
| [BarcodeSignature()](#BarcodeSignature--) | Inisialisasi BarcodeSignature dengan parameter default. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Menentukan Tipe Enkode Barcode. |
| [getText()](#getText--) | Menentukan teks Barcode. |
| [getFormat()](#getFormat--) | Menentukan format gambar tanda tangan Barcode. |
| [getContent()](#getContent--) | Menentukan konten gambar data biner Barcode dengan tipe Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
| [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
| [deepClone()](#deepClone--) | Klon instance Tanda Tangan Barcode. |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


Inisialisasi objek BarcodeSignature dengan pengidentifikasi tanda tangan yang diperoleh setelah proses pencarian. Pengidentifikasi unik ini digunakan untuk menemukan properti tambahan untuk tanda tangan ini dari lapisan informasi tanda tangan dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signatureId | java.lang.String | Pengidentifikasi tanda tangan unik yang diperoleh melalui metode Sign atau Search dari kelas Signature [Signature](../../com.groupdocs.signature/signature). |

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


Inisialisasi BarcodeSignature dengan parameter default.

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Menentukan Tipe Enkode Barcode.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


Menentukan teks Barcode.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Menentukan format gambar tanda tangan Barcode.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Menentukan konten gambar data biner Barcode dengan tipe Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). Secara default properti ini tidak akan diatur. Gunakan properti BarcodeSearchOptions.ReturnContent ([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions\#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions\#setReturnContent-boolean-)) untuk mengaktifkan fitur ini.

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
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| gambar | java.awt.image.BufferedImage |  |

