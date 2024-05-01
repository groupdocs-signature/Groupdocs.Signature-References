---
title: IAlignment
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Interface describes alignment of Signature area on document page.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.signature.domain.interfaces/ialignment/
---```
public interface IAlignment
```

Interface describes alignment of Signature area on document page.
## Methods

| Method | Description |
| --- | --- |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Horizontal alignment of Image on Document Page. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Horizontal alignment of Image on Document Page. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Vertical alignment of Image on Document Page. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Vertical alignment of Image on Document Page. |
| [getMargin()](#getMargin--) | Gets the space that is specified by default between Image and Document edges (works if horizontal or vertical alignment is specified). |
| [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | Gets the space that is specified by default between Image and Document edges (works if horizontal or vertical alignment is specified). |
| [getMarginMeasureType()](#getMarginMeasureType--) | Margin measurement type (pixels, percents or millimeters). |
| [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Margin measurement type (pixels, percents or millimeters). |
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public abstract int getHorizontalAlignment()
```


Horizontal alignment of Image on Document Page.

**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public abstract void setHorizontalAlignment(int value)
```


Horizontal alignment of Image on Document Page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public abstract int getVerticalAlignment()
```


Vertical alignment of Image on Document Page.

**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public abstract void setVerticalAlignment(int value)
```


Vertical alignment of Image on Document Page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMargin() {#getMargin--}
```
public abstract Padding getMargin()
```


Gets the space that is specified by default between Image and Document edges (works if horizontal or vertical alignment is specified).

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public abstract void setMargin(Padding value)
```


Gets the space that is specified by default between Image and Document edges (works if horizontal or vertical alignment is specified).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public abstract int getMarginMeasureType()
```


Margin measurement type (pixels, percents or millimeters).

**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public abstract void setMarginMeasureType(int value)
```


Margin measurement type (pixels, percents or millimeters).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

