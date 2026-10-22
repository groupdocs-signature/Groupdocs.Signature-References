---
title: "ExportImageSaveOptions"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "导出文档为图像的保存选项。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

导出文档为图像的保存选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ExportImageSaveOptions()](#ExportImageSaveOptions--) | 使用默认值初始化 ExportAsImageSaveOptions 类的新实例。 |
| [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | 使用指定的文件格式初始化 ExportAsImageSaveOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | 获取或设置要导出的文档页码。 |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | 获取或设置要导出的文档页码。 |
| [getExportAllPages()](#getExportAllPages--) | 标志以导出每一页。 |
| [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | 标志以导出每一页。 |
| [getPagesSetup()](#getPagesSetup--) | 用于指定要签署的页面的选项。 |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | 用于指定要签署的页面的选项。 |
| [getPageColumns()](#getPageColumns--) | 获取或设置导出图像的列数。 |
| [setPageColumns(int value)](#setPageColumns-int-) | 获取或设置导出图像的列数。 |
| [getBorder()](#getBorder--) | 获取或设置图像边框设置。 |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | 获取或设置图像边框设置。 |
| [getTiffMultipage()](#getTiffMultipage--) | 将文档页面放置在 Tiff 图像的不同帧中。 |
| [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | 将文档页面放置在 Tiff 图像的不同帧中。 |
| [toString()](#toString--) | 覆盖字符串转换。 |
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


使用默认值初始化 ExportAsImageSaveOptions 类的新实例。

### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


使用指定的文件格式初始化 ExportAsImageSaveOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileFormat | int | 输出图像文件格式。 |

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


获取或设置要导出的文档页码。最小值为 1。

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


获取或设置要导出的文档页码。最小值为 1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


标志以导出每一页。

**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


标志以导出每一页。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


用于指定要签署的页面的选项。

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


用于指定要签署的页面的选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


获取或设置导出图像的列数。如果需要将图像放在一行中，请使用此属性。

**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


获取或设置导出图像的列数。如果需要将图像放在一行中，请使用此属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


获取或设置图像边框设置。默认情况下此值未设置。

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


获取或设置图像边框设置。默认情况下此值未设置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


将文档页面放置在 Tiff 图像的不同帧中。

**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


将文档页面放置在 Tiff 图像的不同帧中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### toString() {#toString--}
```
public String toString()
```


覆盖字符串转换。

**Returns:**
java.lang.String -
