---
title: "QrCodeVerifyOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Behåller alternativ för att verifiera dokumentets QR-kod-signatur."
type: docs
weight: 13
url: /sv/java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

Behåller alternativ för att verifiera dokumentets QR-kod-signatur.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/)
* Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/)

<br />


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | Skapar verifieringsalternativ QRCodeVerifyOptions för QR-kodsignaturer. |
|
|  | [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | Skapar verifieringsalternativ QRCodeVerifyOptions för QR-kodsignaturer med QR-kodtext att verifiera. |
|
|  | [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Skapar verifieringsalternativ QRCodeVerifyOptions för QR-kodsignaturer med text och QR-kodkodningstyp att verifiera. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Hämtar eller anger verifiering av QR-kodtyp. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Hämtar eller anger verifiering av QR-kodtyp. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) gränssnittet för att koda och avkoda QR-kodsignaturens textegenskaper. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) gränssnittet för att koda och avkoda QR-kodsignaturens textegenskaper. |
|
|  | [toString()](#toString--) | Åsidosätter konvertering till sträng. |
|
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


Skapar verifieringsalternativ QRCodeVerifyOptions för QR-kodsignaturer.


### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


Skapar verifieringsalternativ QRCodeVerifyOptions för QR-kodsignaturer med QR-kodtext att verifiera.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | QR-kodtext att verifiera |
|

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


Skapar verifieringsalternativ QRCodeVerifyOptions för QR-kodsignaturer med text och QR-kodkodningstyp att verifiera.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | Text att verifiera |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Kodningstyp |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Hämtar eller anger verifiering av QR-kodtyp. Denna egenskap är valfri.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Hämtar eller anger verifiering av QR-kodtyp. Denna egenskap är valfri.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) gränssnittet för att koda och avkoda QR-kodsignaturens textegenskaper.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) gränssnittet för att koda och avkoda QR-kodsignaturens textegenskaper.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


Åsidosätter konvertering till sträng.


**Returns:**
java.lang.String -
