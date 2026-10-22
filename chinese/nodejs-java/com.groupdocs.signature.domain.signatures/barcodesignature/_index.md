---
title: "BarcodeSignature"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "包含 Barcode Signature 属性。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

包含 Barcode Signature 属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | 使用在搜索过程后获得的签名标识符初始化 BarcodeSignature 对象。 |
| [BarcodeSignature()](#BarcodeSignature--) | 使用默认参数初始化 BarcodeSignature。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | 指定条形码编码类型。 |
| [getText()](#getText--) | 指定条形码的文本。 |
| [getFormat()](#getFormat--) | 指定条形码签名图像的格式。 |
| [getContent()](#getContent--) | 指定条形码二进制数据图像内容，类型为 Format (\\#getFormat.getFormat/\\#setFormat(FileType).setFormat(FileType))。 |
| [equals(Object signature)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较签名属性 |
| [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法。 |
| [deepClone()](#deepClone--) | 克隆 Barcode Signature 实例。 |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


使用在搜索过程后获得的签名标识符初始化 BarcodeSignature 对象。此唯一标识符用于从文档签名信息层查找该签名的其他属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signatureId | java.lang.String | 通过 Signature 类的 Sign 或 Search 方法获取的唯一签名标识符 [Signature](../../com.groupdocs.signature/signature)。 |

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


使用默认参数初始化 BarcodeSignature。

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


指定条形码编码类型。

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


指定条形码的文本。

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


指定条形码签名图像的格式。

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


指定条形码二进制数据图像内容，类型为 Format (\\#getFormat.getFormat/\\#setFormat(FileType).setFormat(FileType))。默认情况下此属性不会被设置。使用属性 BarcodeSearchOptions.ReturnContent ([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions\\#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions\\#setReturnContent-boolean-)) 来启用此功能。

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


克隆 Barcode Signature 实例。

**Returns:**
java.lang.Object - 返回克隆的 Barcode Signature 实例。
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| 图像 | java.awt.image.BufferedImage |  |

