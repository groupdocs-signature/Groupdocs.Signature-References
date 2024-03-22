---
title: WordProcessingSaveOptions
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Save options for WordProcessing documents.
type: docs
weight: 15
url: /nodejs-java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

Save options for WordProcessing documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Initializes a new instance of WordProcessingSaveOptions class with default values. |
| [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | Initializes a new instance of WordProcessingSaveOptions class with specified output file format. |
| [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | Initializes a new instance of WordProcessingSaveOptions class with specified output type and overwrite flag. |
| [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | Initializes a new instance of WordProcessingSaveOptions class with specified output file format and overwrite flag. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Gets or sets file format of signed document. |
| [setFileFormat(int value)](#setFileFormat-int-) | Gets or sets file format of signed document. |
| [toString()](#toString--) | Override string conversion |
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Initializes a new instance of WordProcessingSaveOptions class with default values.

### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


Initializes a new instance of WordProcessingSaveOptions class with specified output file format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileFormat | int | Output file type [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


Initializes a new instance of WordProcessingSaveOptions class with specified output type and overwrite flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| overwriteExistingFile | boolean | Flag whether to overwrite signed file with same file. |

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initializes a new instance of WordProcessingSaveOptions class with specified output file format and overwrite flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileFormat | int | Output file type [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
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


Override string conversion

**Returns:**
java.lang.String - 
