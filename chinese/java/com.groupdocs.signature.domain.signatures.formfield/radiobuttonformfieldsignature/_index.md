---
title: "RadioButtonFormFieldSignature"
second_title: "GroupDocs.Signature for Java API 参考"
description: "包含单选按钮输入表单字段签名属性。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.signature.domain.signatures.formfield/radiobuttonformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
```
public final class RadioButtonFormFieldSignature extends FormFieldSignature
```

包含单选按钮输入表单字段签名属性。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [RadioButtonFormFieldSignature(String name)](#RadioButtonFormFieldSignature-java.lang.String-) | 创建具有预定义名称的 RadioButtonFieldSignature。 |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | 创建具有预定义名称和项目列表的 RadioButtonFieldSignature。 |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items, Object selected)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | 创建具有预定义名称、项目列表和选定值的 RadioButtonFieldSignature。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSelected()](#getSelected--) | 包含选定的值。 |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | 包含选定的值。 |
|
|  | [getItems()](#getItems--) | 获取或设置单选按钮选项列表。 |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | 获取或设置单选按钮选项列表。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较签名属性 |
|
|  | [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法 |
|
|  | [deepClone()](#deepClone--) | 克隆 FormField Signature 实例。 |
|
### RadioButtonFormFieldSignature(String name) {#RadioButtonFormFieldSignature-java.lang.String-}
```
public RadioButtonFormFieldSignature(String name)
```


创建具有预定义名称的 RadioButtonFieldSignature。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 表单字段对象的名称。 |
|

### RadioButtonFormFieldSignature(String name, List<String> items) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public RadioButtonFormFieldSignature(String name, List<String> items)
```


创建具有预定义名称和项目列表的 RadioButtonFieldSignature。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 表单字段对象的名称。 |
|
|  | items | java.util.List<java.lang.String> | 单选按钮列表的值。 |
|

### RadioButtonFormFieldSignature(String name, List<String> items, Object selected) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public RadioButtonFormFieldSignature(String name, List<String> items, Object selected)
```


创建具有预定义名称、项目列表和选定值的 RadioButtonFieldSignature。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 表单字段对象的名称。 |
|
|  | items | java.util.List<java.lang.String> | 单选按钮列表的值。 |
|
|  | selected | java.lang.Object | 选定的值。 |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


包含选定的值。


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


包含选定的值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


获取或设置单选按钮选项列表。


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


获取或设置单选按钮选项列表。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.List<java.lang.String> |  |

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

