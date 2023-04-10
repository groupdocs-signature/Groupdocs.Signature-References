---
title: ImageSearchOptions
second_title: GroupDocs.Signature for Java API Reference
description: Represents search options for Image signatures.
type: docs
weight: 13
url: /java/com.groupdocs.signature.options.search/imagesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class ImageSearchOptions extends SearchOptions
```

Represents search options for Image signatures.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageSearchOptions()](#ImageSearchOptions--) | Initializes a new instance of the ImageSearchOptions class with default values. |
## Methods

| Method | Description |
| --- | --- |
| [getReturnContent()](#getReturnContent--) | Gets or sets flag to grab image content of signature on document page. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Gets or sets flag to grab image content of signature on document page. |
| [getMinContentSize()](#getMinContentSize--) | For non zero value this flag specifies minimal size of images for search criteria. |
| [setMinContentSize(long value)](#setMinContentSize-long-) | For non zero value this flag specifies minimal size of images for search criteria. |
| [getMaxContentSize()](#getMaxContentSize--) | For non zero value this flag specifies maximum size of images for search criteria. |
| [setMaxContentSize(long value)](#setMaxContentSize-long-) | For non zero value this flag specifies maximum size of images for search criteria. |
| [getReturnContentType()](#getReturnContentType--) | Specifies file type of returned content of the image signature when ReturnContent property is enabled. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Specifies file type of returned content of the image signature when ReturnContent property is enabled. |
### ImageSearchOptions() {#ImageSearchOptions--}
```
public ImageSearchOptions()
```


Initializes a new instance of the ImageSearchOptions class with default values.

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Gets or sets flag to grab image content of signature on document page. If this flag is set true, image signature content will keep raw image data by required format  ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). By default this option is disabled.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Gets or sets flag to grab image content of signature on document page. If this flag is set true, image signature content will keep raw image data by required format  ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). By default this option is disabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMinContentSize() {#getMinContentSize--}
```
public final long getMinContentSize()
```


For non zero value this flag specifies minimal size of images for search criteria. By default this flag is set to zero and does not affect search result.

**Returns:**
long
### setMinContentSize(long value) {#setMinContentSize-long-}
```
public final void setMinContentSize(long value)
```


For non zero value this flag specifies minimal size of images for search criteria. By default this flag is set to zero and does not affect search result.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getMaxContentSize() {#getMaxContentSize--}
```
public final long getMaxContentSize()
```


For non zero value this flag specifies maximum size of images for search criteria. By default this flag is set to zero and does not affect search result.

**Returns:**
long
### setMaxContentSize(long value) {#setMaxContentSize-long-}
```
public final void setMaxContentSize(long value)
```


For non zero value this flag specifies maximum size of images for search criteria. By default this flag is set to zero and does not affect search result.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Specifies file type of returned content of the image signature when ReturnContent property is enabled. By default it set to Null. That means to return image content in original format. This image format is specified at  ImageSignature.Format  Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. If provided format is not supported than image content in original format will be returned.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Specifies file type of returned content of the image signature when ReturnContent property is enabled. By default it set to Null. That means to return image content in original format. This image format is specified at  ImageSignature.Format  Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. If provided format is not supported than image content in original format will be returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

