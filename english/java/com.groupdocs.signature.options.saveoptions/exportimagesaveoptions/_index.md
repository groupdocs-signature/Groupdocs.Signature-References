---
title: ExportImageSaveOptions
second_title: GroupDocs.Signature for Java API Reference
description: Save options for exporting documents to image.
type: docs
weight: 10
url: /java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

Save options for exporting documents to image.
## Constructors

| Constructor | Description |
| --- | --- |
| [ExportImageSaveOptions()](#ExportImageSaveOptions--) | Initializes a new instance of ExportAsImageSaveOptions class with default values. |
| [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | Initializes a new instance of ExportAsImageSaveOptions class with specified file format. |
## Methods

| Method | Description |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | Gets or sets document page number for export. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Gets or sets document page number for export. |
| [getExportAllPages()](#getExportAllPages--) | Flag to export each page. |
| [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | Flag to export each page. |
| [getPagesSetup()](#getPagesSetup--) | Options to specify pages to be signed. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Options to specify pages to be signed. |
| [getPageColumns()](#getPageColumns--) | Gets or sets number of columns for exported images. |
| [setPageColumns(int value)](#setPageColumns-int-) | Gets or sets number of columns for exported images. |
| [getBorder()](#getBorder--) | Gets or sets the image border settings. |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Gets or sets the image border settings. |
| [getTiffMultipage()](#getTiffMultipage--) | Put document pages on different frames in Tiff image. |
| [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | Put document pages on different frames in Tiff image. |
| [toString()](#toString--) | Override string conversion. |
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


Initializes a new instance of ExportAsImageSaveOptions class with default values.

### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


Initializes a new instance of ExportAsImageSaveOptions class with specified file format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileFormat | int | Output image file format. |

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Gets or sets document page number for export. Minimal value is 1.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Gets or sets document page number for export. Minimal value is 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


Flag to export each page.

**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


Flag to export each page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Options to specify pages to be signed.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Options to specify pages to be signed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


Gets or sets number of columns for exported images. Use this property if you need put images in a row.

**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


Gets or sets number of columns for exported images. Use this property if you need put images in a row.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Gets or sets the image border settings. By default this value is not set.

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Gets or sets the image border settings. By default this value is not set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


Put document pages on different frames in Tiff image.

**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


Put document pages on different frames in Tiff image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Override string conversion.

**Returns:**
java.lang.String - 
