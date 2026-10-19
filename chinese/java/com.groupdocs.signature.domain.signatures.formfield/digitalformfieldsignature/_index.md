---
title: "DigitalFormFieldSignature"
second_title: "GroupDocs.Signature for Java API 参考"
description: "包含用于 PDF 文档的数字签名输入表单字段属性。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.signature.domain.signatures.formfield/digitalformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
```
public final class DigitalFormFieldSignature extends FormFieldSignature
```

包含用于 PDF 文档的数字签名输入表单字段属性。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DigitalFormFieldSignature(String name)](#DigitalFormFieldSignature-java.lang.String-) | 创建具有预定义名称的 PdfDigitalFormFieldSignature。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSigned()](#getSigned--) | 只读属性，显示 Form-field Signature 是否使用数字证书签名。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较签名属性 |
|
|  | [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法 |
|
|  | [deepClone()](#deepClone--) | 克隆 FormField Signature 实例。 |
|
### DigitalFormFieldSignature(String name) {#DigitalFormFieldSignature-java.lang.String-}
```
public DigitalFormFieldSignature(String name)
```


创建具有预定义名称的 PdfDigitalFormFieldSignature。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 表单字段对象的名称。 |
|

### getSigned() {#getSigned--}
```
public final boolean getSigned()
```


只读属性，显示 Form-field Signature 是否使用数字证书签名。


**Returns:**
boolean
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

