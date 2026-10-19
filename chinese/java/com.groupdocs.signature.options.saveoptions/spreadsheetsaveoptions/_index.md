---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "电子表格文档的保存选项。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

电子表格文档的保存选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | 使用默认值初始化 SpreadsheetSaveOptions 类的新实例。 |
|
|  | [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | 使用预定义的输出文件格式初始化 SpreadsheetSaveOptions 类的新实例。 |
|
|  | [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | 使用指定的输出类型和覆盖标志初始化 SpreadsheetSaveOptions 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | 获取或设置已签署文档的文件格式。 |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | 获取或设置已签署文档的文件格式。 |
|
|  | [toString()](#toString--) | 覆盖字符串转换。 |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


使用默认值初始化 SpreadsheetSaveOptions 类的新实例。


### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


使用预定义的输出文件格式初始化 SpreadsheetSaveOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileFormat | int | 指定输出文件格式。 |
|

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


使用指定的输出类型和覆盖标志初始化 SpreadsheetSaveOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileFormat | int | 指定输出文件格式。 |
|
|  | overwriteExistingFile | boolean | 标志是否使用相同文件覆盖已签署的文件。 |
|

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
