---
title: SearchOptions
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents the extract signatures from document options.
type: docs
weight: 17
url: /nodejs-java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)
```
public abstract class SearchOptions extends OptionsExtensions
```

Represents the extract signatures from document options.
## Methods

| Method | Description |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | Gets or sets Document page number for searching. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Gets or sets Document page number for searching. |
| [getPagesSetup()](#getPagesSetup--) | Options to specify pages for Signature searching. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Options to specify pages for Signature searching. |
| [getAllPages()](#getAllPages--) | Flag to search on each Document page. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | Flag to search on each Document page. |
| [getSkipExternal()](#getSkipExternal--) | Flag to return only signatures marked as IsSignature. |
| [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | Flag to return only signatures marked as IsSignature. |
| [getSearchPages(int totalPages)](#getSearchPages-int-) | Virtual method to get list of pages for Signature extraction. |
| [toString()](#toString--) | Override string conversion. |
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Gets or sets Document page number for searching. Value is optional.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Gets or sets Document page number for searching. Value is optional.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Options to specify pages for Signature searching.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Options to specify pages for Signature searching.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Flag to search on each Document page. By default this value is set to true.

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Flag to search on each Document page. By default this value is set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


Flag to return only signatures marked as IsSignature. By default value is false that indicates to return all signatures that match specified criteria.

**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


Flag to return only signatures marked as IsSignature. By default value is false that indicates to return all signatures that match specified criteria.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


Virtual method to get list of pages for Signature extraction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| totalPages | int | Total count of pages |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - List of page numbers
### toString() {#toString--}
```
public String toString()
```


Override string conversion.

**Returns:**
java.lang.String - 
