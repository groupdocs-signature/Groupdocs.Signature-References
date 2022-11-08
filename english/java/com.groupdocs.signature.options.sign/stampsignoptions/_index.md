---
title: StampSignOptions
second_title: GroupDocs.Signature for Java API Reference
description: Represents the Stamp signature options.
type: docs
weight: 17
url: /java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

Represents the Stamp signature options.
## Constructors

| Constructor | Description |
| --- | --- |
| [StampSignOptions()](#StampSignOptions--) | Initializes a new instance of the StampSignOptions class with default values. |
| [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | Initializes a new instance of the StampSignOptions class with alignment options. |
## Methods

| Method | Description |
| --- | --- |
| [getStampType()](#getStampType--) | Gets or sets stamp type. |
| [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | Gets or sets stamp type. |
| [getOuterLines()](#getOuterLines--) | List of Outer Lines rendered as concentric circles. |
| [getInnerLines()](#getInnerLines--) | List of Inner Lines rendered as set of rectangles. |
| [getBackground()](#getBackground--) | Gets or sets the Stamp background. |
| [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Gets or sets the Stamp background. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets or sets the background color of signature. |
| [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | Gets or sets the background color of signature. |
| [getBackgroundBrush()](#getBackgroundBrush--) | Gets or sets the signature background brush. |
| [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | Gets or sets the signature background brush. |
| [getBackgroundColorCropType()](#getBackgroundColorCropType--) | Gets or sets the background color crop type of signature. |
| [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | Gets or sets the background color crop type of signature. |
| [getBackgroundImageCropType()](#getBackgroundImageCropType--) | Gets or sets the background image crop type of signature. |
| [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | Gets or sets the background image crop type of signature. |
| [toString()](#toString--) | Override string conversion |
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


Initializes a new instance of the StampSignOptions class with default values.

### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


Initializes a new instance of the StampSignOptions class with alignment options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | int | The x-coordinate of the left top edge of Stamp Signature |
| top | int | The y-coordinate of the left top edge of Stamp Signature |
| width | int | The width of Stamp Signature |
| height | int | The height of Stamp Signature |

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


Gets or sets stamp type. Value by default is Round.

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


Gets or sets stamp type. Value by default is Round.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


List of Outer Lines rendered as concentric circles.

**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


List of Inner Lines rendered as set of rectangles.

**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Gets or sets the Stamp background.

**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Gets or sets the Stamp background.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Gets or sets the background color of signature.

**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


Gets or sets the background color of signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


Gets or sets the signature background brush. Value by default is null.

**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


Gets or sets the signature background brush. Value by default is null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


Gets or sets the background color crop type of signature.

**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


Gets or sets the background color crop type of signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


Gets or sets the background image crop type of signature.

**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


Gets or sets the background image crop type of signature.

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
