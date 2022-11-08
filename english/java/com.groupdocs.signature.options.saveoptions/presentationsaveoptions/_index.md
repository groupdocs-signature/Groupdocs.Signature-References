---
title: PresentationSaveOptions
second_title: GroupDocs.Signature for Java API Reference
description: Save options for Presentation documents.
type: docs
weight: 12
url: /java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

Save options for Presentation documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationSaveOptions()](#PresentationSaveOptions--) | Initializes a new instance of PresentationSaveOptions class with default values. |
| [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | Initializes a new instance of PresentationSaveOptions class with specified output file format. |
| [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | Initializes a new instance of PresentationSaveOptions class with specified output type and overwrite flag. |
| [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | Initializes a new instance of PresentationSaveOptions class with specified output file format and overwrite flag. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Gets or sets file format of signed document. |
| [setFileFormat(int value)](#setFileFormat-int-) | Gets or sets file format of signed document. |
| [toString()](#toString--) | Override string conversion. |
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Initializes a new instance of PresentationSaveOptions class with default values.

### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


Initializes a new instance of PresentationSaveOptions class with specified output file format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileFormat | int | Output file type [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


Initializes a new instance of PresentationSaveOptions class with specified output type and overwrite flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| overwriteExistingFile | boolean | Flag whether to overwrite signed file with same file. |

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initializes a new instance of PresentationSaveOptions class with specified output file format and overwrite flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileFormat | int | Output file type [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
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
