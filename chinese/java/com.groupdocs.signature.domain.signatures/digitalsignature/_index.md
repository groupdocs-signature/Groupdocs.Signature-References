---
title: "DigitalSignature"
second_title: "GroupDocs.Signature for Java API 参考"
description: "包含数字签名属性。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

包含数字签名属性。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DigitalSignature()](#DigitalSignature--) | 使用默认参数初始化 DigitalSignature。 |
|
|  | [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | 使用已知的 SignatureId 初始化 DigitalSignature。 |
|
|  | [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | 使用指定的证书创建 DigitalSignature。 |
|
|  | [DigitalSignature(X509Certificate cert, PrivateKey key)](#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | 基于 X509Certificate 证书和 PrivateKey 创建 DigitalSignature。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | 获取或设置 KeyStore 证书。 |
|
|  | [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | 获取或设置 KeyStore 证书。 |
|
|  | [getX509Certificate()](#getX509Certificate--) | 获取或设置 X509 证书。 |
|
|  | [setX509Certificate(X509Certificate value)](#setX509Certificate-java.security.cert.X509Certificate-) | 获取或设置 X509 证书。 |
|
|  | [getPrivateKey()](#getPrivateKey--) | 获取或设置证书的 PrivateKey。 |
|
|  | [setPrivateKey(PrivateKey value)](#setPrivateKey-java.security.PrivateKey-) | 获取或设置证书的 PrivateKey。 |
|
|  | [getCertificateName()](#getCertificateName--) | 获取或设置 X509 证书名称。 |
|
|  | [setCertificateName(String value)](#setCertificateName-java.lang.String-) | 获取或设置 X509 证书名称。 |
|
|  | [getComments()](#getComments--) | 获取或设置签名目的注释。 |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | 获取或设置签名目的注释。 |
|
|  | [isValid()](#isValid--) | 如果此数字签名有效且文档未被篡改，则保持为 true。 |
|
|  | [setValid(boolean value)](#setValid-boolean-) | 如果此数字签名有效且文档未被篡改，则保持为 true。 |
|
|  | [getSignTime()](#getSignTime--) | 获取或设置文档签署的时间。 |
|
|  | [setSignTime(Date value)](#setSignTime-java.util.Date-) | 获取或设置文档签署的时间。 |
|
|  | [getXAdESType()](#getXAdESType--) | XAdES 类型 |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | XAdES 类型 |
XAdESType
.
|
|  | [getThumbprint()](#getThumbprint--) | 获取证书的指纹。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较签名属性 |
|
|  | [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法 |
|
|  | [deepClone()](#deepClone--) | 克隆 Barcode Signature 实例。 |
|
|  | [loadDigitalSignatures()](#loadDigitalSignatures--) | 从所有系统 X509 证书存储加载数字签名。 |
|
|  | [loadDigitalSignatures(StoreName storeName)](#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-) | 从传入的 X509 证书存储加载数字签名。 |
|
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


使用默认参数初始化 DigitalSignature。


### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


使用已知的 SignatureId 初始化 DigitalSignature。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signatureId | java.lang.String |  |

### DigitalSignature(KeyStore certificate) {#DigitalSignature-java.security.KeyStore-}
```
public DigitalSignature(KeyStore certificate)
```


使用指定的证书创建 DigitalSignature。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 证书 | java.security.KeyStore | X509 证书。 |
|

### DigitalSignature(X509Certificate cert, PrivateKey key) {#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
```
public DigitalSignature(X509Certificate cert, PrivateKey key)
```


基于 X509Certificate 证书和 PrivateKey 创建 DigitalSignature。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | cert | java.security.cert.X509Certificate | X509Certificate 证书。 |
|
|  | key | java.security.PrivateKey | 证书的 PrivateKey。 |
|

### getCertificate() {#getCertificate--}
```
public final KeyStore getCertificate()
```


获取或设置 KeyStore 证书。


**Returns:**
java.security.KeyStore
### setCertificate(KeyStore value) {#setCertificate-java.security.KeyStore-}
```
public final void setCertificate(KeyStore value)
```


获取或设置 KeyStore 证书。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.security.KeyStore |  |

### getX509Certificate() {#getX509Certificate--}
```
public final X509Certificate getX509Certificate()
```


获取或设置 X509 证书。


**Returns:**
java.security.cert.X509Certificate
### setX509Certificate(X509Certificate value) {#setX509Certificate-java.security.cert.X509Certificate-}
```
public final void setX509Certificate(X509Certificate value)
```


获取或设置 X509 证书。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.security.cert.X509Certificate |  |

### getPrivateKey() {#getPrivateKey--}
```
public final PrivateKey getPrivateKey()
```


获取或设置证书的 PrivateKey。


**Returns:**
java.security.PrivateKey
### setPrivateKey(PrivateKey value) {#setPrivateKey-java.security.PrivateKey-}
```
public final void setPrivateKey(PrivateKey value)
```


获取或设置证书的 PrivateKey。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.security.PrivateKey |  |

### getCertificateName() {#getCertificateName--}
```
public final String getCertificateName()
```


获取或设置 X509 证书名称。


**Returns:**
java.lang.String
### setCertificateName(String value) {#setCertificateName-java.lang.String-}
```
public final void setCertificateName(String value)
```


获取或设置 X509 证书名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


获取或设置签名目的注释。


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


获取或设置签名目的注释。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


如果此数字签名有效且文档未被篡改，则保持为 true。


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


如果此数字签名有效且文档未被篡改，则保持为 true。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


获取或设置文档签署的时间。


**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


获取或设置文档签署的时间。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES 类型
XAdESType
默认值为 None（XAdES 已关闭）。
目前仅在电子表格文档中支持 XAdES 签名类型。


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES 类型
XAdESType
默认值为 None（XAdES 已关闭）。
目前仅在电子表格文档中支持 XAdES 签名类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


获取证书的指纹。


**Returns:**
java.lang.String
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

### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


从所有系统 X509 证书存储加载数字签名。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - 返回 [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) 数字签名的列表。

### loadDigitalSignatures(StoreName storeName) {#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-}
```
public static List<DigitalSignature> loadDigitalSignatures(StoreName storeName)
```


从传入的 X509 证书存储加载数字签名。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| storeName | [StoreName](../../com.groupdocs.signature.domain.signatures/storename) |  |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - 返回 [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) 数字签名的列表。

