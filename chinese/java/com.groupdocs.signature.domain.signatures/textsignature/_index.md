---
title: "TextSignature"
second_title: "GroupDocs.Signature for Java API 参考"
description: "包含文本签名属性。"
type: docs
weight: 18
url: /zh/java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

包含文本签名属性。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | 使用在搜索过程后获得的签名标识符初始化 TextSignature 对象。 |
|
| [TextSignature()](#TextSignature--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getText()](#getText--) | 指定签名中的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 指定签名中的文本。 |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | 指定文本签名的实现。 |
|
|  | [getNative()](#getNative--) | 指定本机属性。 |
|
|  | [setNative(boolean value)](#setNative-boolean-) | 指定本机属性。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较签名属性 |
|
|  | [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法 |
|
|  | [deepClone()](#deepClone--) | 克隆 Text Signature 实例。 |
|
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


使用在搜索过程后获得的签名标识符初始化 TextSignature 对象。
此唯一标识符用于从文档签名信息层查找此签名的附加属性。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | signatureId | java.lang.String | 通过签名或搜索方法获取的唯一签名标识符。 |
|

### TextSignature() {#TextSignature--}
```
public TextSignature()
```


### getText() {#getText--}
```
public final String getText()
```


指定签名中的文本。


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


指定签名中的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


指定文本签名的实现。


**Returns:**
int
### getNative() {#getNative--}
```
public final boolean getNative()
```


指定本机属性。如果签名是文档特定的，则为 true。


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


指定本机属性。如果签名是文档特定的，则为 true。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

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


克隆 Text Signature 实例。


**Returns:**
java.lang.Object - 返回克隆的文本签名实例。

