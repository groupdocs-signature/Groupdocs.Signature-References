---
title: "CertificateVerifyOptions"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "保留验证证书文档的选项。"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

保留验证证书文档的选项。

--------------------

 **Learn more** 

 *  
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CertificateVerifyOptions()](#CertificateVerifyOptions--) | 使用默认值初始化 TextVerifyOptions 的新实例。 |
| [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | 使用要验证的主题初始化 CertificateVerifyOptions 的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIssuer()](#getIssuer--) | 如果应验证，请指定证书颁发者。 |
| [setIssuer(String value)](#setIssuer-java.lang.String-) | 如果应验证，请指定证书颁发者。 |
| [getSerialNumber()](#getSerialNumber--) | 如果应验证，请指定证书序列号。 |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | 如果应验证，请指定证书序列号。 |
| [getSubject()](#getSubject--) | 如果应验证，请指定证书主题。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | 如果应验证，请指定证书主题。 |
| [getThumbprint()](#getThumbprint--) | 如果应验证，请指定证书指纹。 |
| [setThumbprint(String value)](#setThumbprint-java.lang.String-) | 如果应验证，请指定证书指纹。 |
| [getMatchType()](#getMatchType--) | 获取或设置 Text Match Type 验证。 |
| [setMatchType(int value)](#setMatchType-int-) | 获取或设置 Text Match Type 验证。 |
| [getExpired()](#getExpired--) | 指示证书是否因验证结果而已过期。 |
| [setExpired(boolean value)](#setExpired-boolean-) | 指示证书是否因验证结果而已过期。 |
| [getPerformChainValidation()](#getPerformChainValidation--) | 获取或设置验证过程是否应使用基本验证策略提供 X.509 链验证。 |
| [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | 获取或设置验证过程是否应使用基本验证策略提供 X.509 链验证。 |
| [toString()](#toString--) | 重写转换为字符串的方法。 |
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


使用默认值初始化 TextVerifyOptions 的新实例。

### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


使用要验证的主题初始化 CertificateVerifyOptions 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subject | java.lang.String | 要验证的主题 |

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


如果应验证，请指定证书颁发者。

**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


如果应验证，请指定证书颁发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


如果应验证，请指定证书序列号。

**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


如果应验证，请指定证书序列号。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


如果应验证，请指定证书主题。

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


如果应验证，请指定证书主题。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


如果应验证，请指定证书指纹。

**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


如果应验证，请指定证书指纹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


获取或设置 Text Match Type 验证。

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


获取或设置 Text Match Type 验证。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


指示证书是否因验证结果而已过期。属性为只读。

**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


指示证书是否因验证结果而已过期。属性为只读。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


获取或设置验证过程是否应使用基本验证策略提供 X.509 链验证。默认情况下此值为 true。

**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


获取或设置验证过程是否应使用基本验证策略提供 X.509 链验证。默认情况下此值为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### toString() {#toString--}
```
public String toString()
```


重写转换为字符串的方法。

**Returns:**
java.lang.String -
