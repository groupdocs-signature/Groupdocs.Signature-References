---
title: "QrCodeVerifyOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Belge QR-kodu imzasını doğrulama seçeneklerini tutar."
type: docs
weight: 13
url: /tr/java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

Belge QR-kodu imzasını doğrulama seçeneklerini tutar.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/)
* Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/)

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | QR-Kod İmzaları için QRCodeVerifyOptions doğrulama seçeneği oluşturur. |
|
|  | [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | Doğrulanacak QR-Kod metniyle QR-Code İmzaları için QRCodeVerifyOptions doğrulama seçeneği oluşturur. |
|
|  | [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QR-Code İmzaları için metin ve QR-Code kodlama türüyle doğrulama yapmak üzere QRCodeVerifyOptions doğrulama seçeneği oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | QR-code Tür doğrulamasını alır veya ayarlar. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QR-code Tür doğrulamasını alır veya ayarlar. |
|
|  | [getDataEncryption()](#getDataEncryption--) | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulamasını alır veya ayarlar; QR-Code İmza Metni özelliklerini kodlamak ve çözmek için. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulamasını alır veya ayarlar; QR-Code İmza Metni özelliklerini kodlamak ve çözmek için. |
|
|  | [toString()](#toString--) | Stringe dönüşümü geçersiz kılar. |
|
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


QR-Kod İmzaları için QRCodeVerifyOptions doğrulama seçeneği oluşturur.


### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


Doğrulanacak QR-Kod metniyle QR-Code İmzaları için QRCodeVerifyOptions doğrulama seçeneği oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | Doğrulanacak QR-code Metni |
|

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


QR-Code İmzaları için metin ve QR-Code kodlama türüyle doğrulama yapmak üzere QRCodeVerifyOptions doğrulama seçeneği oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | Doğrulanacak metin |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Kodlama türü |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QR-code Tür doğrulamasını alır veya ayarlar. Bu özellik isteğe bağlıdır.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


QR-code Tür doğrulamasını alır veya ayarlar. Bu özellik isteğe bağlıdır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulamasını alır veya ayarlar; QR-Code İmza Metni özelliklerini kodlamak ve çözmek için.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulamasını alır veya ayarlar; QR-Code İmza Metni özelliklerini kodlamak ve çözmek için.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


Stringe dönüşümü geçersiz kılar.


**Returns:**
java.lang.String -
