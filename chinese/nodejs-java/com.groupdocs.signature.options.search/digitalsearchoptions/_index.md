---
title: "DigitalSearchOptions"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示数字签名搜索的基础选项"
type: docs
weight: 12
url: /zh/nodejs-java/com.groupdocs.signature.options.search/digitalsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class DigitalSearchOptions extends SearchOptions
```

表示数字签名搜索的基础选项
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DigitalSearchOptions()](#DigitalSearchOptions--) | 使用默认值初始化 DigitalSearchOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getComments()](#getComments--) | 要搜索的数字签名的注释。 |
| [setComments(String value)](#setComments-java.lang.String-) | 要搜索的数字签名的注释。 |
| [getSignDateTimeFrom()](#getSignDateTimeFrom--) | 要搜索的数字签名的日期和时间范围。 |
| [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | 要搜索的数字签名的日期和时间范围。 |
| [getSignDateTimeTo()](#getSignDateTimeTo--) | 要搜索的数字签名的日期和时间范围。 |
| [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | 要搜索的数字签名的日期和时间范围。 |
| [getSubjectName()](#getSubjectName--) | 对于非空值，指定要搜索的证书的可辨别主题名称。 |
| [setSubjectName(String value)](#setSubjectName-java.lang.String-) | 对于非空值，指定要搜索的证书的可辨别主题名称。 |
| [getIssuerName()](#getIssuerName--) | 对于非空值，指定要搜索的证书颁发者的可辨别名称。 |
| [setIssuerName(String value)](#setIssuerName-java.lang.String-) | 对于非空值，指定要搜索的证书颁发者的可辨别名称。 |
### DigitalSearchOptions() {#DigitalSearchOptions--}
```
public DigitalSearchOptions()
```


使用默认值初始化 DigitalSearchOptions 类的新实例。

### getComments() {#getComments--}
```
public final String getComments()
```


要搜索的数字签名的注释。

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


要搜索的数字签名的注释。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public final Date getSignDateTimeFrom()
```


要搜索的数字签名的日期和时间范围。可为空的值将被忽略。

**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public final void setSignDateTimeFrom(Date value)
```


要搜索的数字签名的日期和时间范围。可为空的值将被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public final Date getSignDateTimeTo()
```


要搜索的数字签名的日期和时间范围。可为空的值将被忽略。

**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public final void setSignDateTimeTo(Date value)
```


要搜索的数字签名的日期和时间范围。可为空的值将被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Date |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


对于非空值，指定要搜索的证书的可辨别主题名称。

**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


对于非空值，指定要搜索的证书的可辨别主题名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


对于非空值，指定要搜索的证书颁发者的可辨别名称。

**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


对于非空值，指定要搜索的证书颁发者的可辨别名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

