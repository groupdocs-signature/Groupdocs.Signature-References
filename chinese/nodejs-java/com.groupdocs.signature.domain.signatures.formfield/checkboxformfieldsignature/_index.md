---
title: "CheckboxFormFieldSignature"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "包含复选框输入表单字段签名属性。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

包含复选框输入表单字段签名属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | 创建具有预定义名称的 PdfCheckboxFormFieldSignature。 |
| [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | 创建具有预定义名称和数值的 PdfCheckboxFormFieldSignature |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getChecked()](#getChecked--) | 获取或设置表单字段复选框输入的已选值。 |
| [setChecked(boolean value)](#setChecked-boolean-) | 获取或设置表单字段复选框输入的已选值。 |
| [equals(Object signature)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较签名属性 |
| [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法。 |
| [deepClone()](#deepClone--) | 克隆 FormField Signature 实例。 |
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


创建具有预定义名称的 PdfCheckboxFormFieldSignature。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 表单字段对象的名称。 |

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


创建具有预定义名称和数值的 PdfCheckboxFormFieldSignature

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 表单字段对象的名称。 |
| isChecked | boolean | 如果复选框被选中时的值 |

### getChecked() {#getChecked--}
```
public final boolean getChecked()
```


获取或设置表单字段复选框输入的已选值。

**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public final void setChecked(boolean value)
```


获取或设置表单字段复选框输入的已选值。

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
