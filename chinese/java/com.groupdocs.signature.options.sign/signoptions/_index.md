---
title: "SignOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示签名选项。"
type: docs
weight: 16
url: /zh/java/com.groupdocs.signature.options.sign/signoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SignOptions
```

表示签名选项。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | 获取或设置用于签名的文档页码。 |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | 获取或设置用于签名的文档页码。 |
|
|  | [getAllPages()](#getAllPages--) | 在所有文档页上放置签名。 |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | 在所有文档页上放置签名。 |
|
|  | [getAppearance()](#getAppearance--) | 附加签名外观。 |
|
|  | [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | 附加签名外观。 |
|
|  | [getExtensions()](#getExtensions--) | 签名扩展。 |
|
|  | [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | 签名扩展。 |
|
|  | [getPagesSetup()](#getPagesSetup--) | 指定要签署页面的选项。 |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | 指定要签署页面的选项。 |
|
|  | [getSignatureType()](#getSignatureType--) | 获取签名类型 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
|
|  | [getDocumentType()](#getDocumentType--) | 获取或设置签名选项的文档类型 [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [setDocumentType(int value)](#setDocumentType-int-) | 获取或设置签名选项的文档类型 [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [getZOrder()](#getZOrder--) | 获取或设置文本签名的 Z 顺序位置。 |
|
|  | [setZOrder(int value)](#setZOrder-int-) | 获取或设置文本签名的 Z 顺序位置。 |
|
|  | [getHashAlgorithm()](#getHashAlgorithm--) | 获取或设置用于加密操作的哈希算法。 |
|
|  | [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | 获取或设置用于加密操作的哈希算法。 |
|
|  | [toString()](#toString--) | 覆盖字符串转换。 |
|
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


获取或设置用于签名的文档页码。
最小值和默认值为 1。


**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


获取或设置用于签名的文档页码。
最小值和默认值为 1。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


在所有文档页上放置签名。


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


在所有文档页上放置签名。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


附加签名外观。


**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


附加签名外观。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


签名扩展。


**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


签名扩展。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


指定要签署页面的选项。


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


指定要签署页面的选项。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


获取签名类型 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)


**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


获取或设置签名选项的文档类型 [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


获取或设置签名选项的文档类型 [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


获取或设置文本签名的 Z 顺序位置。
确定重叠签名的显示顺序。


**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


获取或设置文本签名的 Z 顺序位置。
确定重叠签名的显示顺序。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHashAlgorithm() {#getHashAlgorithm--}
```
public final int getHashAlgorithm()
```


获取或设置用于加密操作的哈希算法。
仅在 PDF 文件中的数字签名中受支持。
值是 [HashAlgorithm](../../com.groupdocs.signature.domain.enums/hashalgorithm) 上的常量之一。


**Returns:**
int
### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


获取或设置用于加密操作的哈希算法。
仅在 PDF 文件中的数字签名中受支持。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### toString() {#toString--}
```
public String toString()
```


覆盖字符串转换。


**Returns:**
java.lang.String - 
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
