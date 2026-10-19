---
title: "ImageSignature"
second_title: "GroupDocs.Signature for Java API 参考"
description: "包含图像签名属性。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

包含图像签名属性。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | 使用在搜索过程后获得的签名标识符初始化 ImageSignature 对象。 |
|
|  | [ImageSignature()](#ImageSignature--) | 使用默认参数初始化 ImageSignature。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSize()](#getSize--) | 指定签名图像的字节大小。 |
|
|  | [setSize(int value)](#setSize-int-) | 指定签名图像的字节大小。 |
|
|  | [getFormat()](#getFormat--) | 指定签名图像的格式。 |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | 指定签名图像的格式。 |
|
|  | [getContent()](#getContent--) | 指定类型的图像二进制数据内容。 |
格式
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较签名属性 |
|
|  | [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法 |
|
|  | [deepClone()](#deepClone--) | 克隆 Barcode Signature 实例。 |
|
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


使用在搜索过程后获得的签名标识符初始化 ImageSignature 对象。
此唯一标识符用于从文档签名信息层查找此签名的附加属性。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | signatureId | java.lang.String | 由 Signature 类的 Sign 或 Search 方法获取的唯一签名标识符 [Signature](../../com.groupdocs.signature/signature)。 |
|

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


使用默认参数初始化 ImageSignature。


### getSize() {#getSize--}
```
public final int getSize()
```


指定签名图像的字节大小。


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


指定签名图像的字节大小。



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


指定签名图像的格式。


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFormat(FileType value)
```


指定签名图像的格式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getContent() {#getContent--}
```
public final byte[] getContent()
```


指定类型的图像二进制数据内容。
格式
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
默认情况下，此属性不会被设置。
使用属性
ImageSearchOptions.ReturnContent
（{ ImageSearchOptions#getReturnContent}/{ ImageSearchOptions#setReturnContent(boolean)}) 用于启用此功能。


**Returns:**
byte[]
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


覆盖 Equals 方法以比较签名属性


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 签名 | java.lang.Object | 用于比较的签名对象。 |
|

**Returns:**
boolean - 如果传入的签名对象具有相同类型且所有属性都等于此实例的属性，则返回 true。

### hashCode() {#hashCode--}
```
public int hashCode()
```


覆盖 GetHashCode 方法


**Returns:**
int - 签名哈希码

### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆 Barcode Signature 实例。


**Returns:**
java.lang.Object - 返回克隆的条形码签名实例。

