---
title: "PresentationMetadataSignature"
second_title: "GroupDocs.Signature for Java API 参考"
description: "包含演示文稿元数据签名属性。"
type: docs
weight: 16
url: /zh/java/com.groupdocs.signature.domain.signatures.metadata/presentationmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PresentationMetadataSignature extends MetadataSignature
```

包含演示文稿元数据签名属性。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PresentationMetadataSignature(String name)](#PresentationMetadataSignature-java.lang.String-) | 创建具有预定义名称和空值的演示文稿元数据签名 |
|
|  | [PresentationMetadataSignature(String name, Object value)](#PresentationMetadataSignature-java.lang.String-java.lang.Object-) | 创建具有预定义值的演示文稿元数据签名 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [deepClone()](#deepClone--) | 克隆 Metadata Signature 实例。 |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | 克隆具有给定值的幻灯片元数据签名实例。 |
|
|  | [toString()](#toString--) | 使用覆盖的 ToString() 方法转换为字符串 |
|
|  | [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | 使用指定格式转换为字符串 |
|
### PresentationMetadataSignature(String name) {#PresentationMetadataSignature-java.lang.String-}
```
public PresentationMetadataSignature(String name)
```


创建具有预定义名称和空值的演示文稿元数据签名


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 演示文稿元数据签名名称 |
|

### PresentationMetadataSignature(String name, Object value) {#PresentationMetadataSignature-java.lang.String-java.lang.Object-}
```
public PresentationMetadataSignature(String name, Object value)
```


创建具有预定义值的演示文稿元数据签名


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | Metadata 签名对象的名称 |
|
|  | 值 | java.lang.Object | Metadata 签名的值 |
|

### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆 Metadata Signature 实例。


**Returns:**
java.lang.Object - 返回克隆的 Metadata Signature 实例

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


克隆具有给定值的幻灯片元数据签名实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.Object | 新克隆对象的值。 |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

### toString() {#toString--}
```
public String toString()
```


使用覆盖的 ToString() 方法转换为字符串


**Returns:**
java.lang.String - 将元数据签名值作为 String 返回。

<br />

*** ** * ** ***

将布尔属性转换为 "True" 或 "False"。对于其他数据类型，将使用默认的数据格式提供程序。

<br />


### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


使用指定格式转换为字符串


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 格式 | java.lang.String | 数据格式字符串。 |
|
|  | 提供程序 | com.aspose.ms.System.IFormatProvider | 用于数据转换操作的格式数据提供程序。 |

<br />

*** ** * ** ***

将布尔属性转换为 "True" 或 "False"。

<br />

|

**Returns:**
java.lang.String - 将元数据签名值作为 String 返回。

