---
title: ImageSignOptions
second_title: GroupDocs.Signature for Java API Reference
description: Represents the Image signature options.
type: docs
weight: 13
url: /java/com.groupdocs.signature.options.sign/imagesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency), com.aspose.ms.System.IDisposable
```
public class ImageSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency, System.IDisposable
```

Represents the Image signature options.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageSignOptions()](#ImageSignOptions--) | Initializes a new instance of the ImageSignOptions class with default values. |
| [ImageSignOptions(String imageFilePath)](#ImageSignOptions-java.lang.String-) | Initializes a new instance of the ImageSignOptions class with image file. |
| [ImageSignOptions(InputStream imageStream)](#ImageSignOptions-java.io.InputStream-) | Initializes a new instance of the ImageSignOptions class with image stream. |
## Methods

| Method | Description |
| --- | --- |
| [getAllPages()](#getAllPages--) | Put signature on all document pages. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | Put signature on all document pages. |
| [getImageFilePath()](#getImageFilePath--) | Gets or sets the signature image file path. |
| [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Gets or sets the signature image file path. |
| [getImageStream()](#getImageStream--) | Gets or sets the signature image stream. |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Gets or sets the signature image stream. |
| [getLeft()](#getLeft--) | Left X position of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [setLeft(int value)](#setLeft-int-) | Left X position of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [getTop()](#getTop--) | Top Y Position of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [setTop(int value)](#setTop-int-) | Top Y Position of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [getWidth()](#getWidth--) | Width of Signature on Document Page in Measure values (pixels, percents or millimeters [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [setWidth(int value)](#setWidth-int-) | Width of Signature on Document Page in Measure values (pixels, percents or millimeters [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [getHeight()](#getHeight--) | Height of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [setHeight(int value)](#setHeight-int-) | Height of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [getLocationMeasureType()](#getLocationMeasureType--) | Measure type (pixels, percents or millimeters) for Left and Top properties. |
| [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | Measure type (pixels, percents or millimeters) for Left and Top properties. |
| [getSizeMeasureType()](#getSizeMeasureType--) | Measure type (pixels, percents or millimeters) for Width and Height properties. |
| [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | Measure type (pixels, percents or millimeters) for Width and Height properties. |
| [getStretch()](#getStretch--) | Stretch mode on Document Page. |
| [setStretch(int value)](#setStretch-int-) | Stretch mode on Document Page. |
| [getRotationAngle()](#getRotationAngle--) | Rotation angle of signature on document page (clockwise). |
| [setRotationAngle(int value)](#setRotationAngle-int-) | Rotation angle of signature on document page (clockwise). |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Horizontal alignment of signature on document page. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Horizontal alignment of signature on document page. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Vertical alignment of signature on document page. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Vertical alignment of signature on document page. |
| [getMargin()](#getMargin--) | Gets or sets the space between Sign and Document edges. |
| [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | Gets or sets the space between Sign and Document edges. |
| [getMarginMeasureType()](#getMarginMeasureType--) | Gets or sets the measure type (pixels, percents or millimeters) for Margin. |
| [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Gets or sets the measure type (pixels, percents or millimeters) for Margin. |
| [getTransparency()](#getTransparency--) | Gets or sets the signature transparency (value from 0.0 (opaque) through 1.0 (clear)). |
| [setTransparency(double value)](#setTransparency-double-) | Gets or sets the signature transparency (value from 0.0 (opaque) through 1.0 (clear)). |
| [getRectangle()](#getRectangle--) | Rectangle of area to put the image on document. |
| [getBorder()](#getBorder--) | Specify border settings |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Specify border settings |
| [toString()](#toString--) | Override string conversion. |
| [fromBase64(String base64Content)](#fromBase64-java.lang.String-) | Creates a new instance of the ImageSignOptions class with predefined Image from Base64. |
| [dispose()](#dispose--) | Clears internal resources |
### ImageSignOptions() {#ImageSignOptions--}
```
public ImageSignOptions()
```


Initializes a new instance of the ImageSignOptions class with default values.

### ImageSignOptions(String imageFilePath) {#ImageSignOptions-java.lang.String-}
```
public ImageSignOptions(String imageFilePath)
```


Initializes a new instance of the ImageSignOptions class with image file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageFilePath | java.lang.String | Image file path |

### ImageSignOptions(InputStream imageStream) {#ImageSignOptions-java.io.InputStream-}
```
public ImageSignOptions(InputStream imageStream)
```


Initializes a new instance of the ImageSignOptions class with image stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream | Image stream |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


Put signature on all document pages. This property can only be used for multi-frames image formats (Tiff).

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


Put signature on all document pages. This property can only be used for multi-frames image formats (Tiff).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Gets or sets the signature image file path. This property is used only if ImageStream is not specified.

**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Gets or sets the signature image file path. This property is used only if ImageStream is not specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Gets or sets the signature image stream. If this property is specified it is always used instead ImageGuid.

**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Gets or sets the signature image stream. If this property is specified it is always used instead ImageGuid.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream |  |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Left X position of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (works if horizontal alignment is not specified).

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Left X position of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (works if horizontal alignment is not specified).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Top Y Position of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (works if vertical alignment is not specified).

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Top Y Position of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (works if vertical alignment is not specified).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Width of Signature on Document Page in Measure values (pixels, percents or millimeters [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Width of Signature on Document Page in Measure values (pixels, percents or millimeters [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Height of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Height of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


Measure type (pixels, percents or millimeters) for Left and Top properties.

**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


Measure type (pixels, percents or millimeters) for Left and Top properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


Measure type (pixels, percents or millimeters) for Width and Height properties.

**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


Measure type (pixels, percents or millimeters) for Width and Height properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


Stretch mode on Document Page.

**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


Stretch mode on Document Page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Rotation angle of signature on document page (clockwise).

**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Rotation angle of signature on document page (clockwise).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Horizontal alignment of signature on document page.

**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Horizontal alignment of signature on document page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Vertical alignment of signature on document page.

**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Vertical alignment of signature on document page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


Gets or sets the space between Sign and Document edges. (works ONLY if horizontal or vertical alignment are specified).

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


Gets or sets the space between Sign and Document edges. (works ONLY if horizontal or vertical alignment are specified).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


Gets or sets the measure type (pixels, percents or millimeters) for Margin.

**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


Gets or sets the measure type (pixels, percents or millimeters) for Margin.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Gets or sets the signature transparency (value from 0.0 (opaque) through 1.0 (clear)). Default value is 0 (opaque).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Gets or sets the signature transparency (value from 0.0 (opaque) through 1.0 (clear)). Default value is 0 (opaque).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


Rectangle of area to put the image on document.

**Returns:**
java.awt.Rectangle
### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Specify border settings

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Specify border settings

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### toString() {#toString--}
```
public String toString()
```


Override string conversion.

**Returns:**
java.lang.String - 
### fromBase64(String base64Content) {#fromBase64-java.lang.String-}
```
public static ImageSignOptions fromBase64(String base64Content)
```


Creates a new instance of the ImageSignOptions class with predefined Image from Base64.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| base64Content | java.lang.String | Image content in Base64 string format |

**Returns:**
[ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions) - 
### dispose() {#dispose--}
```
public final void dispose()
```


Clears internal resources

