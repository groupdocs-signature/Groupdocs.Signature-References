---
title: "TextSearchOptions"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示文本签名的搜索选项。"
type: docs
weight: 18
url: /zh/nodejs-java/com.groupdocs.signature.options.search/textsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class TextSearchOptions extends SearchOptions
```

表示文本签名的搜索选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextSearchOptions()](#TextSearchOptions--) | 使用默认值初始化 TextSearchOptions 类的新实例。 |
| [TextSearchOptions(String text)](#TextSearchOptions-java.lang.String-) | 使用文本值初始化 TextSearchOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getText()](#getText--) | 指定用于搜索匹配的签名文本。 |
| [setText(String value)](#setText-java.lang.String-) | 指定用于搜索匹配的签名文本。 |
| [getMatchType()](#getMatchType--) | 获取或设置文本匹配类型搜索。 |
| [setMatchType(int value)](#setMatchType-int-) | 获取或设置文本匹配类型搜索。 |
| [getSignatureImplementation()](#getSignatureImplementation--) | 指定用于搜索的文本签名实现。 |
| [setSignatureImplementation(Integer value)](#setSignatureImplementation-java.lang.Integer-) | 指定用于搜索的文本签名实现。 |
### TextSearchOptions() {#TextSearchOptions--}
```
public TextSearchOptions()
```


使用默认值初始化 TextSearchOptions 类的新实例。

### TextSearchOptions(String text) {#TextSearchOptions-java.lang.String-}
```
public TextSearchOptions(String text)
```


使用文本值初始化 TextSearchOptions 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 设置文本签名的文本。 |

### getText() {#getText--}
```
public final String getText()
```


指定用于搜索匹配的签名文本。

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


指定用于搜索匹配的签名文本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


获取或设置文本匹配类型搜索。

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


获取或设置文本匹配类型搜索。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final Integer getSignatureImplementation()
```


指定用于搜索的文本签名实现。

**Returns:**
java.lang.Integer
### setSignatureImplementation(Integer value) {#setSignatureImplementation-java.lang.Integer-}
```
public final void setSignatureImplementation(Integer value)
```


指定用于搜索的文本签名实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Integer |  |

