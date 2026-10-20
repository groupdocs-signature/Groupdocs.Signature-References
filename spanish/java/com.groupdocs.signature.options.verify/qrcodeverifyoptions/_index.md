---
title: "QrCodeVerifyOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Mantiene opciones para verificar la firma de código QR del documento."
type: docs
weight: 13
url: /es/java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

Mantiene opciones para verificar la firma de código QR del documento.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/)
* Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/)

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | Crea la opción de verificación QRCodeVerifyOptions para QR-Code Signatures. |
|
|  | [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | Crea la opción de verificación QRCodeVerifyOptions para QR-Code Signatures con texto QR-Code a verificar. |
|
|  | [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Crea la opción de verificación QRCodeVerifyOptions para firmas QR-Code con texto y tipo de codificación QR-Code para verificar. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Obtiene o establece la verificación del tipo QR-code. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Obtiene o establece la verificación del tipo QR-code. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar las propiedades de texto de la firma QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar las propiedades de texto de la firma QR-Code. |
|
|  | [toString()](#toString--) | Sobrescribe la conversión a cadena. |
|
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


Crea la opción de verificación QRCodeVerifyOptions para QR-Code Signatures.


### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


Crea la opción de verificación QRCodeVerifyOptions para QR-Code Signatures con texto QR-Code a verificar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | texto | java.lang.String | Texto QR-code para verificar |
|

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


Crea la opción de verificación QRCodeVerifyOptions para firmas QR-Code con texto y tipo de codificación QR-Code para verificar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | texto | java.lang.String | Texto a verificar |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Tipo de codificación |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Obtiene o establece la verificación del tipo QR-code. Esta propiedad es opcional.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Obtiene o establece la verificación del tipo QR-code. Esta propiedad es opcional.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar las propiedades de texto de la firma QR-Code.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar las propiedades de texto de la firma QR-Code.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


Sobrescribe la conversión a cadena.


**Returns:**
java.lang.String - 
