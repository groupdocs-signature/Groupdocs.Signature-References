---
title: "CertificateSearchOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示证书元数据签名的搜索选项。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.signature.options.search/certificatesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class CertificateSearchOptions extends SearchOptions
```

表示证书元数据签名的搜索选项。

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [CertificateSearchOptions()](#CertificateSearchOptions--) | 使用默认值初始化 TextSearchOptions 类的新实例。 |
|
|  | [CertificateSearchOptions(String text)](#CertificateSearchOptions-java.lang.String-) | 使用文本值初始化 TextSearchOptions 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getText()](#getText--) | 指定在搜索时要匹配的证书属性文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 指定在搜索时要匹配的证书属性文本。 |
|
|  | [getMatchType()](#getMatchType--) | 获取或设置文本匹配类型搜索。 |
|
|  | [setMatchType(int value)](#setMatchType-int-) | 获取或设置文本匹配类型搜索。 |
|
### CertificateSearchOptions() {#CertificateSearchOptions--}
```
public CertificateSearchOptions()
```


使用默认值初始化 TextSearchOptions 类的新实例。


### CertificateSearchOptions(String text) {#CertificateSearchOptions-java.lang.String-}
```
public CertificateSearchOptions(String text)
```


使用文本值初始化 TextSearchOptions 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文本 | java.lang.String | 设置文本签名的文本。 |
|

### getText() {#getText--}
```
public final String getText()
```


指定在搜索时要匹配的证书属性文本。


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


指定在搜索时要匹配的证书属性文本。


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

