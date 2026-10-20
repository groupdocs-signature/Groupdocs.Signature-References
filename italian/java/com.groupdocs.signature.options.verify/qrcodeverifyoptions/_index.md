---
title: "QrCodeVerifyOptions"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Mantiene le opzioni per verificare la firma QR-code del documento."
type: docs
weight: 13
url: /it/java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

Mantiene le opzioni per verificare la firma QR-code del documento.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/)
* Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/)

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | Crea l'opzione di verifica QRCodeVerifyOptions per le firme QR-Code. |
|
|  | [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | Crea l'opzione di verifica QRCodeVerifyOptions per le firme QR-Code con il testo QR-Code da verificare. |
|
|  | [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Crea l'opzione di verifica QRCodeVerifyOptions per le firme QR-Code con testo e tipo di codifica QR-Code da verificare. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Ottiene o imposta la verifica del tipo QR-code. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Ottiene o imposta la verifica del tipo QR-code. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà di testo della firma QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà di testo della firma QR-Code. |
|
|  | [toString()](#toString--) | Sovrascrive la conversione in stringa. |
|
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


Crea l'opzione di verifica QRCodeVerifyOptions per le firme QR-Code.


### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


Crea l'opzione di verifica QRCodeVerifyOptions per le firme QR-Code con il testo QR-Code da verificare.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | testo | java.lang.String | Testo QR-code da verificare |
|

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


Crea l'opzione di verifica QRCodeVerifyOptions per le firme QR-Code con testo e tipo di codifica QR-Code da verificare.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | testo | java.lang.String | Testo da verificare |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Tipo di codifica |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Ottiene o imposta la verifica del tipo QR-code. Questa proprietà è opzionale.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Ottiene o imposta la verifica del tipo QR-code. Questa proprietà è opzionale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà di testo della firma QR-Code.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà di testo della firma QR-Code.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


Sovrascrive la conversione in stringa.


**Returns:**
java.lang.String -
