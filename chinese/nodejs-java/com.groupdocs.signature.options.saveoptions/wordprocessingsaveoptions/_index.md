---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "文字处理文档的保存选项。"
type: docs
weight: 15
url: /zh/nodejs-java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

文字处理文档的保存选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | 使用默认值初始化 WordProcessingSaveOptions 类的新实例。 |
| [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | 使用指定的输出文件格式初始化 WordProcessingSaveOptions 类的新实例。 |
| [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | 使用指定的输出类型和覆盖标志初始化 WordProcessingSaveOptions 类的新实例。 |
| [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | 使用指定的输出文件格式和覆盖标志初始化 WordProcessingSaveOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | 获取或设置已签署文档的文件格式。 |
| [setFileFormat(int value)](#setFileFormat-int-) | 获取或设置已签署文档的文件格式。 |
| [toString()](#toString--) | 覆盖字符串转换 |
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


使用默认值初始化 WordProcessingSaveOptions 类的新实例。

### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


使用指定的输出文件格式初始化 WordProcessingSaveOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileFormat | int | 输出文件类型 [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat)。 |

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


使用指定的输出类型和覆盖标志初始化 WordProcessingSaveOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| overwriteExistingFile | boolean | 标志是否用相同的文件覆盖已签署的文件。 |

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


使用指定的输出文件格式和覆盖标志初始化 WordProcessingSaveOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileFormat | int | 输出文件类型 [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat)。 |
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


覆盖字符串转换

**Returns:**
java.lang.String -
