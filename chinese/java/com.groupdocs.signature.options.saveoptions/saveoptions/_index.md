---
title: "SaveOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "允许在保存待签署的文档时指定额外选项，例如密码。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

在保存待签名文档时允许指定额外选项（如密码）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | 使用默认值初始化 SaveOptions 类的新实例。 |
|
|  | [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | 使用指定的输出类型和覆盖标志初始化 SaveOptions 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | 获取或设置是否用新输出文件覆盖已有文件。 |
|
|  | [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | 获取或设置是否用新输出文件覆盖已有文件。 |
|
|  | [getPassword()](#getPassword--) | 获取或设置用于以密码保护方式保存已签署文档的密码。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 获取或设置用于以密码保护方式保存已签署文档的密码。 |
|
|  | [getUseOriginalPassword()](#getUseOriginalPassword--) | 获取或设置是否使用 LoadOptions 中的密码来保存受保护的已签署文档。 |
|
|  | [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | 获取或设置是否使用 LoadOptions 中的密码来保存受保护的已签署文档。 |
|
|  | [getAddMissingExtenstion()](#getAddMissingExtenstion--) | 获取或设置在输出文件路径缺少扩展名时自动添加扩展名的标志 |
默认值为 false。
|
|  | [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | 获取或设置在输出文件路径缺少扩展名时自动添加扩展名的标志 |
默认值为 false。
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


使用默认值初始化 SaveOptions 类的新实例。


### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


使用指定的输出类型和覆盖标志初始化 SaveOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | 标志是否使用相同文件覆盖已签署的文件。 |
|

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


获取或设置是否用新输出文件覆盖已有文件。
否则将创建带有数字后缀的新文件。


**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


获取或设置是否用新输出文件覆盖已有文件。
否则将创建带有数字后缀的新文件。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


获取或设置用于以密码保护方式保存已签署文档的密码。
此属性不支持图像文档。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


获取或设置用于以密码保护方式保存已签署文档的密码。
此属性不支持图像文档。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


获取或设置是否使用 LoadOptions 中的密码来保存受保护的已签署文档。
默认值为 true。
此属性不支持图像文档。


**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


获取或设置是否使用 LoadOptions 中的密码来保存受保护的已签署文档。
默认值为 true。
此属性不支持图像文档。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


获取或设置在输出文件路径缺少扩展名时自动添加扩展名的标志
默认值为 false。


**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


获取或设置在输出文件路径缺少扩展名时自动添加扩展名的标志
默认值为 false。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

