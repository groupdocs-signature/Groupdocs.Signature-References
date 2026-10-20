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
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.signature.domain.documentpreview.FileType-) | Initializes a new instance of LoadOptions class with a specified file type.
 |
## Methods

| Method | Description |
| --- | --- |
| [getPassword()](#getPassword--) | Gets or sets password to open a protected document.
 |
| [setPassword(String value)](#setPassword-java.lang.String-) | Gets or sets password to open a protected document.
 |
| [getSkipExternalResources()](#getSkipExternalResources--) | Gets or sets a flag that tells whether resources stored outside the document are skipped when it is loaded.
 |
| [setSkipExternalResources(boolean value)](#setSkipExternalResources-boolean-) | Gets or sets a flag that tells whether resources stored outside the document are skipped when it is loaded.
 |
| [getWhitelistedResources()](#getWhitelistedResources--) | Gets or sets parts of addresses of external resources that may be loaded while
#getSkipExternalResources().getSkipExternalResources() is true.
 |
| [setWhitelistedResources(List<String> value)](#setWhitelistedResources-java.util.List-java.lang.String--) | Gets or sets parts of addresses of external resources that may be loaded while
#getSkipExternalResources().getSkipExternalResources() is true.
 |
| [getPermissions()](#getPermissions--) | The PDF document permissions such as printing, modification and data extraction.
 |
| [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Internal setter, used by document load processors to record permissions parsed from the file.
 |
| [getFileType()](#getFileType--) | Gets the file type of the document.
 |
| [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | Sets the file type of the document, so it is not detected from the document content.
 |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initializes a new instance of LoadOptions class.


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public LoadOptions(FileType fileType)
```


Initializes a new instance of LoadOptions class with a specified file type.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) | The file type of the document, see #setFileType(FileType).setFileType(FileType).
 |

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

### getSkipExternalResources() {#getSkipExternalResources--}
```
public final boolean getSkipExternalResources()
```


Gets or sets a flag that tells whether resources stored outside the document are skipped when it is loaded.
The default value is true.


A document can refer to resources outside it: linked images and INCLUDEPICTURE fields in word processing
documents, linked pictures in presentations and spreadsheets, images and style sheets an SVG image refers to.
Loading such a resource means requesting the address written in the document. On a server that processes
documents from other people that is a server-side request forgery risk, and on an offline installation the
request fails or waits for a time-out.


When true, external resources are not loaded, except those whose address contains one of
#getWhitelistedResources().getWhitelistedResources(). Skipped resources are not drawn in page previews or in documents saved as
images, and image, barcode and QR-code search does not see them. Embedded images are not affected, and
hyperlinks are never followed. The setting also applies to documents inside archives.


**Returns:**
boolean
### setSkipExternalResources(boolean value) {#setSkipExternalResources-boolean-}
```
public final void setSkipExternalResources(boolean value)
```


Gets or sets a flag that tells whether resources stored outside the document are skipped when it is loaded.
The default value is true. See #getSkipExternalResources().getSkipExternalResources().


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public final List<String> getWhitelistedResources()
```


Gets or sets parts of addresses of external resources that may be loaded while
#getSkipExternalResources().getSkipExternalResources() is true. An address is loaded when it contains one of them, ignoring case.
Empty values are ignored. The default is an empty list; setting null clears it.


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> value) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public final void setWhitelistedResources(List<String> value)
```


Gets or sets parts of addresses of external resources that may be loaded while
#getSkipExternalResources().getSkipExternalResources() is true. See #getWhitelistedResources().getWhitelistedResources().


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<java.lang.String> |  |

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

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Gets the file type of the document. When it is [FileType.Unknown](../../com.groupdocs.signature.domain.documentpreview/filetype#Unknown) (the default),
the file type is detected from the document content.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


Sets the file type of the document, so it is not detected from the document content.
[FileType.Unknown](../../com.groupdocs.signature.domain.documentpreview/filetype#Unknown) (the default) or null detects it.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

