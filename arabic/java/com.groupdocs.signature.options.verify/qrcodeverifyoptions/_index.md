---
title: "QrCodeVerifyOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحافظ على خيارات التحقق من توقيع رمز الاستجابة السريعة للمستند."
type: docs
weight: 13
url: /ar/java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

يحافظ على خيارات التحقق من توقيع رمز الاستجابة السريعة للمستند.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/)
* Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/)

<br />


## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | إنشاء خيار التحقق QRCodeVerifyOptions لتوقيعات QR-Code. |
|
|  | [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | إنشاء خيار التحقق QRCodeVerifyOptions لتوقيعات QR-Code مع نص QR-Code للتحقق. |
|
|  | [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | إنشاء خيار التحقق QRCodeVerifyOptions لتوقيعات QR-Code مع النص ونوع ترميز QR-Code للتحقق. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | الحصول أو تعيين التحقق من نوع QR-code. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | الحصول أو تعيين التحقق من نوع QR-code. |
|
|  | [getDataEncryption()](#getDataEncryption--) | الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص نص توقيع QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص نص توقيع QR-Code. |
|
|  | [toString()](#toString--) | يتجاوز التحويل إلى string. |
|
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


إنشاء خيار التحقق QRCodeVerifyOptions لتوقيعات QR-Code.


### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


إنشاء خيار التحقق QRCodeVerifyOptions لتوقيعات QR-Code مع نص QR-Code للتحقق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | نص QR-code للتحقق |
|

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


إنشاء خيار التحقق QRCodeVerifyOptions لتوقيعات QR-Code مع النص ونوع ترميز QR-Code للتحقق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | النص المراد التحقق منه |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | نوع الترميز |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


الحصول أو تعيين التحقق من نوع QR-code. هذه الخاصية اختيارية.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


الحصول أو تعيين التحقق من نوع QR-code. هذه الخاصية اختيارية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص نص توقيع QR-Code.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص نص توقيع QR-Code.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


يتجاوز التحويل إلى string.


**Returns:**
java.lang.String -
