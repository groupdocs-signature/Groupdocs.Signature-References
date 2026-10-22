---
title: "CertificateMetadataSignature"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "包含证书元数据签名属性。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/certificatemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class CertificateMetadataSignature extends MetadataSignature
```

包含证书元数据签名属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CertificateMetadataSignature(String name)](#CertificateMetadataSignature-java.lang.String-) | 创建具有预定义名称和空值的 Certificate Metadata Signature。 |
| [CertificateMetadataSignature(String name, Object value)](#CertificateMetadataSignature-java.lang.String-java.lang.Object-) | 创建具有预定义值的 Certificate Metadata Signature。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 克隆 Metadata Signature 实例。 |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | 克隆具有给定值的 Certificate Metadata Signature 实例。 |
| [toString()](#toString--) | 使用重写的 ToString() 方法转换为字符串。 |
| [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | 使用指定格式转换为字符串。 |
### CertificateMetadataSignature(String name) {#CertificateMetadataSignature-java.lang.String-}
```
public CertificateMetadataSignature(String name)
```


创建具有预定义名称和空值的 Certificate Metadata Signature。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | Certificate Metadata Signature 名称。 |

### CertificateMetadataSignature(String name, Object value) {#CertificateMetadataSignature-java.lang.String-java.lang.Object-}
```
public CertificateMetadataSignature(String name, Object value)
```


创建具有预定义值的 Certificate Metadata Signature。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | Metadata 签名对象的名称。 |
| 值 | java.lang.Object | Metadata 签名的值。 |

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


克隆具有给定值的 Certificate Metadata Signature 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object | 新克隆对象的值。 |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
### toString() {#toString--}
```
public String toString()
```


使用重写的 ToString() 方法转换为字符串。

**Returns:**
java.lang.String - 将元数据签名的值返回为 String。

--------------------

将布尔属性转换为 "True" 或 "False"。对于其他数据类型，将使用默认的数据格式提供程序。
### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


使用指定格式转换为字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 格式 | java.lang.String | 数据格式字符串。 |
|  | 提供程序 | com.aspose.ms.System.IFormatProvider | 用于数据转换操作的格式化数据提供程序。 |

--------------------

将布尔属性转换为 "True" 或 "False"。 |

**Returns:**
java.lang.String - 将元数据签名的值返回为 String。
