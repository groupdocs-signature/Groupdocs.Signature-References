---
title: "QrCodeSearchOptions"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示二维码签名的抽象搜索选项。"
type: docs
weight: 16
url: /zh/nodejs-java/com.groupdocs.signature.options.search/qrcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class QrCodeSearchOptions extends SearchOptions
```

表示二维码签名的抽象搜索选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [QrCodeSearchOptions()](#QrCodeSearchOptions--) | 使用默认值初始化 QRCodeSearchOptions 类的新实例。 |
| [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | 使用编码类型值初始化 QRCodeSearchOptions 类的新实例。 |
| [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | 使用编码类型和文本值初始化 QRCodeSearchOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | 指定用于搜索二维码的编码类型属性。 |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | 指定用于搜索二维码的编码类型属性。 |
| [getText()](#getText--) | 指定 QR-Code 签名文本（如果应进行搜索和匹配）。 |
| [setText(String value)](#setText-java.lang.String-) | 指定 QR-Code 签名文本（如果应进行搜索和匹配）。 |
| [getMatchType()](#getMatchType--) | 获取或设置 QR-Code 文本匹配类型搜索。 |
| [setMatchType(int value)](#setMatchType-int-) | 获取或设置 QR-Code 文本匹配类型搜索。 |
| [getDataEncryption()](#getDataEncryption--) | 获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以对 QR-Code 签名文本或数据属性进行编码和解码。 |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | 获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以对 QR-Code 签名文本或数据属性进行编码和解码。 |
| [getReturnContent()](#getReturnContent--) | 获取或设置标志，以获取文档页面上签名的 QR-Code 图像内容。 |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | 获取或设置标志，以获取文档页面上签名的 QR-Code 图像内容。 |
| [getReturnContentType()](#getReturnContentType--) | 指定在启用 ReturnContent 属性时返回的 QR-Code 签名图像内容的文件类型。 |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | 指定在启用 ReturnContent 属性时返回的 QR-Code 签名图像内容的文件类型。 |
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


使用默认值初始化 QRCodeSearchOptions 类的新实例。

### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


使用编码类型值初始化 QRCodeSearchOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | 指定 QR-Code 编码类型。 |

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


使用编码类型和文本值初始化 QRCodeSearchOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | 指定 QR-Code 编码类型。 |
| 文本 | java.lang.String | 设置 QR-Code 签名的文本。 |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


指定用于搜索 QR-Code 的编码类型属性。如果未设置此值，则会对所有支持的 QR-Code 类型进行搜索。

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


指定用于搜索 QR-Code 的编码类型属性。如果未设置此值，则会对所有支持的 QR-Code 类型进行搜索。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


指定 QR-Code 签名文本（如果应进行搜索和匹配）。

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


指定 QR-Code 签名文本（如果应进行搜索和匹配）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


获取或设置 QR-Code 文本匹配类型搜索。仅在设置 Text 属性时使用。

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


获取或设置 QR-Code 文本匹配类型搜索。仅在设置 Text 属性时使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

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


获取或设置标志，以获取文档页面上签名的 QR-Code 图像内容。如果此标志设为 true，QR-Code 签名图像内容将按所需格式 ReturnContentType (\\#getReturnContentType.getReturnContentType/\\#setReturnContentType(FileType).setReturnContentType(FileType)) 保持原始图像数据。默认情况下此选项已禁用。

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


获取或设置标志，以获取文档页面上签名的 QR-Code 图像内容。如果此标志设为 true，QR-Code 签名图像内容将按所需格式 ReturnContentType (\\#getReturnContentType.getReturnContentType/\\#setReturnContentType(FileType).setReturnContentType(FileType)) 保持原始图像数据。默认情况下此选项已禁用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


指定在启用 ReturnContent 属性时返回的 QR-Code 签名图像内容的文件类型。默认设置为 Null，这意味着返回原始格式的 QR-Code 图像内容。该图像格式在 QrCodeSignature.Format() 中指定，可能的支持值有：FileType.JPEG、FileType.PNG、FileType.BMP。如果提供的格式不受支持，则返回原始 .png 格式的 QR-Code 图像内容。

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


指定在启用 ReturnContent 属性时返回的 QR-Code 签名图像内容的文件类型。默认设置为 Null，这意味着返回原始格式的 QR-Code 图像内容。该图像格式在 QrCodeSignature.Format() 中指定，可能的支持值有：FileType.JPEG、FileType.PNG、FileType.BMP。如果提供的格式不受支持，则返回原始 .png 格式的 QR-Code 图像内容。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

