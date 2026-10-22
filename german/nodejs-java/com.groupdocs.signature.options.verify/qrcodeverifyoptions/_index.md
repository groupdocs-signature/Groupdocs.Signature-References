---
title: "QrCodeVerifyOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Enthält Optionen zum Verifizieren der QR‑Code‑Signatur des Dokuments."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

Enthält Optionen zum Verifizieren der QR‑Code‑Signatur des Dokuments.

--------------------

**Learn more**

 *  Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document ][How to eVerification QR-code signatures in a document]
 *  Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings][]


[How to eVerification QR-code signatures in a document]: https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/
[Advanced usage of eVerification QR-code signatures in a document and additional settings]: https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | Erstellt die Verifizierungsoption QRCodeVerifyOptions für QR-Code-Signaturen. |
| [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | Erstellt die Verifizierungsoption QRCodeVerifyOptions für QR-Code-Signaturen mit QR-Code-Text zur Verifizierung. |
| [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Erstellt die Verifizierungsoption QRCodeVerifyOptions für QR-Code-Signaturen mit Text und QR-Code-Kodierungstyp zur Verifizierung. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Liest oder setzt die QR-Code-Typ-Verifizierung. |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Liest oder setzt die QR-Code-Typ-Verifizierung. |
| [getDataEncryption()](#getDataEncryption--) | Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Kodieren und Dekodieren der QR-Code-Signatur-Text-Eigenschaften. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Kodieren und Dekodieren der QR-Code-Signatur-Text-Eigenschaften. |
| [toString()](#toString--) | Überschreibt die Konvertierung in einen String. |
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


Erstellt die Verifizierungsoption QRCodeVerifyOptions für QR-Code-Signaturen.

### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


Erstellt die Verifizierungsoption QRCodeVerifyOptions für QR-Code-Signaturen mit QR-Code-Text zur Verifizierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | QR-Code-Text zur Verifizierung |

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


Erstellt die Verifizierungsoption QRCodeVerifyOptions für QR-Code-Signaturen mit Text und QR-Code-Kodierungstyp zur Verifizierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu überprüfender Text |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Kodierungstyp |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Liest oder setzt die QR-Code-Typ-Verifizierung. Diese Eigenschaft ist optional.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Liest oder setzt die QR-Code-Typ-Verifizierung. Diese Eigenschaft ist optional.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Kodieren und Dekodieren der QR-Code-Signatur-Text-Eigenschaften.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Kodieren und Dekodieren der QR-Code-Signatur-Text-Eigenschaften.

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
