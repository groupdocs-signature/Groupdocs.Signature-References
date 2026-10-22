---
title: "QrCodeSignOptions"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示 QR-Code 签名选项。"
type: docs
weight: 15
url: /zh/nodejs-java/com.groupdocs.signature.options.sign/qrcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class QrCodeSignOptions extends TextSignOptions
```

表示 QR-Code 签名选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [QrCodeSignOptions()](#QrCodeSignOptions--) | 使用默认值初始化 QRCodeSignOptions 类的新实例。 |
| [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | 使用文本初始化 QRCodeSignOptions 类的新实例。 |
| [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | 使用文本初始化 BarcodeSignOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | 获取或设置 QRCode 类型。 |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | 获取或设置 QRCode 类型。 |
| [getForeColor()](#getForeColor--) | 获取或设置 QR-Code 条的前景颜色。使用此属性可能导致验证问题。 |
| [setForeColor(Color value)](#setForeColor-java.awt.Color-) | 获取或设置 QR-Code 条的前景颜色。使用此属性可能导致验证问题。 |
| [setForeColor(String value)](#setForeColor-java.lang.String-) | 获取或设置 QR-Code 条的前景颜色。使用此属性可能导致验证问题。 |
| [getInnerMargins()](#getInnerMargins--) | 获取或设置 QRCode 元素与结果图像边框之间的间距。 |
| [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | 获取或设置 QRCode 元素与结果图像边框之间的间距。 |
| [getCodeTextAlignment()](#getCodeTextAlignment--) | 获取或设置结果 QR-code 图像中文本的对齐方式。 |
| [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | 获取或设置结果 QR-code 图像中文本的对齐方式。 |
| [getLogoFilePath()](#getLogoFilePath--) | 获取或设置 QR-code 徽标图像文件名。 |
| [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | 获取或设置 QR-code 徽标图像文件名。 |
| [getLogoStream()](#getLogoStream--) | 获取或设置 QR-code 徽标图像流。 |
| [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | 获取或设置 QR-code 徽标图像流。 |
| [getData()](#getData--) | 获取或设置用于序列化为 QR-Code 内容的自定义对象。 |
| [setData(Object value)](#setData-java.lang.Object-) | 获取或设置用于序列化为 QR-Code 内容的自定义对象。 |
| [getDataEncryption()](#getDataEncryption--) | 获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以对 QR-Code 签名文本或数据属性进行编码和解码。 |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | 获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以对 QR-Code 签名文本或数据属性进行编码和解码。 |
| [getReturnContent()](#getReturnContent--) | 获取或设置标志，以获取放置在文档页面上的签名的 QR-Code 图像内容。 |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | 获取或设置标志，以获取放置在文档页面上的签名的 QR-Code 图像内容。 |
| [getReturnContentType()](#getReturnContentType--) | 指定在启用 ReturnContent 属性时返回的 QR-Code 签名图像内容的文件类型。 |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | 指定在启用 ReturnContent 属性时返回的 QR-Code 签名图像内容的文件类型。 |
| [toString()](#toString--) | 覆盖字符串转换。 |
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


使用默认值初始化 QRCodeSignOptions 类的新实例。

### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


使用文本初始化 QRCodeSignOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 签名文本。 |

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


使用文本初始化 BarcodeSignOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | QRCode 文本 |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QRCode 编码类型，请参见 [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


获取或设置 QRCode 类型。

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


获取或设置 QRCode 类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


获取或设置 QR-Code 条的前景颜色。使用此属性可能导致验证问题。请谨慎使用。

**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


获取或设置 QR-Code 条的前景颜色。使用此属性可能导致验证问题。请谨慎使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


获取或设置 QR-Code 条的前景颜色。使用此属性可能导致验证问题。请谨慎使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


获取或设置 QRCode 元素与结果图像边框之间的间距。

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


获取或设置 QRCode 元素与结果图像边框之间的间距。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


获取或设置结果 QR-code 图像中文本的对齐方式。默认值为 None。

**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


获取或设置结果 QR-code 图像中文本的对齐方式。默认值为 None。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


获取或设置 QR-code 徽标图像文件名。仅在未指定 LogoStream 时使用此属性。使用此属性可能导致验证问题。请谨慎使用。

**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


获取或设置 QR-code 徽标图像文件名。仅在未指定 LogoStream 时使用此属性。使用此属性可能导致验证问题。请谨慎使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


获取或设置 QR-code 徽标图像流。如果指定了此属性，则始终使用它而不是 LogoGuid。使用此属性可能导致验证问题。请谨慎使用。

**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


获取或设置 QR-code 徽标图像流。如果指定了此属性，则始终使用它而不是 LogoGuid。使用此属性可能导致验证问题。请谨慎使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


获取或设置用于序列化为 QR-Code 内容的自定义对象。

**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


获取或设置用于序列化为 QR-Code 内容的自定义对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以对 QR-Code 签名文本或数据属性进行编码和解码。

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以对 QR-Code 签名文本或数据属性进行编码和解码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


获取或设置标志，以获取放置在文档页面上的签名的 QR-Code 图像内容。如果此标志设置为 true，QR-Code 签名图像内容将按照所需格式 ReturnContentType 保留原始图像数据 (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType))。默认情况下此选项为禁用。

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


获取或设置标志，以获取放置在文档页面上的签名的 QR-Code 图像内容。如果此标志设置为 true，QR-Code 签名图像内容将按照所需格式 ReturnContentType 保留原始图像数据 (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType))。默认情况下此选项为禁用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


指定在启用 ReturnContent 属性时返回的 QR-Code 签名图像内容的文件类型。默认设置为 Null，这意味着返回原始格式的 QR-Code 图像内容。该图像格式在 QrCodeSignature.Format 中指定（[QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature\#getFormat)/\{@link QrCodeSignature\#(FileType)\}），可能支持的值有：FileType.JPEG、FileType.PNG、FileType.BMP。如果提供的格式不受支持，则返回 .png 格式的 QR-Code 图像内容。

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


指定在启用 ReturnContent 属性时返回的 QR-Code 签名图像内容的文件类型。默认设置为 Null，这意味着返回原始格式的 QR-Code 图像内容。该图像格式在 QrCodeSignature.Format 中指定（[QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature\#getFormat)/\{@link QrCodeSignature\#(FileType)\}），可能支持的值有：FileType.JPEG、FileType.PNG、FileType.BMP。如果提供的格式不受支持，则返回 .png 格式的 QR-Code 图像内容。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


覆盖字符串转换。

**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
