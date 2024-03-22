---
title: TextSignOptions
second_title: GroupDocs.Signature for Java API Reference
description: Represents the Text signature options.
type: docs
weight: 18
url: /java/com.groupdocs.signature.options.sign/textsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class TextSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency
```

Represents the Text signature options.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextSignOptions()](#TextSignOptions--) | Initializes a new instance of the SignTextOptions class with default values. |
| [TextSignOptions(String text)](#TextSignOptions-java.lang.String-) | Initializes a new instance of the SignTextOptions class with text. |
## Fields

| Field | Description |
| --- | --- |
| [DEFAULT_TRANSPARENCY](#DEFAULT-TRANSPARENCY) |  |
## Methods

| Method | Description |
| --- | --- |
| [getLeft()](#getLeft--) | Left X position of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType property). |
| [setLeft(int value)](#setLeft-int-) | Left X position of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType property). |
| [getTop()](#getTop--) | Top Y Position of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType property). |
| [setTop(int value)](#setTop-int-) | Top Y Position of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType property). |
| [getWidth()](#getWidth--) | Width of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType property). |
| [setWidth(int value)](#setWidth-int-) | Width of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType property). |
| [getHeight()](#getHeight--) | Height of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType property). |
| [setHeight(int value)](#setHeight-int-) | Height of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType property). |
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
| [getText()](#getText--) | Gets or sets the text of signature. |
| [setText(String value)](#setText-java.lang.String-) | Gets or sets the text of signature. |
| [getFont()](#getFont--) | Gets or sets the font of signature. |
| [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | Gets or sets the font of signature. |
| [getForeColor()](#getForeColor--) | Gets or sets the fore color of signature. |
| [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Gets or sets the fore color of signature. |
| [getSignatureImplementation()](#getSignatureImplementation--) | Gets or sets the type of text signature implementation. |
| [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Gets or sets the type of text signature implementation. |
| [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Horizontal alignment of text inside a signature. |
| [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Horizontal alignment of text inside a signature. |
| [getTextVerticalAlignment()](#getTextVerticalAlignment--) | Vertical alignment of text inside a signature. |
| [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | Vertical alignment of text inside a signature. |
| [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Gets or sets the title of text form field to put text signature into it. |
| [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Gets or sets the title of text form field to put text signature into it. |
| [getFormTextFieldType()](#getFormTextFieldType--) | Gets or sets the type of form field to put text signature into it. |
| [setFormTextFieldType(int value)](#setFormTextFieldType-int-) | Gets or sets the type of form field to put text signature into it. |
| [getShapeType()](#getShapeType--) | Gets or sets the type of shape to put text. |
| [setShapeType(int value)](#setShapeType-int-) | Gets or sets the type of shape to put text. |
| [getSignatureID()](#getSignatureID--) | Gets or sets the unique ID of signature. |
| [setSignatureID(int value)](#setSignatureID-int-) | Gets or sets the unique ID of signature. |
| [getBorder()](#getBorder--) | Specify border settings |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Specify border settings |
| [getBackground()](#getBackground--) | Gets or sets the signature background settings. |
| [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Gets or sets the signature background settings. |
| [getNative()](#getNative--) | Gets or sets the native attribute. |
| [setNative(boolean value)](#setNative-boolean-) | Gets or sets the native attribute. |
| [getShapePosition()](#getShapePosition--) | Defines where shape should be presented in the document layout |
| [setShapePosition(int value)](#setShapePosition-int-) | Defines where shape should be presented in the document layout |
| [validate()](#validate--) | Internal method to validate the options parameters. |
| [toString()](#toString--) | Override string conversion. |
### TextSignOptions() {#TextSignOptions--}
```
public TextSignOptions()
```


Initializes a new instance of the SignTextOptions class with default values.

### TextSignOptions(String text) {#TextSignOptions-java.lang.String-}
```
public TextSignOptions(String text)
```


Initializes a new instance of the SignTextOptions class with text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Signature text. |

### DEFAULT_TRANSPARENCY {#DEFAULT-TRANSPARENCY}
```
public static final double DEFAULT_TRANSPARENCY
```


### getLeft() {#getLeft--}
```
public final int getLeft()
```


Left X position of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType property). (works if horizontal alignment is not specified).

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Left X position of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType property). (works if horizontal alignment is not specified).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Top Y Position of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType property). (works if vertical alignment is not specified).

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Top Y Position of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType property). (works if vertical alignment is not specified).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Width of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType property).

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Width of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType property).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Height of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType property).

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Height of Signature on Document Page in Measure values (pixels, percents or millimeters see [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType property).

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

### getText() {#getText--}
```
public final String getText()
```


Gets or sets the text of signature.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Gets or sets the text of signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


Gets or sets the font of signature.

**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


Gets or sets the font of signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Gets or sets the fore color of signature.

**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Gets or sets the fore color of signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Gets or sets the type of text signature implementation.

**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Gets or sets the type of text signature implementation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public final int getTextHorizontalAlignment()
```


Horizontal alignment of text inside a signature. This feature is supported only for Image and Annotation signature implementations (see [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation property).

**Returns:**
int
### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public final void setTextHorizontalAlignment(int value)
```


Horizontal alignment of text inside a signature. This feature is supported only for Image and Annotation signature implementations (see [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation property).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


Vertical alignment of text inside a signature. This feature is supported only for Image signature implementation (see [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation property).

**Returns:**
int
### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


Vertical alignment of text inside a signature. This feature is supported only for Image signature implementation (see [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation property).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Gets or sets the title of text form field to put text signature into it. This property could be used only with SignatureImplementation = TextToFormField.

**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Gets or sets the title of text form field to put text signature into it. This property could be used only with SignatureImplementation = TextToFormField.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final int getFormTextFieldType()
```


Gets or sets the type of form field to put text signature into it. This property could be used only with SignatureImplementation = TextToFormField. Value by default is AllTextTypes.

**Returns:**
int
### setFormTextFieldType(int value) {#setFormTextFieldType-int-}
```
public final void setFormTextFieldType(int value)
```


Gets or sets the type of form field to put text signature into it. This property could be used only with SignatureImplementation = TextToFormField. Value by default is AllTextTypes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Gets or sets the type of shape to put text. This property could be used only with SignatureImplementation = TextStamp. Value by default is Rectangle.

**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public final void setShapeType(int value)
```


Gets or sets the type of shape to put text. This property could be used only with SignatureImplementation = TextStamp. Value by default is Rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Gets or sets the unique ID of signature. It can be used in signature verification options. Property is supported for Pdf documents only

**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Gets or sets the unique ID of signature. It can be used in signature verification options. Property is supported for Pdf documents only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Gets or sets the signature background settings.

**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Gets or sets the signature background settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getNative() {#getNative--}
```
public final boolean getNative()
```


Gets or sets the native attribute. If it is set document specific signatures could be used. Native text watermark for WordProcessing documents is different than regular, for example.

**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Gets or sets the native attribute. If it is set document specific signatures could be used. Native text watermark for WordProcessing documents is different than regular, for example.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


Defines where shape should be presented in the document layout

**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


Defines where shape should be presented in the document layout

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### validate() {#validate--}
```
public void validate()
```


Internal method to validate the options parameters.

### toString() {#toString--}
```
public String toString()
```


Override string conversion.

**Returns:**
java.lang.String - 
