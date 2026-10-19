---
title: "FormFieldSignature"
second_title: "GroupDocs.Signature for Java API 参考"
description: "包含表单字段签名属性。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class FormFieldSignature extends BaseSignature
```

包含表单字段签名属性。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getName()](#getName--) | 指定唯一的表单字段名称。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | 指定唯一的表单字段名称。 |
|
|  | [getType()](#getType--) | 指定表单字段类型。 |
|
|  | [getValue()](#getValue--) | 指定表单字段数据对象。 |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | 指定表单字段数据对象。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较签名属性 |
|
|  | [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法 |
|
|  | [deepClone()](#deepClone--) | 克隆 FormField Signature 实例。 |
|
### getName() {#getName--}
```
public final String getName()
```


指定唯一的表单字段名称。


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


指定唯一的表单字段名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


指定表单字段类型。


**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


指定表单字段数据对象。


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


指定表单字段数据对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

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


克隆 FormField Signature 实例。


**Returns:**
java.lang.Object - 返回克隆的 FormField Signature 实例。

