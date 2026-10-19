---
title: "QrCodeVerifyOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Enthält Optionen zum Verifizieren der QR‑Code‑Signatur eines Dokuments."
type: docs
weight: 13
url: /de/java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

Enthält Optionen zum Verifizieren der QR‑Code‑Signatur eines Dokuments.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/)
* Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/)

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | Erstellt die Verifizierungsoption QRCodeVerifyOptions für QR‑Code‑Signaturen. |
|
|  | [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | Erstellt die Verifizierungsoption QRCodeVerifyOptions für QR‑Code‑Signaturen mit zu verifizierendem QR‑Code‑Text. |
|
|  | [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Erstellt die Verifizierungsoption QRCodeVerifyOptions für QR‑Code‑Signaturen mit Text und zu verifizierendem QR‑Code‑Kodierungstyp. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Abrufen oder Festlegen der QR‑Code‑Typ‑Verifizierung. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Abrufen oder Festlegen der QR‑Code‑Typ‑Verifizierung. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Codieren und Dekodieren von QR-Code-Signatur-Text-Eigenschaften. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Codieren und Dekodieren von QR-Code-Signatur-Text-Eigenschaften. |
|
|  | [toString()](#toString--) | Überschreibt die Konvertierung in einen String. |
|
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


Erstellt die Verifizierungsoption QRCodeVerifyOptions für QR‑Code‑Signaturen.


### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


Erstellt die Verifizierungsoption QRCodeVerifyOptions für QR‑Code‑Signaturen mit zu verifizierendem QR‑Code‑Text.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | QR-Code-Text zur Überprüfung |
|

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


Erstellt die Verifizierungsoption QRCodeVerifyOptions für QR‑Code‑Signaturen mit Text und zu verifizierendem QR‑Code‑Kodierungstyp.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Zu verifizierender Text |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Kodierungstyp |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Liest oder setzt die QR-Code-Typ-Überprüfung. Diese Eigenschaft ist optional.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Liest oder setzt die QR-Code-Typ-Überprüfung. Diese Eigenschaft ist optional.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Codieren und Dekodieren von QR-Code-Signatur-Text-Eigenschaften.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Codieren und Dekodieren von QR-Code-Signatur-Text-Eigenschaften.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


Überschreibt die Konvertierung in einen String.


**Returns:**
java.lang.String -
