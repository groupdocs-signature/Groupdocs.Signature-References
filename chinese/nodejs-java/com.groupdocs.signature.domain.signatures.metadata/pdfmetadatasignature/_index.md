---
title: "PdfMetadataSignature"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "包含 PDF 元数据签名属性。"
type: docs
weight: 14
url: /zh/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

包含 PDF 元数据签名属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | 创建具有预定义名称和空值的 Pdf Metadata 签名 |
| [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | 创建具有预定义值的 Pdf Metadata 签名 |
| [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | 创建具有预定义值的 Pdf Metadata 签名 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTagPrefix()](#getTagPrefix--) | Pdf Metadata 签名名称的前缀标签。 |
| [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | Pdf Metadata 签名名称的前缀标签。 |
| [equals(Object signature)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较签名属性 |
| [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法。 |
| [deepClone()](#deepClone--) | 克隆 Metadata Signature 实例。 |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | 克隆具有给定值的 Pdf Metadata Signature 实例。 |
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


创建具有预定义名称和空值的 Pdf Metadata 签名

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | Pdf Metadata Signature 名称 |

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


创建具有预定义值的 Pdf Metadata 签名

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | Metadata 签名对象的名称 |
| 值 | java.lang.Object | Metadata 签名的值 |

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


创建具有预定义值的 Pdf Metadata 签名

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | Metadata 签名对象的名称 |
| 值 | java.lang.Object | Metadata 签名的值 |
| 标签 | java.lang.String | Metadata 签名的前缀标签 |

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


Pdf Metadata 签名名称的前缀标签。默认情况下，此属性设置为 "xmp"。可能的值有

**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


Pdf Metadata 签名名称的前缀标签。默认情况下，此属性设置为 "xmp"。可能的值有

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


覆盖 Equals 方法以比较签名属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 签名 | java.lang.Object | 用于比较的 Signature 对象。 |

**Returns:**
boolean - 如果传入的签名对象具有相同类型且所有属性都等于此实例的属性，则返回 true。
### hashCode() {#hashCode--}
```
public int hashCode()
```


覆盖 GetHashCode 方法。

**Returns:**
int - 签名哈希码
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


克隆具有给定值的 Pdf Metadata Signature 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object | 新克隆对象的值。 |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
