---
title: "QrCodeVerifyOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat opties om de QR-codehandtekening van een document te verifiëren."
type: docs
weight: 13
url: /nl/java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

Bevat opties om de QR-codehandtekening van een document te verifiëren.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/)
* Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/)

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | Maakt verificatie‑optie QRCodeVerifyOptions voor QR‑code‑handtekeningen. |
|
|  | [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | Maakt verificatie‑optie QRCodeVerifyOptions voor QR‑code‑handtekeningen met QR‑code‑tekst om te verifiëren. |
|
|  | [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Maakt verificatie‑optie QRCodeVerifyOptions voor QR‑code‑handtekeningen met tekst en QR‑code‑encodeertype om te verifiëren. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Haalt op of stelt QR‑code‑type verificatie in. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Haalt op of stelt QR‑code‑type verificatie in. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Haalt op of stelt implementatie van [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface in om QR‑code‑handtekening‑tekst‑eigenschappen te coderen en te decoderen. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Haalt op of stelt implementatie van [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface in om QR‑code‑handtekening‑tekst‑eigenschappen te coderen en te decoderen. |
|
|  | [toString()](#toString--) | Overschrijft conversie naar string. |
|
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


Maakt verificatie‑optie QRCodeVerifyOptions voor QR‑code‑handtekeningen.


### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


Maakt verificatie‑optie QRCodeVerifyOptions voor QR‑code‑handtekeningen met QR‑code‑tekst om te verifiëren.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | QR‑code‑tekst om te verifiëren |
|

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


Maakt verificatie‑optie QRCodeVerifyOptions voor QR‑code‑handtekeningen met tekst en QR‑code‑encodeertype om te verifiëren.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | Te verifiëren tekst |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Type van codering |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Haalt op of stelt QR‑code‑type verificatie in. Deze eigenschap is optioneel.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Haalt op of stelt QR‑code‑type verificatie in. Deze eigenschap is optioneel.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Haalt op of stelt implementatie van [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface in om QR‑code‑handtekening‑tekst‑eigenschappen te coderen en te decoderen.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Haalt op of stelt implementatie van [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface in om QR‑code‑handtekening‑tekst‑eigenschappen te coderen en te decoderen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


Overschrijft conversie naar string.


**Returns:**
java.lang.String -
