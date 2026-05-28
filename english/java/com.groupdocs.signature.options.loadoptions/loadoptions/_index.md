---
title: LoadOptions
second_title: GroupDocs.Signature for Java API Reference
description: Allows to specify additional options such as password when opening a document to sign.
type: docs
weight: 10
url: /java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Allows to specify additional options (such as password) when opening a document to sign.

## Constructors

| Constructor | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Initializes a new instance of LoadOptions class.
 |
## Methods

| Method | Description |
| --- | --- |
| [getPassword()](#getPassword--) | Gets or sets password to open a protected document.
 |
| [setPassword(String value)](#setPassword-java.lang.String-) | Gets or sets password to open a protected document.
 |
| [getLoadExternalResources()](#getLoadExternalResources--) | Gets or sets options that specifies if external document resources should be loaded.
 |
| [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | Gets or sets options that specifies if external document resources should be loaded.
 |
| [getPermissions()](#getPermissions--) | The PDF document permissions such as printing, modification and data extraction.
 |
| [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Internal setter, used by document load processors to record permissions parsed from the file.
 |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initializes a new instance of LoadOptions class.


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Gets or sets password to open a protected document.
It will be also used to save signed document as protected.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Gets or sets password to open a protected document.
It will be also used to save signed document as protected.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


Gets or sets options that specifies if external document resources should be loaded.
This option with disabled value (false) allows to save loading time for the documents with many or large external resource links.
By default value is enabled (true).


**Returns:**
boolean
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


Gets or sets options that specifies if external document resources should be loaded.
This option with disabled value (false) allows to save loading time for the documents with many or large external resource links.
By default value is enabled (true).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


The PDF document permissions such as printing, modification and data extraction.
Only for PDF documents. Read-only \\u2014 populated automatically while loading the document.
The value is a flags combination from [Permissions](../../com.groupdocs.signature.options/permissions).


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Internal setter, used by document load processors to record permissions parsed from the file.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

