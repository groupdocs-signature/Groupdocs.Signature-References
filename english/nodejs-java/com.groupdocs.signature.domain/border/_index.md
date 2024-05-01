---
title: Border
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Instance to keep Border line properties.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.signature.domain/border/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class Border implements ITransparency
```

Instance to keep Border line properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [Border()](#Border--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getDashStyle()](#getDashStyle--) | Gets or sets the signature border style. |
| [setDashStyle(int value)](#setDashStyle-int-) | Gets or sets the signature border style. |
| [getTransparency()](#getTransparency--) | Gets or sets the signature border transparency (value from 0.0 (opaque) through 1.0 (clear)). |
| [setTransparency(double value)](#setTransparency-double-) | Gets or sets the signature border transparency (value from 0.0 (opaque) through 1.0 (clear)). |
| [getWeight()](#getWeight--) | Gets or sets the weight of the signature border. |
| [setWeight(double value)](#setWeight-double-) | Gets or sets the weight of the signature border. |
| [getColor()](#getColor--) | Gets or sets the border color of signature. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Gets or sets the border color of signature. |
| [setColor(String value)](#setColor-java.lang.String-) | Gets or sets the border color of signature. |
| [getVisible()](#getVisible--) | Gets or sets the border visibility. |
| [setVisible(boolean value)](#setVisible-boolean-) |  |
| [deepClone()](#deepClone--) | Implement IClonable interface |
### Border() {#Border--}
```
public Border()
```


### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Gets or sets the signature border style.

**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Gets or sets the signature border style.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Gets or sets the signature border transparency (value from 0.0 (opaque) through 1.0 (clear)).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Gets or sets the signature border transparency (value from 0.0 (opaque) through 1.0 (clear)).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getWeight() {#getWeight--}
```
public final double getWeight()
```


Gets or sets the weight of the signature border.

**Returns:**
double
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Gets or sets the weight of the signature border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Gets or sets the border color of signature.

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Gets or sets the border color of signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Gets or sets the border color of signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Gets or sets the border visibility.

**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Implement IClonable interface

**Returns:**
java.lang.Object - Newly created Border instance with same properties
