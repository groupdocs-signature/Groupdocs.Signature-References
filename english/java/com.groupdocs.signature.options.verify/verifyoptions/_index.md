---
title: VerifyOptions
second_title: GroupDocs.Signature for Java API Reference
description: Keeps options to verify document.
type: docs
weight: 14
url: /java/com.groupdocs.signature.options.verify/verifyoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class VerifyOptions
```

Keeps options to verify document.
## Methods

| Method | Description |
| --- | --- |
| [isValid()](#isValid--) | Valid property flag. |
| [setValid(boolean value)](#setValid-boolean-) | Valid property flag. |
| [getPageNumber()](#getPageNumber--) | Document Page Number to be verified. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Document Page Number to be verified. |
| [getPagesSetup()](#getPagesSetup--) | Page Options to specify pages to be verified. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Page Options to specify pages to be verified. |
| [getAllPages()](#getAllPages--) | Flag to verify each document page. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | Flag to verify each document page. |
| [getExtensions()](#getExtensions--) | Additional extensions for alternative signature options verification. |
| [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | Additional extensions for alternative signature options verification. |
| [toString()](#toString--) | Override string conversion. |
### isValid() {#isValid--}
```
public final boolean isValid()
```


Valid property flag.

**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Valid property flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Document Page Number to be verified. If property is not set - all Pages of Document will be verified for first occurrence. Minimal value is 1.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


Document Page Number to be verified. If property is not set - all Pages of Document will be verified for first occurrence. Minimal value is 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Page Options to specify pages to be verified.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Page Options to specify pages to be verified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Flag to verify each document page. By default value is true.

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Flag to verify each document page. By default value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


Additional extensions for alternative signature options verification.

**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


Additional extensions for alternative signature options verification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


Override string conversion.

**Returns:**
java.lang.String - 
