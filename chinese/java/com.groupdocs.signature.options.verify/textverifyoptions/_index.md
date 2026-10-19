---
title: "TextVerifyOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "保留验证文档文本签名的选项。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

保留验证文档文本签名的选项。

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/)
* Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-text-signatures/)

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [TextVerifyOptions()](#TextVerifyOptions--) | 使用默认值初始化 TextVerifyOptions 的新实例。 |
|
|  | [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | 使用验证文本初始化 TextVerifyOptions 的新实例。 |
|
|  | [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | 使用要验证的 Text 属性和签名实现初始化 TextVerifyOptions 的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getText()](#getText--) | 指定要验证的签名文本（如果需要验证）。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 指定要验证的签名文本（如果需要验证）。 |
|
|  | [getMatchType()](#getMatchType--) | 获取或设置文本匹配类型验证。 |
|
|  | [setMatchType(int value)](#setMatchType-int-) | 获取或设置文本匹配类型验证。 |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | 要验证的签名类型。 |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | 要验证的签名类型。 |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | 获取或设置要验证的表单字段标题。 |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | 获取或设置要验证的表单字段标题。 |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | 获取或设置要验证的表单字段类型。 |
|
|  | [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | 获取或设置要验证的表单字段类型。 |
|
|  | [getSignatureID()](#getSignatureID--) | 如果应进行验证，请指定大于零的文本签名 ID。 |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | 如果应进行验证，请指定大于零的文本签名 ID。 |
|
|  | [toString()](#toString--) | 重写转换为字符串。 |
|
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


使用默认值初始化 TextVerifyOptions 的新实例。


### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


使用验证文本初始化 TextVerifyOptions 的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文本 | java.lang.String | 待验证的文本 |
|

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


使用要验证的 Text 属性和签名实现初始化 TextVerifyOptions 的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文本 | java.lang.String | 待验证的文本。 |
|
|  | 实现 | int | 签名实现类型。 |
|

### getText() {#getText--}
```
public final String getText()
```


指定要验证的签名文本（如果需要验证）。


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


指定要验证的签名文本（如果需要验证）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


获取或设置文本匹配类型验证。


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


获取或设置文本匹配类型验证。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


要验证的签名类型。


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


要验证的签名类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


获取或设置要验证的表单字段标题。
如果设置此属性，文本仅会在文本表单字段中找到。


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


获取或设置要验证的表单字段标题。
如果设置此属性，文本仅会在文本表单字段中找到。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


获取或设置要验证的表单字段类型。
如果设置此属性，文本仅会在文本表单字段中找到。


**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


获取或设置要验证的表单字段类型。
如果设置此属性，文本仅会在文本表单字段中找到。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


如果应进行验证，请指定大于零的文本签名 ID。此属性仅在 Pdf 文档中受支持


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


如果应进行验证，请指定大于零的文本签名 ID。此属性仅在 Pdf 文档中受支持


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### toString() {#toString--}
```
public String toString()
```


重写转换为字符串。


**Returns:**
java.lang.String - 
