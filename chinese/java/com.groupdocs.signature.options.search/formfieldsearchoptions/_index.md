---
title: "FormFieldSearchOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示表单字段签名的抽象搜索选项。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.signature.options.search/formfieldsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class FormFieldSearchOptions extends SearchOptions
```

表示表单字段签名的抽象搜索选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [FormFieldSearchOptions()](#FormFieldSearchOptions--) | 使用默认值初始化 SearchFormFieldOptions 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getType()](#getType--) | 指定表单字段签名的类型（如果需要搜索）。 |
|
|  | [setType(Integer value)](#setType-java.lang.Integer-) | 指定表单字段签名的类型（如果需要搜索）。 |
|
|  | [getName()](#getName--) | 指定表单字段签名名称的正则表达式模式（如果需要搜索）。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | 指定表单字段签名名称的正则表达式模式（如果需要搜索）。 |
|
|  | [getValue()](#getValue--) | 指定表单字段签名的值（如果需要搜索）。 |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | 指定表单字段签名的值（如果需要搜索）。 |
|
### FormFieldSearchOptions() {#FormFieldSearchOptions--}
```
public FormFieldSearchOptions()
```


使用默认值初始化 SearchFormFieldOptions 类的新实例。


### getType() {#getType--}
```
public final Integer getType()
```


指定表单字段签名的类型（如果需要搜索）。默认值为 null。


**Returns:**
java.lang.Integer
### setType(Integer value) {#setType-java.lang.Integer-}
```
public final void setType(Integer value)
```


指定表单字段签名的类型（如果需要搜索）。默认值为 null。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Integer |  |

### getName() {#getName--}
```
public final String getName()
```


指定表单字段签名名称的正则表达式模式（如果需要搜索）。
您可以简单地使用 \"text\"，或使用正则表达式如 \"abc\\\\d+\"。默认值为空字符串。


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


指定表单字段签名名称的正则表达式模式（如果需要搜索）。
您可以简单地使用 \"text\"，或使用正则表达式如 \"abc\\\\d+\"。默认值为空字符串。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


指定表单字段签名的值（如果需要搜索）。默认值为 null。


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


指定表单字段签名的值（如果需要搜索）。默认值为 null。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

