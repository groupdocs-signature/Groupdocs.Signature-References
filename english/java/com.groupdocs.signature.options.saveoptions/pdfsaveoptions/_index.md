---
title: PdfSaveOptions
second_title: GroupDocs.Signature for Java API Reference
description: Save options for PDF documents.
type: docs
weight: 11
url: /java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

Save options for PDF documents.

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | Initializes a new instance of PdfSaveOptions class with default values.
 |
| [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | Initializes a new instance of PdfSaveOptions class with specified output file format.
 |
| [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | Initializes a new instance of PdfSaveOptions class with overwrite flag.
 |
| [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | Initializes a new instance of PdfSaveOptions class with specified output file format and overwrite flag.
 |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Gets or sets file format of signed document.
 |
| [setFileFormat(int value)](#setFileFormat-int-) | Gets or sets file format of signed document.
 |
| [getPermissionsPassword()](#getPermissionsPassword--) | A permissions password (the primary password) requires a password to change permission settings.
 |
| [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | A permissions password (the primary password) requires a password to change permission settings.
 |
| [getPermissions()](#getPermissions--) | The PDF document permissions such as printing, modification and data extraction.
 |
| [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | The PDF document permissions such as printing, modification and data extraction.
 |
| [toString()](#toString--) | Override string conversion.
 |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


Initializes a new instance of PdfSaveOptions class with default values.


### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


Initializes a new instance of PdfSaveOptions class with specified output file format.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileFormat | int | Output file type [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat).
 |

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


Initializes a new instance of PdfSaveOptions class with overwrite flag.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| overwriteExistingFile | boolean | Flag whether to overwrite signed file with same file.
 |

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initializes a new instance of PdfSaveOptions class with specified output file format and overwrite flag.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileFormat | int | Output file type [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat).
 |
| overwriteExistingFile | boolean | Flag whether to overwrite signed file with same file.
 |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Gets or sets file format of signed document.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Gets or sets file format of signed document.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


A permissions password (the primary password) requires a password to change permission settings.


**Returns:**
java.lang.String
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


A permissions password (the primary password) requires a password to change permission settings.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


The PDF document permissions such as printing, modification and data extraction.


To modify these permissions, the 
PermissionsPassword
 must be set.
The value is a flags combination from [Permissions](../../com.groupdocs.signature.options/permissions).
A 
null
 value means no explicit permissions are applied.


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


The PDF document permissions such as printing, modification and data extraction.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


Override string conversion.


**Returns:**
java.lang.String - 
