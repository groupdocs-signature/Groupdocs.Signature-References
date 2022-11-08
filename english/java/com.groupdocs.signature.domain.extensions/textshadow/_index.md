---
title: TextShadow
second_title: GroupDocs.Signature for Java API Reference
description: Represents text shadow properties for text signatures.
type: docs
weight: 16
url: /java/com.groupdocs.signature.domain.extensions/textshadow/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.SignatureExtension](../../com.groupdocs.signature.domain.extensions/signatureextension)
```
public class TextShadow extends SignatureExtension
```

Represents text shadow properties for text signatures. The result may vary depending on the signature type and document format. TextShadow is recommended for using with TextAsImage signature for all supported document types, also with simple TextSignature and TextSignature as watermark for Cells (.xslx) and Slides (.pptx). Simple TextSignature for Words (.docx) is recommended too, but has limited functionality.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextShadow()](#TextShadow--) | Creates TextShadow with default options. |
## Methods

| Method | Description |
| --- | --- |
| [getDistance()](#getDistance--) | Gets or sets distance from text to shadow. |
| [setDistance(double value)](#setDistance-double-) | Gets or sets distance from text to shadow. |
| [getAngle()](#getAngle--) | Gets or sets angle for placing shadow relative to the text. |
| [setAngle(double value)](#setAngle-double-) | Gets or sets angle for placing shadow relative to the text. |
| [getColor()](#getColor--) | Gets or sets color of the shadow. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Gets or sets color of the shadow. |
| [getTransparency()](#getTransparency--) | Gets or sets transparency of the shadow. |
| [setTransparency(double value)](#setTransparency-double-) | Gets or sets transparency of the shadow. |
| [getBlur()](#getBlur--) | Gets or sets blur of the shadow. |
| [setBlur(double value)](#setBlur-double-) | Gets or sets blur of the shadow. |
### TextShadow() {#TextShadow--}
```
public TextShadow()
```


Creates TextShadow with default options.

### getDistance() {#getDistance--}
```
public final double getDistance()
```


Gets or sets distance from text to shadow. Default value is 1.

**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Gets or sets distance from text to shadow. Default value is 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


Gets or sets angle for placing shadow relative to the text. Default value is 0.

**Returns:**
double
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Gets or sets angle for placing shadow relative to the text. Default value is 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Gets or sets color of the shadow. Default value is Black.

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Gets or sets color of the shadow. Default value is Black.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Gets or sets transparency of the shadow. Default value is 0.

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Gets or sets transparency of the shadow. Default value is 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getBlur() {#getBlur--}
```
public final double getBlur()
```


Gets or sets blur of the shadow. Default value is 4.

**Returns:**
double
### setBlur(double value) {#setBlur-double-}
```
public final void setBlur(double value)
```


Gets or sets blur of the shadow. Default value is 4.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

