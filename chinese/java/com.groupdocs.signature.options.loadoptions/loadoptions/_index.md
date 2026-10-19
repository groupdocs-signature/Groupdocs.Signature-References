---
title: "LoadOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "允许在打开文档进行签名时指定额外选项，例如密码。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

在打开文档进行签名时，允许指定附加选项（例如密码）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | 初始化 LoadOptions 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 获取或设置用于打开受保护文档的密码。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 获取或设置用于打开受保护文档的密码。 |
|
|  | [getLoadExternalResources()](#getLoadExternalResources--) | 获取或设置指定是否应加载外部文档资源的选项。 |
|
|  | [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | 获取或设置指定是否应加载外部文档资源的选项。 |
|
|  | [getPermissions()](#getPermissions--) | PDF 文档的权限，例如打印、修改和数据提取。 |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | 内部设置器，供文档加载处理器记录从文件解析的权限。 |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


初始化 LoadOptions 类的新实例。


### getPassword() {#getPassword--}
```
public final String getPassword()
```


获取或设置用于打开受保护文档的密码。
它也将用于将已签名的文档保存为受保护状态。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


获取或设置用于打开受保护文档的密码。
它也将用于将已签名的文档保存为受保护状态。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


获取或设置指定是否应加载外部文档资源的选项。
将此选项设置为禁用 (false) 可为包含大量或大型外部资源链接的文档节省加载时间。
默认情况下，该值为启用 (true)。


**Returns:**
boolean
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


获取或设置指定是否应加载外部文档资源的选项。
将此选项设置为禁用 (false) 可为包含大量或大型外部资源链接的文档节省加载时间。
默认情况下，该值为启用 (true)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


PDF 文档的权限，例如打印、修改和数据提取。
仅适用于 PDF 文档。只读 \u2014 在加载文档时自动填充。
该值是来自 [Permissions](../../com.groupdocs.signature.options/permissions) 的标志组合。


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


内部设置器，供文档加载处理器记录从文件解析的权限。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Integer |  |

