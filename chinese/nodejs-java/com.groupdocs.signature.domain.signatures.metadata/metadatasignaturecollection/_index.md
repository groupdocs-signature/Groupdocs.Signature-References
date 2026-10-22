---
title: "MetadataSignatureCollection"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "元数据签名对象的集合。"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
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
| [MetadataSignatureCollection()](#MetadataSignatureCollection--) | 创建 Metadata 签名的集合。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 获取集合中项目的数量。 |
| [clear()](#clear--) | 从集合中移除所有项目。 |
| [contains(String name)](#contains-java.lang.String-) | 如果集合中存在具有指定名称的 Metadata，则返回 true。 |
| [indexOf(String name)](#indexOf-java.lang.String-) | 根据名称获取属性的索引。 |
| [remove(String name)](#remove-java.lang.String-) | 从集合中移除具有指定名称的 Metadata Signature。 |
| [removeAt(int index)](#removeAt-int-) | 在指定索引处移除 Metadata Signature。 |
| [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | 向集合中添加 Metadata Signature 对象。 |
| [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | 添加 Metadata Signature 集合。 |
| [deepClone()](#deepClone--) | 克隆包含 Metadata Signature 项的 Metadata Signature Collection 类。 |
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
| 名称 | java.lang.String | 属性的不区分大小写的名称。 |

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
| 名称 | java.lang.String | MetadataSignature 的不区分大小写的名称。 |

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
| 名称 | java.lang.String | 不区分大小写的元数据签名名称。 |

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
| 索引 | int | 基于零的索引。 |

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


向集合中添加 Metadata Signature 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | 要添加到集合的元数据签名。 |

--------------------

如果名称值在整个现有集合中不唯一，则抛出异常 |

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


添加 Metadata Signature 集合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | 要添加的签名集合。 |

--------------------

如果名称值在整个现有集合中不唯一，则抛出异常 |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


克隆包含 Metadata Signature 项的 Metadata Signature Collection 类。

**Returns:**
java.lang.Object - 返回复制的实例，其中包含克隆的签名项
