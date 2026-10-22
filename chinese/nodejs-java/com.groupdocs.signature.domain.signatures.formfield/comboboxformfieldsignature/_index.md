---
title: "ComboboxFormFieldSignature"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "包含下拉框输入表单字段签名属性。"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

包含下拉框输入表单字段签名属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | 使用预定义名称创建 ComboboxFormFieldSignature。 |
| [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | 使用预定义名称和选项列表创建 ComboboxFormFieldSignature。 |
| [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | 使用预定义名称、选项列表和选定值创建 ComboboxFormFieldSignature。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSelected()](#getSelected--) | 获取或设置选定值。 |
| [setSelected(String value)](#setSelected-java.lang.String-) | 获取或设置选定值。 |
| [getItems()](#getItems--) | 获取或设置组合框选项列表。 |
| [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | 获取或设置组合框选项列表。 |
| [equals(Object signature)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较签名属性 |
| [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法。 |
| [deepClone()](#deepClone--) | 克隆 FormField Signature 实例。 |
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


使用预定义名称创建 ComboboxFormFieldSignature。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 表单字段对象的名称。 |

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


使用预定义名称和选项列表创建 ComboboxFormFieldSignature。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 表单字段对象的名称。 |
| items | java.util.List<java.lang.String> | 组合框列表的值。 |

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


使用预定义名称、选项列表和选定值创建 ComboboxFormFieldSignature。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 表单字段对象的名称。 |
| items | java.util.List<java.lang.String> | 组合框列表的值。 |
| selected | java.lang.Object | 选定值。 |

### getSelected() {#getSelected--}
```
public final String getSelected()
```


获取或设置选定值。

**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


获取或设置选定值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


获取或设置组合框选项列表。

**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


获取或设置组合框选项列表。

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
| 签名 | java.lang.Object | 用于比较的 Signature 对象。 |

**Returns:**
boolean - 如果传入的签名对象具有相同类型且所有属性都等于此实例的属性，则返回 true。
### hashCode() {#hashCode--}
```
public int hashCode()
```


覆盖 GetHashCode 方法。

**Returns:**
int - 签名哈希码
### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆 FormField Signature 实例。

**Returns:**
java.lang.Object - 返回克隆的 FormField Signature 实例。
