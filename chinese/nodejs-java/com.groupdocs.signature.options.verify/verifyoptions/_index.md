---
title: "VerifyOptions"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "保留验证文档的选项。"
type: docs
weight: 15
url: /zh/nodejs-java/com.groupdocs.signature.options.verify/verifyoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class VerifyOptions
```

保留验证文档的选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [isValid()](#isValid--) | 有效属性标志。 |
| [setValid(boolean value)](#setValid-boolean-) | 有效属性标志。 |
| [getPageNumber()](#getPageNumber--) | 待验证的文档页码。 |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | 待验证的文档页码。 |
| [getPagesSetup()](#getPagesSetup--) | 用于指定要验证的页面的页面选项。 |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | 用于指定要验证的页面的页面选项。 |
| [getAllPages()](#getAllPages--) | 标志以验证每个文档页。 |
| [setAllPages(boolean value)](#setAllPages-boolean-) | 标志以验证每个文档页。 |
| [getExtensions()](#getExtensions--) | 用于替代签名选项验证的附加扩展。 |
| [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | 用于替代签名选项验证的附加扩展。 |
| [toString()](#toString--) | 覆盖字符串转换。 |
### isValid() {#isValid--}
```
public final boolean isValid()
```


有效属性标志。

**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


有效属性标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


待验证的文档页码。如果属性未设置 - 将验证文档的所有页面的首次出现。最小值为 1。

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


待验证的文档页码。如果属性未设置 - 将验证文档的所有页面的首次出现。最小值为 1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


用于指定要验证的页面的页面选项。

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


用于指定要验证的页面的页面选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


标志以验证每个文档页。默认值为 true。

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


标志以验证每个文档页。默认值为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


用于替代签名选项验证的附加扩展。

**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


用于替代签名选项验证的附加扩展。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


覆盖字符串转换。

**Returns:**
java.lang.String -
