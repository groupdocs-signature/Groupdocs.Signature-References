---
title: PreviewOptions
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents document preview options.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Represents document preview options.
## Constructors

| Constructor | Description |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | Initializes PreviewOptions object. |
| [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | Initializes PreviewOptions object. |
| [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | Initializes PreviewOptions object. |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Gets or sets preview images width. |
| [setWidth(int value)](#setWidth-int-) | Gets or sets preview images width. |
| [getHeight()](#getHeight--) | Gets or sets preview images height. |
| [setHeight(int value)](#setHeight-int-) | Gets or sets preview images height. |
| [getPageNumbers()](#getPageNumbers--) | Gets or sets preview images page numbers. |
| [setPageNumbers(int[] value)](#setPageNumbers-int---) | Gets or sets preview images page numbers. |
| [getPreviewFormat()](#getPreviewFormat--) | Gets or sets preview images format. |
| [setPreviewFormat(int value)](#setPreviewFormat-int-) | Gets or sets preview images format. |
| [getHideSignatures()](#getHideSignatures--) | Gets or sets flag to hide signatures from page preview image. |
| [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | Gets or sets flag to hide signatures from page preview image. |
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


Initializes PreviewOptions object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | Interface which defines method to create output page preview stream. |
| pageNumbers | int[] | Desired page numbers |

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


Initializes PreviewOptions object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | Interface which defines method to create output page preview stream. |
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


Initializes PreviewOptions object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | Path to output file. |
| pageNumbers | int[] | Desired page numbers |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets or sets preview images width.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Gets or sets preview images width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets or sets preview images height.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Gets or sets preview images height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Gets or sets preview images page numbers.

**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Gets or sets preview images page numbers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Gets or sets preview images format.

**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Gets or sets preview images format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


Gets or sets flag to hide signatures from page preview image. Only signatures are marked as IsSignature will be hidden from generated document page image.

**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


Gets or sets flag to hide signatures from page preview image. Only signatures are marked as IsSignature will be hidden from generated document page image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

