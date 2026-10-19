---
title: "DigitalSignatureAppearance"
second_title: "GroupDocs.Signature for Java API 参考"
description: "描述数字签名的签名线外观。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

描述数字签名的签名线外观。
一个签名行只能用于一个数字签名。
签名行始终位于第一页。
此功能可能对 .docx、.doc、.odt 和 .xlsx 文件格式有用。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | 创建签名行外观对象。 |
|
|  | [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | 使用指定值（签名者、标题、电子邮件）创建签名行外观。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSigner()](#getSigner--) | 获取或设置签名行的签名者名称。 |
|
|  | [setSigner(String value)](#setSigner-java.lang.String-) | 获取或设置签名行的签名者名称。 |
|
|  | [getTitle()](#getTitle--) | 获取或设置签名行的标题。 |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | 获取或设置签名行的标题。 |
|
|  | [getEmail()](#getEmail--) | 获取或设置将在签名行中显示的电子邮件。 |
|
|  | [setEmail(String value)](#setEmail-java.lang.String-) | 获取或设置将在签名行中显示的电子邮件。 |
|
|  | [toString()](#toString--) | 覆盖字符串转换。 |
|
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


创建签名行外观对象。


### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


使用指定值（签名者、标题、电子邮件）创建签名行外观。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 签名者 | java.lang.String | 签名者名称。 |
|
|  | 标题 | java.lang.String | 签名标题。 |
|
|  | 电子邮件 | java.lang.String | 作者的电子邮件。 |
|

### getSigner() {#getSigner--}
```
public final String getSigner()
```


获取或设置签名行的签名者名称。


**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


获取或设置签名行的签名者名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


获取或设置签名行的标题。


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


获取或设置签名行的标题。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


获取或设置将在签名行中显示的电子邮件。


**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


获取或设置将在签名行中显示的电子邮件。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


覆盖字符串转换。


**Returns:**
java.lang.String - 
