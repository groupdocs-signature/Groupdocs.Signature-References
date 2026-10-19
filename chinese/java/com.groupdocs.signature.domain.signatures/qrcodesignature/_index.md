---
title: "QrCodeSignature"
second_title: "GroupDocs.Signature for Java API 参考"
description: "包含二维码签名属性。"
type: docs
weight: 16
url: /zh/java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

包含二维码签名属性。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | 使用在搜索过程后获得的签名标识符初始化 QrCodeSignature 对象。 |
|
| [QrCodeSignature()](#QrCodeSignature--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | 指定 QR 码编码类型。 |
|
|  | [getText()](#getText--) | 指定 QR 码的文本。 |
|
|  | [getFormat()](#getFormat--) | 指定 QR 码签名图像的格式。 |
|
|  | [getContent()](#getContent--) | 指定 QR-code 二进制数据图像内容的类型 |
格式
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | 通过反序列化从 QR-Code 签名文本获取对象。 |
|
|  | [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | 通过反序列化从 QR-Code 签名文本获取对象。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较签名属性 |
|
|  | [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法 |
|
|  | [deepClone()](#deepClone--) | 克隆 QR-Code 签名实例。 |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


使用在搜索过程后获得的签名标识符初始化 QrCodeSignature 对象。
此唯一标识符用于从文档签名信息层查找此签名的附加属性。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | signatureId | java.lang.String | 通过签名或搜索方法获取的唯一签名标识符。 |
|

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


指定 QR 码编码类型。


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


指定 QR 码的文本。


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


指定 QR 码签名图像的格式。


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


指定 QR-code 二进制数据图像内容的类型
格式
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
默认情况下，此属性不会被设置。
使用属性
QrCodeSearchOptions.ReturnContent
([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions#setReturnContent-boolean-)) 以启用此功能。


**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


通过反序列化从 QR-Code 签名文本获取对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | java.lang.Class<T> |  |

**Returns:**
T -
T
: 从 QR-Code 文本反序列化的对象类型

### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


通过反序列化从 QR-Code 签名文本获取对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | 设置自定义数据加密实现 |


T
: 从 QR-Code 文本反序列化的对象类型
|
| 类型 | java.lang.Class<T> |  |

**Returns:**
T -
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


克隆 QR-Code 签名实例。


**Returns:**
java.lang.Object - 返回克隆的 QR-code 签名实例。

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| 图像 | java.awt.image.BufferedImage |  |

