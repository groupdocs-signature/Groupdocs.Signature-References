---
title: "MetadataSignatureCollection"
second_title: "GroupDocs.Signature for Java API 参考"
description: "元数据签名对象的集合。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class MetadataSignatureCollection implements Iterable<MetadataSignature>
```

元数据签名对象的集合。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [MetadataSignatureCollection()](#MetadataSignatureCollection--) | 创建 Metadata 签名的集合。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getCount()](#getCount--) | 获取集合中项目的数量。 |
|
|  | [clear()](#clear--) | 从集合中移除所有项目。 |
|
|  | [contains(String name)](#contains-java.lang.String-) | 如果集合中存在具有指定名称的 Metadata，则返回 true。 |
|
|  | [indexOf(String name)](#indexOf-java.lang.String-) | 根据名称获取属性的索引。 |
|
|  | [remove(String name)](#remove-java.lang.String-) | 从集合中移除具有指定名称的 Metadata Signature。 |
|
|  | [removeAt(int index)](#removeAt-int-) | 在指定索引处移除 Metadata Signature。 |
|
|  | [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | 将 Metadata Signature 对象添加到集合。 |
|
|  | [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | 添加 Metadata Signature 集合。 |
|
|  | [deepClone()](#deepClone--) | 克隆带有 Metadata Signature 项目的 Metadata Signature Collection 类。 |
|
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


创建 Metadata 签名的集合。


### getCount() {#getCount--}
```
public final int getCount()
```


获取集合中项目的数量。


**Returns:**
int
### clear() {#clear--}
```
public final void clear()
```


从集合中移除所有项目。


### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


如果集合中存在具有指定名称的 Metadata，则返回 true。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 属性的大小写不敏感名称。 |
|

**Returns:**
boolean - 如果集合中存在该 Metadata 则为 true；否则为 false。

### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


根据名称获取属性的索引。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | MetadataSignature 的大小写不敏感名称。 |
|

**Returns:**
int - 零基索引。如果未找到则为负值。

### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


从集合中移除具有指定名称的 Metadata Signature。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | Metadata Signature 的大小写不敏感名称。 |
|

**Returns:**
boolean -
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


在指定索引处移除 Metadata Signature。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 索引 | int | 零基索引。 |
|

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


将 Metadata Signature 对象添加到集合。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | 要添加到集合的 Metadata 签名。 |

<br />

*** ** * ** ***

如果名称值在整个现有集合中不唯一，则抛出异常

<br />

|

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


添加 Metadata Signature 集合。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | 要添加的签名集合。 |

<br />

*** ** * ** ***

如果名称值在整个现有集合中不唯一，则抛出异常

<br />

|

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


克隆带有 Metadata Signature 项目的 Metadata Signature Collection 类。


**Returns:**
java.lang.Object - 返回带有克隆的 Signature 项目的复制实例

