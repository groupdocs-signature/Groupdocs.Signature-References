---
title: "TextFormFieldSignature"
second_title: "GroupDocs.Signature for Java API 参考"
description: "包含用于 PDF 文档的文本输入表单字段签名属性"
type: docs
weight: 15
url: /zh/java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

包含用于 PDF 文档的文本输入表单字段签名属性

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | 创建具有预定义名称的 PdfTextFormFieldSignature。 |
|
|  | [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | 创建具有预定义名称的 PdfTextFormFieldSignature。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getText()](#getText--) | 获取或设置表单字段文本输入的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 获取或设置表单字段文本输入的文本。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较签名属性 |
|
|  | [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法 |
|
|  | [deepClone()](#deepClone--) | 克隆 FormField Signature 实例。 |
|
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


创建具有预定义名称的 PdfTextFormFieldSignature。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 表单字段对象的名称。 |
|

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


创建具有预定义名称的 PdfTextFormFieldSignature。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 表单字段对象的名称。 |
|
|  | 文本 | java.lang.String | 表单字段对象的文本。 |
|

### getText() {#getText--}
```
public final String getText()
```


获取或设置表单字段文本输入的文本。


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


获取或设置表单字段文本输入的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

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

