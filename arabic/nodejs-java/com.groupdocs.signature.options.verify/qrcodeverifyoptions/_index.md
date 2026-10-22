---
title: "QrCodeVerifyOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحافظ على خيارات التحقق من توقيع QR-code للمستند."
type: docs
weight: 13
url: /ar/nodejs-java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

يحافظ على خيارات التحقق من توقيع QR-code للمستند.

--------------------

**Learn more**

 *  Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document ][How to eVerification QR-code signatures in a document]
 *  Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings][]


[How to eVerification QR-code signatures in a document]: https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/
[Advanced usage of eVerification QR-code signatures in a document and additional settings]: https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | ينشئ خيار التحقق QRCodeVerifyOptions لتوقيعات QR-Code. |
| [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | ينشئ خيار التحقق QRCodeVerifyOptions لتوقيعات QR-Code مع نص QR-Code للتحقق. |
| [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | ينشئ خيار التحقق QRCodeVerifyOptions لتوقيعات QR-Code مع النص ونوع ترميز QR-Code للتحقق. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | يحصل أو يعيّن تحقق نوع QR-code. |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | يحصل أو يعيّن تحقق نوع QR-code. |
| [getDataEncryption()](#getDataEncryption--) | يحصل أو يعيّن تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص نص توقيع QR-Code. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | يحصل أو يعيّن تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص نص توقيع QR-Code. |
| [toString()](#toString--) | يتجاوز التحويل إلى سلسلة. |
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


ينشئ خيار التحقق QRCodeVerifyOptions لتوقيعات QR-Code.

### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


ينشئ خيار التحقق QRCodeVerifyOptions لتوقيعات QR-Code مع نص QR-Code للتحقق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نص | java.lang.String | نص QR-code للتحقق |

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


ينشئ خيار التحقق QRCodeVerifyOptions لتوقيعات QR-Code مع النص ونوع ترميز QR-Code للتحقق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نص | java.lang.String | النص المراد التحقق منه |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | نوع الترميز |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


يحصل أو يعيّن تحقق نوع QR-code. هذه الخاصية اختيارية.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


يحصل أو يعيّن تحقق نوع QR-code. هذه الخاصية اختيارية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


يحصل أو يعيّن تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص نص توقيع QR-Code.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


يحصل أو يعيّن تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص نص توقيع QR-Code.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


يتجاوز التحويل إلى سلسلة.

**Returns:**
java.lang.String -
