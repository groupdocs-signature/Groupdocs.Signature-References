---
title: "MetadataSignOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示元数据签名选项。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.signature.options.sign/metadatasignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
```
public class MetadataSignOptions extends SignOptions
```

表示元数据签名选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [MetadataSignOptions()](#MetadataSignOptions--) | 使用默认值初始化 SignMetadataOptions 类的新实例。 |
|
|  | [MetadataSignOptions(ArrayList<MetadataSignature> signatures)](#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--) | 使用元数据初始化 SignMetadataOptions 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSignatures()](#getSignatures--) | 获取或设置签名的元数据。 |
|
|  | [setSignatures(MetadataSignatureCollection value)](#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-) | 获取或设置签名的元数据。 |
|
|  | [getDataEncryption()](#getDataEncryption--) | 获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以对 QR-Code 签名文本或数据属性进行编码和解码。 |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | 获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以对 QR-Code 签名文本或数据属性进行编码和解码。 |
|
|  | [addPdfSignature(String name, Object value, String tag)](#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-) | 使用传入的参数创建新的 PdfMetadataSignature 并将其添加到集合中。 |
|
|  | [addImageSignature(int id, Object value)](#addImageSignature-int-java.lang.Object-) | 使用传入的参数创建新的 ImageMetadataSignature 并将其添加到集合中。 |
|
|  | [add(MetadataSignature metadataSignature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | 将现有的 MetadataSignature 实例添加到集合中。 |
|
|  | [validate()](#validate--) | 内部方法，用于验证选项参数。 |
|
|  | [toString()](#toString--) | 覆盖字符串转换。 |
|
| [signature()](#signature--) |  |
### MetadataSignOptions() {#MetadataSignOptions--}
```
public MetadataSignOptions()
```


使用默认值初始化 SignMetadataOptions 类的新实例。


### MetadataSignOptions(ArrayList<MetadataSignature> signatures) {#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--}
```
public MetadataSignOptions(ArrayList<MetadataSignature> signatures)
```


使用元数据初始化 SignMetadataOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | signatures | java.util.ArrayList<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature> | Metadata 签名的集合 [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)。 |
|

### getSignatures() {#getSignatures--}
```
public final MetadataSignatureCollection getSignatures()
```


获取或设置签名的元数据。


**Returns:**
[MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection)
### setSignatures(MetadataSignatureCollection value) {#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-}
```
public final void setSignatures(MetadataSignatureCollection value)
```


获取或设置签名的元数据。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection) |  |

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

### addPdfSignature(String name, Object value, String tag) {#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public final PdfMetadataSignature addPdfSignature(String name, Object value, String tag)
```


使用传入的参数创建新的 PdfMetadataSignature 并将其添加到集合中。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | Metadata 签名对象的名称 |
|
|  | 值 | java.lang.Object | Metadata 签名的值 |
|
|  | 标签 | java.lang.String | Metadata 签名的前缀标签 |
|

**Returns:**
[PdfMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### addImageSignature(int id, Object value) {#addImageSignature-int-java.lang.Object-}
```
public final ImageMetadataSignature addImageSignature(int id, Object value)
```


使用传入的参数创建新的 ImageMetadataSignature 并将其添加到集合中。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 标识符 | int | 唯一标识符 Image Metadata Signature 名称。请参阅参考文献以获取 Exif 标签规范中可能的 id 值。 |
|
|  | 值 | java.lang.Object | Metadata 值 |
|

**Returns:**
[ImageMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### add(MetadataSignature metadataSignature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final MetadataSignOptions add(MetadataSignature metadataSignature)
```


将现有的 MetadataSignature 实例添加到集合中。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | metadataSignature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | 要添加的现有 MetadataSignature 实例 |
|

**Returns:**
[MetadataSignOptions](../../com.groupdocs.signature.options.sign/metadatasignoptions) - Instance itself

### validate() {#validate--}
```
public void validate()
```


内部方法，用于验证选项参数。


### toString() {#toString--}
```
public String toString()
```


覆盖字符串转换。


**Returns:**
java.lang.String - 
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
