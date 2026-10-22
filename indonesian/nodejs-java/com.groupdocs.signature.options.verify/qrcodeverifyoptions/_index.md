---
title: "QrCodeVerifyOptions"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Menyimpan opsi untuk memverifikasi tanda tangan kode QR dokumen."
type: docs
weight: 13
url: /id/nodejs-java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

Menyimpan opsi untuk memverifikasi tanda tangan kode QR dokumen.

--------------------

**Learn more**

 *  Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document ][How to eVerification QR-code signatures in a document]
 *  Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings][]


[How to eVerification QR-code signatures in a document]: https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/
[Advanced usage of eVerification QR-code signatures in a document and additional settings]: https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | Membuat opsi verifikasi QRCodeVerifyOptions untuk Tanda Tangan QR-Code. |
| [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | Membuat opsi verifikasi QRCodeVerifyOptions untuk Tanda Tangan QR-Code dengan teks QR-Code untuk diverifikasi. |
| [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Membuat opsi verifikasi QRCodeVerifyOptions untuk Tanda Tangan QR-Code dengan teks dan tipe enkode QR-Code untuk diverifikasi. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Mendapatkan atau mengatur verifikasi Tipe QR-code. |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Mendapatkan atau mengatur verifikasi Tipe QR-code. |
| [getDataEncryption()](#getDataEncryption--) | Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi properti Teks Tanda Tangan QR-Code. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi properti Teks Tanda Tangan QR-Code. |
| [toString()](#toString--) | Menimpa konversi ke string. |
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


Membuat opsi verifikasi QRCodeVerifyOptions untuk Tanda Tangan QR-Code.

### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


Membuat opsi verifikasi QRCodeVerifyOptions untuk Tanda Tangan QR-Code dengan teks QR-Code untuk diverifikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | Teks QR-code untuk diverifikasi |

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


Membuat opsi verifikasi QRCodeVerifyOptions untuk Tanda Tangan QR-Code dengan teks dan tipe enkode QR-Code untuk diverifikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | Teks yang akan diverifikasi |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Tipe enkoding |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Mendapatkan atau mengatur verifikasi Tipe QR-code. Properti ini bersifat opsional.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Mendapatkan atau mengatur verifikasi Tipe QR-code. Properti ini bersifat opsional.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi properti Teks Tanda Tangan QR-Code.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi properti Teks Tanda Tangan QR-Code.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


Menimpa konversi ke string.

**Returns:**
java.lang.String -
