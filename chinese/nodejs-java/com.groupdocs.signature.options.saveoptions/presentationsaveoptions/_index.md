---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "演示文稿文档的保存选项。"
type: docs
weight: 12
url: /zh/nodejs-java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

演示文稿文档的保存选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PresentationSaveOptions()](#PresentationSaveOptions--) | 使用默认值初始化 PresentationSaveOptions 类的新实例。 |
| [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | 使用指定的输出文件格式初始化 PresentationSaveOptions 类的新实例。 |
| [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | 使用指定的输出类型和覆盖标志初始化 PresentationSaveOptions 类的新实例。 |
| [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | 使用指定的输出文件格式和覆盖标志初始化 PresentationSaveOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | 获取或设置已签署文档的文件格式。 |
| [setFileFormat(int value)](#setFileFormat-int-) | 获取或设置已签署文档的文件格式。 |
| [toString()](#toString--) | 覆盖字符串转换。 |
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


使用默认值初始化 PresentationSaveOptions 类的新实例。

### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


使用指定的输出文件格式初始化 PresentationSaveOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileFormat | int | 输出文件类型 [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat)。 |

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


使用指定的输出类型和覆盖标志初始化 PresentationSaveOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| overwriteExistingFile | boolean | 标志是否用相同的文件覆盖已签署的文件。 |

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


使用指定的输出文件格式和覆盖标志初始化 PresentationSaveOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileFormat | int | 输出文件类型 [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat)。 |
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
