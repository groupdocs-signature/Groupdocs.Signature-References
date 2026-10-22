---
title: "QrCodeSignature"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Berisi properti QR-code signature."
type: docs
weight: 16
url: /id/nodejs-java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

Berisi properti QR-code signature.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | Inisialisasi objek QrCodeSignature dengan pengidentifikasi tanda tangan yang diperoleh setelah proses pencarian. |
| [QrCodeSignature()](#QrCodeSignature--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Menentukan Tipe Enkode QR-code. |
| [getText()](#getText--) | Menentukan teks QR-code. |
| [getFormat()](#getFormat--) | Menentukan format gambar tanda tangan QR-code. |
| [getContent()](#getContent--) | Menentukan konten gambar data biner QR-code dengan tipe  Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | Mendapatkan objek dari Teks Tanda Tangan QR-Code melalui deserialisasi. |
| [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | Mendapatkan objek dari Teks Tanda Tangan QR-Code melalui deserialisasi. |
| [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
| [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
| [deepClone()](#deepClone--) | Kloning instance Tanda Tangan QR-Code. |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


Inisialisasi objek QrCodeSignature dengan pengidentifikasi tanda tangan yang diperoleh setelah proses pencarian. Pengidentifikasi unik ini digunakan untuk menemukan properti tambahan untuk tanda tangan ini dari lapisan informasi tanda tangan dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signatureId | java.lang.String | Pengidentifikasi tanda tangan unik yang diperoleh melalui metode tanda tangan atau pencarian. |

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Menentukan Tipe Enkode QR-code.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


Menentukan teks QR-code.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Menentukan format gambar tanda tangan QR-code.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Menentukan konten gambar data biner QR-code dengan tipe  Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). Secara default properti ini tidak akan diatur. Gunakan properti  QrCodeSearchOptions.ReturnContent ([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions\#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions\#setReturnContent-boolean-)) untuk mengaktifkan fitur ini.

**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


Mendapatkan objek dari Teks Tanda Tangan QR-Code melalui deserialisasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | java.lang.Class<T> |  |

**Returns:**
T -  T : Tipe objek untuk deserialisasi dari Teks QR-Code
### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


Mendapatkan objek dari Teks Tanda Tangan QR-Code melalui deserialisasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Atur implementasi enkripsi data khusus |

T : Tipe objek untuk deserialisasi dari Teks QR-Code |
| tipe | java.lang.Class<T> |  |

**Returns:**
T -
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


Kloning instance Tanda Tangan QR-Code.

**Returns:**
java.lang.Object - Mengembalikan instance Tanda Tangan QR-code yang dikloning.
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| gambar | java.awt.image.BufferedImage |  |

