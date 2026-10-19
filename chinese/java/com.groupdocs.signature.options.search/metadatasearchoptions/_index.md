---
title: "MetadataSearchOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示元数据签名的抽象搜索选项。"
type: docs
weight: 15
url: /zh/java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

表示元数据签名的抽象搜索选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [MetadataSearchOptions()](#MetadataSearchOptions--) | 使用默认值初始化 SearchMetadataOptions 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getName()](#getName--) | 指定元数据签名名称（如果需要搜索和匹配）。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | 指定元数据签名名称（如果需要搜索和匹配）。 |
|
|  | [getNameMatchType()](#getNameMatchType--) | 获取或设置元数据名称匹配类型搜索。 |
|
|  | [setNameMatchType(int value)](#setNameMatchType-int-) | 获取或设置元数据名称匹配类型搜索。 |
|
|  | [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | 指示是否应将内置文档属性（如文档统计信息、信息等）包含在搜索结果中。 |
|
|  | [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | 指示是否应将内置文档属性（如文档统计信息、信息等）包含在搜索结果中。 |
|
|  | [getDataEncryption()](#getDataEncryption--) | 获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以对 QR-Code 签名文本或数据属性进行编码和解码。 |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | 获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以对 QR-Code 签名文本或数据属性进行编码和解码。 |
|
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


使用默认值初始化 SearchMetadataOptions 类的新实例。


### getName() {#getName--}
```
public final String getName()
```


指定元数据签名名称（如果需要搜索和匹配）。


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


指定元数据签名名称（如果需要搜索和匹配）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


获取或设置元数据名称匹配类型搜索。仅在设置 Name 属性时使用。


**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


获取或设置元数据名称匹配类型搜索。仅在设置 Name 属性时使用。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


指示是否应将内置文档属性（如文档统计信息、信息等）包含在搜索结果中。
此标志在演示文稿、电子表格和文字处理文档文件类型中有效。


**Returns:**
boolean
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


指示是否应将内置文档属性（如文档统计信息、信息等）包含在搜索结果中。
此标志在演示文稿、电子表格和文字处理文档文件类型中有效。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以对 QR-Code 签名文本或数据属性进行编码和解码。


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以对 QR-Code 签名文本或数据属性进行编码和解码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

