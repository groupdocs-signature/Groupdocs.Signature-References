---
title: "PdfSaveOptions"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "PDF 文档的保存选项。"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

PDF 文档的保存选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | 使用默认值初始化 PdfSaveOptions 类的新实例。 |
| [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | 使用指定的输出文件格式初始化 PdfSaveOptions 类的新实例。 |
| [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | 使用覆盖标志初始化 PdfSaveOptions 类的新实例。 |
| [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | 使用指定的输出文件格式和覆盖标志初始化 PdfSaveOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | 获取或设置已签署文档的文件格式。 |
| [setFileFormat(int value)](#setFileFormat-int-) | 获取或设置已签署文档的文件格式。 |
| [toString()](#toString--) | 覆盖字符串转换。 |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


使用默认值初始化 PdfSaveOptions 类的新实例。

### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


使用指定的输出文件格式初始化 PdfSaveOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileFormat | int | 输出文件类型 [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat)。 |

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


使用覆盖标志初始化 PdfSaveOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| overwriteExistingFile | boolean | 标志是否用相同的文件覆盖已签署的文件。 |

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


使用指定的输出文件格式和覆盖标志初始化 PdfSaveOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileFormat | int | 输出文件类型 [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat)。 |
| overwriteExistingFile | boolean | 标志是否用相同的文件覆盖已签署的文件。 |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


获取或设置已签署文档的文件格式。

**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


获取或设置已签署文档的文件格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### toString() {#toString--}
```
public String toString()
```


覆盖字符串转换。

**Returns:**
java.lang.String -
