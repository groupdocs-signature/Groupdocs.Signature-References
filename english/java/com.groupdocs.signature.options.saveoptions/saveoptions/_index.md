---
title: SaveOptions
second_title: GroupDocs.Editor for Java API Reference
description: Allows to specify additional options such as password when saving a document to sign.
type: docs
weight: 13
url: /java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Allows to specify additional options (such as password) when saving a document to sign.
## Constructors

| Constructor | Description |
| --- | --- |
| [SaveOptions()](#SaveOptions--) | Initializes a new instance of SaveOptions class with default values. |
| [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | Initializes a new instance of SaveOptions class with specified output type and overwrite flag. |
## Methods

| Method | Description |
| --- | --- |
| [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | Gets or sets whether to overwrite existing file with new output file. |
| [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | Gets or sets whether to overwrite existing file with new output file. |
| [getPassword()](#getPassword--) | Gets or sets password to save signed document with password protection. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Gets or sets password to save signed document with password protection. |
| [getUseOriginalPassword()](#getUseOriginalPassword--) | Gets or sets whether to use password from LoadOptions to save signed document as protected. |
| [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | Gets or sets whether to use password from LoadOptions to save signed document as protected. |
| [getAddMissingExtenstion()](#getAddMissingExtenstion--) | Gets or sets flag to automatically add extension when it was missing in output file path Default value is false. |
| [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | Gets or sets flag to automatically add extension when it was missing in output file path Default value is false. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Initializes a new instance of SaveOptions class with default values.

### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


Initializes a new instance of SaveOptions class with specified output type and overwrite flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| overwriteExistingFile | boolean | Flag whether to overwrite signed file with same file. |

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


Gets or sets whether to overwrite existing file with new output file. Otherwise new file will be created with number as suffix.

**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


Gets or sets whether to overwrite existing file with new output file. Otherwise new file will be created with number as suffix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Gets or sets password to save signed document with password protection. This property is not supported for Image documents.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Gets or sets password to save signed document with password protection. This property is not supported for Image documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


Gets or sets whether to use password from LoadOptions to save signed document as protected. Default value is true. This property is not supported for Image documents.

**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


Gets or sets whether to use password from LoadOptions to save signed document as protected. Default value is true. This property is not supported for Image documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


Gets or sets flag to automatically add extension when it was missing in output file path Default value is false.

**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


Gets or sets flag to automatically add extension when it was missing in output file path Default value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

