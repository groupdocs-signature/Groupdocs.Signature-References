---
title: Background
second_title: GroupDocs.Signature for Java API Reference
description: Represents background appearance
type: docs
weight: 10
url: /java/com.groupdocs.signature.domain/background/
---
**Inheritance:**
java.lang.Object
```
public class Background
```

Represents background appearance
## Constructors

| Constructor | Description |
| --- | --- |
| [Background()](#Background--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Gets or sets the background color of signature. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Gets or sets the background color of signature. |
| [getTransparency()](#getTransparency--) | Gets or sets the background transparency (value from 0.0 (opaque) through 1.0 (clear)). |
| [setTransparency(double value)](#setTransparency-double-) | Gets or sets the background transparency (value from 0.0 (opaque) through 1.0 (clear)). |
| [getBrush()](#getBrush--) | Gets or sets the background brush. |
| [setBrush(Brush value)](#setBrush-com.groupdocs.signature.domain.extensions.Brush-) | Gets or sets the background brush. |
### Background() {#Background--}
```
public Background()
```


### getColor() {#getColor--}
```
public final Color getColor()
```


Gets or sets the background color of signature.

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Gets or sets the background color of signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Gets or sets the background transparency (value from 0.0 (opaque) through 1.0 (clear)).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Gets or sets the background transparency (value from 0.0 (opaque) through 1.0 (clear)).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Gets or sets the background brush. Value by default is null. This property expects instance of Brush objects implementations See different Brush classes

**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBrush(Brush value) {#setBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBrush(Brush value)
```


Gets or sets the background brush. Value by default is null. This property expects instance of Brush objects implementations See different Brush classes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

