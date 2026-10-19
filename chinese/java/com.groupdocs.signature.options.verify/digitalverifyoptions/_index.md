---
title: "DigitalVerifyOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "保留验证文档数字签名的选项。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

保留验证文档数字签名的选项。

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](../https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/)
* Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Digital signatures in a document and additional settings](../)

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DigitalVerifyOptions()](#DigitalVerifyOptions--) | 使用默认值创建 Digital Verification Option。 |
|
|  | [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | 使用给定的数字证书 guid 创建 Digital Verification Option。 |
|
|  | [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | 使用给定的证书流创建 Digital Verification Option。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | 从证书 Guid 或流获取 X509Certificate2 证书。 |
|
|  | [getPassword()](#getPassword--) | 如果需要，数字证书的密码。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 如果需要，数字证书的密码。 |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | 数字证书的文件 Guid。 |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | 数字证书的文件 Guid。 |
|
|  | [getCertificateStream()](#getCertificateStream--) | 数字证书的流。 |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | 数字证书的流。 |
|
|  | [getComments()](#getComments--) | 要验证的数字签名的注释。 |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | 要验证的数字签名的注释。 |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | 要验证的数字签名的日期和时间范围。 |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | 要验证的数字签名的日期和时间范围。 |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | 要验证的数字签名的日期和时间范围。 |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | 要验证的数字签名的日期和时间范围。 |
|
|  | [getReason()](#getReason--) | 要验证的数字签名的原因。 |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | 要验证的数字签名的原因。 |
|
|  | [getContact()](#getContact--) | 要验证的签名联系人。 |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | 要验证的签名联系人。 |
|
|  | [getLocation()](#getLocation--) | 要验证的签名位置。 |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | 要验证的签名位置。 |
|
|  | [getSubjectName()](#getSubjectName--) | 要验证的证书的主题可分辨名称。 |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | 要验证的证书的主题可分辨名称。 |
|
|  | [getIssuerName()](#getIssuerName--) | 要验证的证书的发行者名称。 |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | 要验证的证书的发行者名称。 |
|
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


使用默认值创建 Digital Verification Option。


### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


使用给定的数字证书 guid 创建 Digital Verification Option。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | certificateGuid | java.lang.String | 数字证书的文件路径。 |
|

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


使用给定的证书流创建 Digital Verification Option。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | 证书的流。 |
|

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


从证书 Guid 或流获取 X509Certificate2 证书。


**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


如果需要，数字证书的密码。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


如果需要，数字证书的密码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


数字证书的文件 Guid。


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


数字证书的文件 Guid。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


数字证书的流。


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


数字证书的流。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


要验证的数字签名的注释。


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


要验证的数字签名的注释。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


要验证的数字签名的日期和时间范围。可为空的值将被忽略。


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


要验证的数字签名的日期和时间范围。可为空的值将被忽略。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


要验证的数字签名的日期和时间范围。可为空的值将被忽略。


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


要验证的数字签名的日期和时间范围。可为空的值将被忽略。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


要验证的数字签名的原因。


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


要验证的数字签名的原因。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


要验证的签名联系人。


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


要验证的签名联系人。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


要验证的签名位置。


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


要验证的签名位置。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


要验证的证书的主题可分辨名称。值区分大小写。
如果设置了此属性，验证将检查签名主题名称是否包含或等于传入的值


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


要验证的证书的主题可分辨名称。值区分大小写。
如果设置了此属性，验证将检查签名主题名称是否包含或等于传入的值


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


要验证的证书的颁发者名称。值区分大小写。
如果设置了此属性，验证将检查签名的颁发者名称是否包含或等于传入的值


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


要验证的证书的颁发者名称。值区分大小写。
如果设置了此属性，验证将检查签名的颁发者名称是否包含或等于传入的值


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

