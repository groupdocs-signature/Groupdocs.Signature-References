---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示数字签名选项。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

表示数字签名选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DigitalSignOptions()](#DigitalSignOptions--) | 使用默认值初始化 DigitalSignOptions 类的新实例。 |
|
|  | [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | 使用证书文件初始化 DigitalSignOptions 类的新实例。 |
|
|  | [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | 使用证书流初始化 DigitalSignOptions 类的新实例。 |
|
|  | [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | 使用证书文件和图像文件初始化 DigitalSignOptions 类的新实例。 |
|
|  | [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | 使用证书文件和图像流初始化 DigitalSignOptions 类的新实例。 |
|
|  | [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | 使用证书流和图像文件初始化 DigitalSignOptions 类的新实例。 |
|
|  | [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | 使用证书流和图像流初始化 DigitalSignOptions 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getReason()](#getReason--) | 获取或设置签名的原因。 |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | 获取或设置签名的原因。 |
|
|  | [getContact()](#getContact--) | 获取或设置签名联系人。 |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | 获取或设置签名联系人。 |
|
|  | [getLocation()](#getLocation--) | 获取或设置签名位置。 |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | 获取或设置签名位置。 |
|
|  | [getPassword()](#getPassword--) | 获取或设置数字证书的密码。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 获取或设置数字证书的密码。 |
|
|  | [getSignature()](#getSignature--) | 获取或设置文档数字签名的属性。 |
|
|  | [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | 获取或设置文档数字签名的属性。 |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | 获取或设置数字证书文件路径。 |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | 获取或设置数字证书文件的 GUID。 |
|
|  | [getCertificateStream()](#getCertificateStream--) | 获取或设置数字证书流。 |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | 获取或设置数字证书流。 |
|
|  | [getVisible()](#getVisible--) | 获取或设置签名的可见性。 |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | 获取或设置签名的可见性。 |
|
|  | [getUseLtv()](#getUseLtv--) | 获取/设置 LTV（长期验证）验证标志。 |
|
|  | [setUseLtv(boolean value)](#setUseLtv-boolean-) | 获取/设置 LTV（长期验证）验证标志。 |
|
|  | [getCustomSignHash()](#getCustomSignHash--) | 获取或设置自定义哈希签名实现，允许调用方插入自己的 |
数字签名逻辑（HSM、远程签名器、软件密钥库等）。
|
|  | [setCustomSignHash(ICustomSignHash value)](#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-) | 设置自定义哈希签名实现，允许调用方插入自己的 |
数字签名逻辑。
|
|  | [getXAdESType()](#getXAdESType--) | XAdES 类型 |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | XAdES 类型 |
XAdESType
.
|
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
|  | [toString()](#toString--) | 覆盖字符串转换。 |
|
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


使用默认值初始化 DigitalSignOptions 类的新实例。


### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


使用证书文件初始化 DigitalSignOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | 数字证书文件路径 |
|

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


使用证书流初始化 DigitalSignOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | 数字证书流 |
|

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


使用证书文件和图像文件初始化 DigitalSignOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | 数字证书文件路径 |
|
|  | imageFilePath | java.lang.String | 签名外观图像文件路径 |
|

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


使用证书文件和图像流初始化 DigitalSignOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | 数字证书文件路径 |
|
|  | appearenceImageStream | java.io.InputStream | 签名外观图像流 |
|

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


使用证书流和图像文件初始化 DigitalSignOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | 数字证书流 |
|
|  | imageFilePath | java.lang.String | 签名外观图像文件路径 |
|

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


使用证书流和图像流初始化 DigitalSignOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | 数字证书流 |
|
|  | appearenceImageStream | java.io.InputStream | 签名外观图像流 |
|

### getReason() {#getReason--}
```
public final String getReason()
```


获取或设置签名的原因。


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


获取或设置签名的原因。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


获取或设置签名联系人。


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


获取或设置签名联系人。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


获取或设置签名位置。


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


获取或设置签名位置。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


获取或设置数字证书的密码。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


获取或设置数字证书的密码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


获取或设置文档数字签名的属性。


**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


获取或设置文档数字签名的属性。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


获取或设置数字证书文件路径。
仅当未指定 CertificateStream 时才使用此属性。


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


获取或设置数字证书文件的 GUID。
仅当未指定 CertificateStream 时才使用此属性。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


获取或设置数字证书流。
如果指定了此属性，则始终使用它而不是 CertificateGuid。


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


获取或设置数字证书流。
如果指定了此属性，则始终使用它而不是 CertificateGuid。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


获取或设置签名的可见性。


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


获取或设置签名的可见性。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


获取/设置 LTV（长期验证）验证标志。


**Returns:**
boolean
### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


获取/设置 LTV（长期验证）验证标志。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getCustomSignHash() {#getCustomSignHash--}
```
public final ICustomSignHash getCustomSignHash()
```


获取或设置自定义哈希签名实现，允许调用方插入自己的
数字签名逻辑（HSM、远程签名器、软件密钥库等）。


**Returns:**
[ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash)
### setCustomSignHash(ICustomSignHash value) {#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-}
```
public final void setCustomSignHash(ICustomSignHash value)
```


设置自定义哈希签名实现，允许调用方插入自己的
数字签名逻辑。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash) |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES 类型
XAdESType
默认值为 None（XAdES 已关闭）。
目前，仅在 .NET Framework（不在 .NET Standard）下支持 XAdES 签名类型的电子表格文档。


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES 类型
XAdESType
默认值为 None（XAdES 已关闭）。
目前，仅在 .NET Framework（不在 .NET Standard）下支持 XAdES 签名类型的电子表格文档。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSignatureLineId() {#getSignatureLineId--}
```
public final UUID getSignatureLineId()
```




**Returns:**
java.util.UUID
### setSignatureLineId(UUID value) {#setSignatureLineId-java.util.UUID-}
```
public final void setSignatureLineId(UUID value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


覆盖字符串转换。


**Returns:**
java.lang.String - 
