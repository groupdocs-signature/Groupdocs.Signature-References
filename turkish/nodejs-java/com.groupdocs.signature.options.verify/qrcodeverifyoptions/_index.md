---
title: "QrCodeVerifyOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Belge QR-kodu imzasını doğrulamak için seçenekleri tutar."
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

Belge QR-kodu imzasını doğrulamak için seçenekleri tutar.

--------------------

**Learn more**

 *  Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document ][How to eVerification QR-code signatures in a document]
 *  Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings][]


[How to eVerification QR-code signatures in a document]: https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/
[Advanced usage of eVerification QR-code signatures in a document and additional settings]: https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | QR-Kod İmzaları için QRCodeVerifyOptions doğrulama seçeneği oluşturur. |
| [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | Doğrulama metniyle QR-Kod İmzaları için QRCodeVerifyOptions doğrulama seçeneği oluşturur. |
| [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Metin ve doğrulanacak QR-Kod kodlama türüyle QR-Kod İmzaları için QRCodeVerifyOptions doğrulama seçeneği oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | QR-kod Türü doğrulamasını alır veya ayarlar. |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QR-kod Türü doğrulamasını alır veya ayarlar. |
| [getDataEncryption()](#getDataEncryption--) | QR-Kod İmza Metni özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QR-Kod İmza Metni özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar. |
| [toString()](#toString--) | String'e dönüşümünü geçersiz kılar. |
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


QR-Kod İmzaları için QRCodeVerifyOptions doğrulama seçeneği oluşturur.

### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


Doğrulama metniyle QR-Kod İmzaları için QRCodeVerifyOptions doğrulama seçeneği oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Doğrulanacak QR-kod Metni |

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


Metin ve doğrulanacak QR-Kod kodlama türüyle QR-Kod İmzaları için QRCodeVerifyOptions doğrulama seçeneği oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Doğrulanacak metin |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Kodlama türü |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QR-kod Türü doğrulamasını alır veya ayarlar. Bu özellik isteğe bağlıdır.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


QR-kod Türü doğrulamasını alır veya ayarlar. Bu özellik isteğe bağlıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


QR-Kod İmza Metni özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


QR-Kod İmza Metni özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


String'e dönüşümünü geçersiz kılar.

**Returns:**
java.lang.String -
