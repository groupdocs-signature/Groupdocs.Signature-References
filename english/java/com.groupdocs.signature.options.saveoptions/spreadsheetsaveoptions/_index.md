---
title: SpreadsheetSaveOptions
second_title: GroupDocs.Signature for Java API Reference
description: Save options for Spreadsheet Documents.
type: docs
weight: 14
url: /java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

Save options for Spreadsheet Documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Initializes a new instance of SpreadsheetSaveOptions class with default values. |
| [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | Initializes a new instance of SpreadsheetSaveOptions class with predefined output file format. |
| [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | Initializes a new instance of SpreadsheetSaveOptions class with specified output type and overwrite flag. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Gets or sets file format of signed document. |
| [setFileFormat(int value)](#setFileFormat-int-) | Gets or sets file format of signed document. |
| [toString()](#toString--) | Override string conversion. |
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Initializes a new instance of SpreadsheetSaveOptions class with default values.

### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


Initializes a new instance of SpreadsheetSaveOptions class with predefined output file format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileFormat | int | Specifies output file format. |

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initializes a new instance of SpreadsheetSaveOptions class with specified output type and overwrite flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileFormat | int | Specifies output file format. |
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
