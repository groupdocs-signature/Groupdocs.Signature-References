---
title: "QrCodeVerifyOptions"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "保留验证文档二维码签名的选项。"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

保留验证文档二维码签名的选项。

--------------------

**Learn more**

 *  Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document ][How to eVerification QR-code signatures in a document]
 *  Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings][]


[How to eVerification QR-code signatures in a document]: https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/
[Advanced usage of eVerification QR-code signatures in a document and additional settings]: https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | 为二维码签名创建验证选项 QRCodeVerifyOptions。 |
| [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | 为二维码签名创建验证选项 QRCodeVerifyOptions，包含要验证的二维码文本。 |
| [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | 为二维码签名创建验证选项 QRCodeVerifyOptions，包含要验证的文本和二维码编码类型。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | 获取或设置二维码类型验证。 |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | 获取或设置二维码类型验证。 |
| [getDataEncryption()](#getDataEncryption--) | 获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以对二维码签名文本属性进行编码和解码。 |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | 获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以对二维码签名文本属性进行编码和解码。 |
| [toString()](#toString--) | 重写转换为字符串的方法。 |
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


为二维码签名创建验证选项 QRCodeVerifyOptions。

### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


为二维码签名创建验证选项 QRCodeVerifyOptions，包含要验证的二维码文本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 要验证的二维码文本 |

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


为二维码签名创建验证选项 QRCodeVerifyOptions，包含要验证的文本和二维码编码类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 待验证的文本 |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | 编码类型 |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


获取或设置 QR-code 类型验证。此属性是可选的。

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


获取或设置 QR-code 类型验证。此属性是可选的。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以对二维码签名文本属性进行编码和解码。

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以对二维码签名文本属性进行编码和解码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


重写转换为字符串的方法。

**Returns:**
java.lang.String -
