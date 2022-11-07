---
title: QrCodeVerifyOptions
second_title: GroupDocs.Editor for Java API Reference
description: Keeps options to verify document QR-code signature.
type: docs
weight: 12
url: /java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

Keeps options to verify document QR-code signature.

--------------------

**Learn more**

 *  Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document ][How to eVerification QR-code signatures in a document]
 *  Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings][]


[How to eVerification QR-code signatures in a document]: https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/
[Advanced usage of eVerification QR-code signatures in a document and additional settings]: https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/
## Constructors

| Constructor | Description |
| --- | --- |
| [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | Creates verification option QRCodeVerifyOptions for QR-Code Signatures. |
| [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | Creates verification option QRCodeVerifyOptions for QR-Code Signatures with QR-Code text to verify. |
| [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Creates verification option QRCodeVerifyOptions for QR-Code Signatures with text and QR-Code encode type to verify. |
## Methods

| Method | Description |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Gets or sets QR-code Type verification. |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Gets or sets QR-code Type verification. |
| [getDataEncryption()](#getDataEncryption--) | Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text properties. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text properties. |
| [toString()](#toString--) | Overrides conversion to string. |
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


Creates verification option QRCodeVerifyOptions for QR-Code Signatures.

### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


Creates verification option QRCodeVerifyOptions for QR-Code Signatures with QR-Code text to verify.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | QR-code Text to verify |

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


Creates verification option QRCodeVerifyOptions for QR-Code Signatures with text and QR-Code encode type to verify.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to be verified |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Type of encoding |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Gets or sets QR-code Type verification. This property is optional.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Gets or sets QR-code Type verification. This property is optional.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text properties.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


Overrides conversion to string.

**Returns:**
java.lang.String - 
