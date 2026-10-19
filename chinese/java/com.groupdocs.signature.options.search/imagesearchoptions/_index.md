---
title: "ImageSearchOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示图像签名的搜索选项。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.signature.options.search/imagesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class ImageSearchOptions extends SearchOptions
```

表示图像签名的搜索选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [ImageSearchOptions()](#ImageSearchOptions--) | 使用默认值初始化 ImageSearchOptions 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getReturnContent()](#getReturnContent--) | 获取或设置标志，以获取文档页面上签名的图像内容。 |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | 获取或设置标志，以获取文档页面上签名的图像内容。 |
|
|  | [getMinContentSize()](#getMinContentSize--) | 对于非零值，此标志指定搜索条件的图像最小尺寸。 |
|
|  | [setMinContentSize(long value)](#setMinContentSize-long-) | 对于非零值，此标志指定搜索条件的图像最小尺寸。 |
|
|  | [getMaxContentSize()](#getMaxContentSize--) | 对于非零值，此标志指定搜索条件的图像最大尺寸。 |
|
|  | [setMaxContentSize(long value)](#setMaxContentSize-long-) | 对于非零值，此标志指定搜索条件的图像最大尺寸。 |
|
|  | [getReturnContentType()](#getReturnContentType--) | 当启用 ReturnContent 属性时，指定图像签名返回内容的文件类型。 |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | 当启用 ReturnContent 属性时，指定图像签名返回内容的文件类型。 |
|
### ImageSearchOptions() {#ImageSearchOptions--}
```
public ImageSearchOptions()
```


使用默认值初始化 ImageSearchOptions 类的新实例。


### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


获取或设置标志，以获取文档页面上签名的图像内容。
如果此标志设置为 true，图像签名内容将保持所需格式的原始图像数据。
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
默认情况下此选项是禁用的。


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


获取或设置标志，以获取文档页面上签名的图像内容。
如果此标志设置为 true，图像签名内容将保持所需格式的原始图像数据。
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
默认情况下此选项是禁用的。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getMinContentSize() {#getMinContentSize--}
```
public final long getMinContentSize()
```


对于非零值，此标志指定搜索条件的图像最小尺寸。
默认情况下，此标志设置为零，不影响搜索结果。


**Returns:**
long
### setMinContentSize(long value) {#setMinContentSize-long-}
```
public final void setMinContentSize(long value)
```


对于非零值，此标志指定搜索条件的图像最小尺寸。
默认情况下，此标志设置为零，不影响搜索结果。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### getMaxContentSize() {#getMaxContentSize--}
```
public final long getMaxContentSize()
```


对于非零值，此标志指定搜索条件的图像最大尺寸。
默认情况下，此标志设置为零，不影响搜索结果。


**Returns:**
long
### setMaxContentSize(long value) {#setMaxContentSize-long-}
```
public final void setMaxContentSize(long value)
```


对于非零值，此标志指定搜索条件的图像最大尺寸。
默认情况下，此标志设置为零，不影响搜索结果。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


当启用 ReturnContent 属性时，指定图像签名返回内容的文件类型。
默认情况下，它设置为 Null。这意味着返回原始格式的图像内容。
此图像格式在以下位置指定：
ImageSignature.Format

可能支持的值包括：FileType.JPEG、FileType.PNG、FileType.BMP。
如果提供的格式不受支持，则返回原始格式的图像内容。


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


当启用 ReturnContent 属性时，指定图像签名返回内容的文件类型。
默认情况下，它设置为 Null。这意味着返回原始格式的图像内容。
此图像格式在以下位置指定：
ImageSignature.Format

可能支持的值包括：FileType.JPEG、FileType.PNG、FileType.BMP。
如果提供的格式不受支持，则返回原始格式的图像内容。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

