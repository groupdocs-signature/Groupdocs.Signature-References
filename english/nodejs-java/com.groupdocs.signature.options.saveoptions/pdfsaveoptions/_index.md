---
title: PdfSaveOptions
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Save options for PDF documents.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
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
| [PdfSaveOptions()](#PdfSaveOptions--) | Initializes a new instance of PdfSaveOptions class with default values. |
| [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | Initializes a new instance of PdfSaveOptions class with specified output file format. |
| [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | Initializes a new instance of PdfSaveOptions class with overwrite flag. |
| [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | Initializes a new instance of PdfSaveOptions class with specified output file format and overwrite flag. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Gets or sets file format of signed document. |
| [setFileFormat(int value)](#setFileFormat-int-) | Gets or sets file format of signed document. |
| [toString()](#toString--) | Override string conversion. |
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
| fileFormat | int | Output file type [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


Initializes a new instance of PdfSaveOptions class with overwrite flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| overwriteExistingFile | boolean | Flag whether to overwrite signed file with same file. |

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initializes a new instance of PdfSaveOptions class with specified output file format and overwrite flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileFormat | int | Output file type [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
| overwriteExistingFile | boolean | Flag whether to overwrite signed file with same file. |

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

### toString() {#toString--}
```
public String toString()
```


Override string conversion.

**Returns:**
java.lang.String - 
