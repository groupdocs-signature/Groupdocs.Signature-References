---
title: "BarcodeSearchOptions"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示条形码签名的抽象搜索选项。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.signature.options.search/barcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class BarcodeSearchOptions extends SearchOptions
```

表示条形码签名的抽象搜索选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BarcodeSearchOptions()](#BarcodeSearchOptions--) | 使用默认值初始化 SearchBarcodeOptions 类的新实例。 |
| [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | 使用编码类型值初始化 SearchBarcodeOptions 类的新实例。 |
| [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | 使用编码类型和文本值初始化 SearchBarcodeOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | 指定用于搜索条形码的编码类型属性。 |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | 指定用于搜索条形码的编码类型属性。 |
| [getText()](#getText--) | 指定条形码签名文本（如果需要搜索和匹配）。 |
| [setText(String value)](#setText-java.lang.String-) | 指定条形码签名文本（如果需要搜索和匹配）。 |
| [getMatchType()](#getMatchType--) | 获取或设置条形码文本匹配类型搜索。 |
| [setMatchType(int value)](#setMatchType-int-) | 获取或设置条形码文本匹配类型搜索。 |
| [getReturnContent()](#getReturnContent--) | 获取或设置标志，以获取文档页面上签名的条形码图像内容。 |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | 获取或设置标志，以获取文档页面上签名的条形码图像内容。 |
| [getReturnContentType()](#getReturnContentType--) | 当启用 ReturnContent 属性时，指定条形码签名返回的图像内容的文件类型。 |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | 当启用 ReturnContent 属性时，指定条形码签名返回的图像内容的文件类型。 |
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


使用默认值初始化 SearchBarcodeOptions 类的新实例。

### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


使用编码类型值初始化 SearchBarcodeOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | 指定条形码编码类型。 |

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


使用编码类型和文本值初始化 SearchBarcodeOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | 指定条形码编码类型。 |
| 文本 | java.lang.String | 设置条形码签名的文本。 |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


指定用于搜索条形码的编码类型属性。如果未设置此值，则会对所有支持的条形码类型进行搜索。

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


指定用于搜索条形码的编码类型属性。如果未设置此值，则会对所有支持的条形码类型进行搜索。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


指定条形码签名文本（如果需要搜索和匹配）。

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


指定条形码签名文本（如果需要搜索和匹配）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


获取或设置条形码文本匹配类型搜索。仅在设置 Text 属性时使用。

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


获取或设置条形码文本匹配类型搜索。仅在设置 Text 属性时使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


获取或设置标志，以获取文档页面上签名的条形码图像内容。如果此标志设为 true，条形码签名图像内容将按所需格式 ReturnContentType (\\#getReturnContentType.getReturnContentType/\\#setReturnContentType(FileType).setReturnContentType(FileType)) 保持原始图像数据。默认情况下此选项已禁用。

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


获取或设置标志，以获取文档页面上签名的条形码图像内容。如果此标志设为 true，条形码签名图像内容将按所需格式 ReturnContentType (\\#getReturnContentType.getReturnContentType/\\#setReturnContentType(FileType).setReturnContentType(FileType)) 保持原始图像数据。默认情况下此选项已禁用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


指定在启用 ReturnContent 属性时返回的条形码签名图像内容的文件类型。默认设置为 Null。这意味着返回条形码图像内容的原始格式。此图像格式在 BarcodeSignature.Format ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}) 中指定。可能支持的值有：FileType.JPEG、FileType.PNG、FileType.BMP。如果提供的格式不受支持，则返回 .png 格式的条形码图像内容。

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


指定在启用 ReturnContent 属性时返回的条形码签名图像内容的文件类型。默认设置为 Null。这意味着返回条形码图像内容的原始格式。此图像格式在 BarcodeSignature.Format ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}) 中指定。可能支持的值有：FileType.JPEG、FileType.PNG、FileType.BMP。如果提供的格式不受支持，则返回 .png 格式的条形码图像内容。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

