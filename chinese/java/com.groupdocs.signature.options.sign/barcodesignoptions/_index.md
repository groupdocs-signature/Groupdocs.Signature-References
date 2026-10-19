---
title: "BarcodeSignOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示条形码签名选项。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

表示条形码签名选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [BarcodeSignOptions()](#BarcodeSignOptions--) | 使用默认值初始化 BarcodeSignOptions 类的一个新实例。 |
|
|  | [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | 使用文本初始化 BarcodeSignOptions 类的一个新实例。 |
|
|  | [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | 使用文本初始化 BarcodeSignOptions 类的一个新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | 获取或设置条形码类型。 |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | 获取或设置条形码类型。 |
|
|  | [getForeColor()](#getForeColor--) | 获取或设置条形码条的前景颜色 |
使用此属性可能导致验证出现问题。
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | 获取或设置条形码条的前景颜色 |
使用此属性可能导致验证出现问题。
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | 获取或设置条形码条的前景颜色 |
使用此属性可能导致验证出现问题。
|
|  | [getInnerMargins()](#getInnerMargins--) | 获取或设置条形码元素与结果图像边框之间的间距。 |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | 获取或设置条形码元素与结果图像边框之间的间距。 |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | 获取或设置结果条形码图像中文本的对齐方式。 |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | 获取或设置结果条形码图像中文本的对齐方式。 |
|
|  | [getReturnContent()](#getReturnContent--) | 获取或设置标志，以获取放置在文档页面上的签名的条形码图像内容。 |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | 获取或设置标志，以获取放置在文档页面上的签名的条形码图像内容。 |
|
|  | [getReturnContentType()](#getReturnContentType--) | 指定在启用 ReturnContent 属性时返回的条形码签名图像内容的文件类型。 |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | 指定在启用 ReturnContent 属性时返回的条形码签名图像内容的文件类型。 |
|
|  | [validate()](#validate--) | 用于验证条形码选项参数的内部方法。 |
|
|  | [toString()](#toString--) | 覆盖字符串转换。 |
|
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


使用默认值初始化 BarcodeSignOptions 类的一个新实例。


### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


使用文本初始化 BarcodeSignOptions 类的一个新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文本 | java.lang.String | 条形码文本 |
|

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


使用文本初始化 BarcodeSignOptions 类的一个新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文本 | java.lang.String | 条形码文本 |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | 条形码编码类型请参见 [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


获取或设置条形码类型。


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


获取或设置条形码类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


获取或设置条形码条的前景颜色
使用此属性可能导致验证出现问题。请谨慎使用。


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


获取或设置条形码条的前景颜色
使用此属性可能导致验证出现问题。请谨慎使用。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


获取或设置条形码条的前景颜色
使用此属性可能导致验证出现问题。请谨慎使用。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


获取或设置条形码元素与结果图像边框之间的间距。


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


获取或设置条形码元素与结果图像边框之间的间距。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


获取或设置结果条形码图像中文本的对齐方式。
默认值为 None。


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


获取或设置结果条形码图像中文本的对齐方式。
默认值为 None。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


获取或设置标志，以获取放置在文档页面上的签名的条形码图像内容。
如果此标志设置为 true，条形码签名图像内容将按所需格式保留原始图像数据
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
默认情况下此选项是禁用的。


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


获取或设置标志，以获取放置在文档页面上的签名的条形码图像内容。
如果此标志设置为 true，条形码签名图像内容将按所需格式保留原始图像数据
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
默认情况下此选项是禁用的。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


指定在启用 ReturnContent 属性时返回的条形码签名图像内容的文件类型。
默认情况下它被设置为 Null。这意味着返回条形码图像内容的原始格式。
此图像格式在以下位置指定：
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
可能支持的值包括：FileType.JPEG、FileType.PNG、FileType.BMP。
如果提供的格式不受支持，则返回 .png 格式的条形码图像内容。


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


指定在启用 ReturnContent 属性时返回的条形码签名图像内容的文件类型。
默认情况下它被设置为 Null。这意味着返回条形码图像内容的原始格式。
此图像格式在以下位置指定：
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat))
可能支持的值包括：FileType.JPEG、FileType.PNG、FileType.BMP。
如果提供的格式不受支持，则返回 .png 格式的条形码图像内容。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


用于验证条形码选项参数的内部方法。


### toString() {#toString--}
```
public String toString()
```


覆盖字符串转换。


**Returns:**
java.lang.String - 
