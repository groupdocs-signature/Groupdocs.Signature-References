---
title: "SearchOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示从文档中提取签名的选项。"
type: docs
weight: 17
url: /zh/java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)
```
public abstract class SearchOptions extends OptionsExtensions
```

表示从文档中提取签名的选项。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | 获取或设置用于搜索的文档页码。 |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | 获取或设置用于搜索的文档页码。 |
|
|  | [getPagesSetup()](#getPagesSetup--) | 用于指定签名搜索页面的选项。 |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | 用于指定签名搜索页面的选项。 |
|
|  | [getAllPages()](#getAllPages--) | 在每个文档页面上进行搜索的标志。 |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | 在每个文档页面上进行搜索的标志。 |
|
|  | [getSkipExternal()](#getSkipExternal--) | 仅返回标记为 IsSignature 的签名的标志。 |
|
|  | [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | 仅返回标记为 IsSignature 的签名的标志。 |
|
|  | [getSearchPages(int totalPages)](#getSearchPages-int-) | 用于获取签名提取页面列表的虚方法。 |
|
|  | [toString()](#toString--) | 覆盖字符串转换。 |
|
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


获取或设置用于搜索的文档页码。
该值是可选的。


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


获取或设置用于搜索的文档页码。
该值是可选的。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


用于指定签名搜索页面的选项。


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


用于指定签名搜索页面的选项。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


在每个文档页面上进行搜索的标志。默认情况下，此值设置为 true。


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


在每个文档页面上进行搜索的标志。默认情况下，此值设置为 true。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


仅返回标记为 IsSignature 的签名的标志。默认值为 false，表示返回所有符合指定条件的签名。


**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


仅返回标记为 IsSignature 的签名的标志。默认值为 false，表示返回所有符合指定条件的签名。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


用于获取签名提取页面列表的虚方法。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | totalPages | int | 页面的总计数 |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - 页面编号列表

### toString() {#toString--}
```
public String toString()
```


覆盖字符串转换。


**Returns:**
java.lang.String - 
