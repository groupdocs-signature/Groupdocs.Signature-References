---
title: "PreviewOptions"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示文档预览选项。"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

表示文档预览选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | 初始化 PreviewOptions 对象。 |
| [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | 初始化 PreviewOptions 对象。 |
| [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | 初始化 PreviewOptions 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWidth()](#getWidth--) | 获取或设置预览图像的宽度。 |
| [setWidth(int value)](#setWidth-int-) | 获取或设置预览图像的宽度。 |
| [getHeight()](#getHeight--) | 获取或设置预览图像的高度。 |
| [setHeight(int value)](#setHeight-int-) | 获取或设置预览图像的高度。 |
| [getPageNumbers()](#getPageNumbers--) | 获取或设置预览图像的页码。 |
| [setPageNumbers(int[] value)](#setPageNumbers-int---) | 获取或设置预览图像的页码。 |
| [getPreviewFormat()](#getPreviewFormat--) | 获取或设置预览图像的格式。 |
| [setPreviewFormat(int value)](#setPreviewFormat-int-) | 获取或设置预览图像的格式。 |
| [getHideSignatures()](#getHideSignatures--) | 获取或设置隐藏签名于页面预览图像的标志。 |
| [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | 获取或设置隐藏签名于页面预览图像的标志。 |
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


初始化 PreviewOptions 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | 定义创建输出页预览流方法的接口。 |
| pageNumbers | int[] | 期望的页码 |

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


初始化 PreviewOptions 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | 定义创建输出页预览流方法的接口。 |
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


初始化 PreviewOptions 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 输出文件的路径。 |
| pageNumbers | int[] | 期望的页码 |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


获取或设置预览图像的宽度。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


获取或设置预览图像的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


获取或设置预览图像的高度。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


获取或设置预览图像的高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


获取或设置预览图像的页码。

**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


获取或设置预览图像的页码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


获取或设置预览图像的格式。

**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


获取或设置预览图像的格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


获取或设置隐藏签名于页面预览图像的标志。仅标记为 IsSignature 的签名将在生成的文档页面图像中被隐藏。

**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


获取或设置隐藏签名于页面预览图像的标志。仅标记为 IsSignature 的签名将在生成的文档页面图像中被隐藏。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

