---
title: Corners
second_title: GroupDocs.Signature for Java API Reference
description: Represents corners of a square graphical object.
type: docs
weight: 10
url: /java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

Represents corners of a square graphical object.
## Constructors

| Constructor | Description |
| --- | --- |
| [Corners()](#Corners--) | Initializes a new instance of Corners class using zero values. |
| [Corners(double all)](#Corners-double-) | Initializes a new instance of the Corners class using the supplied value for all corners. |
| [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | Initializes a new instance of the Corners class using the supplied values. |
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) | Provides a Corners object with no data. |
## Methods

| Method | Description |
| --- | --- |
| [getAll()](#getAll--) | Gets or sets the value for all corners. |
| [setAll(double value)](#setAll-double-) | Gets or sets the value for all corners. |
| [getTopLeft()](#getTopLeft--) | Gets or sets top left corner value. |
| [setTopLeft(double value)](#setTopLeft-double-) | Gets or sets top left corner value. |
| [getTopRight()](#getTopRight--) | Gets or sets top right corner value. |
| [setTopRight(double value)](#setTopRight-double-) | Gets or sets top right corner value. |
| [getBottomLeft()](#getBottomLeft--) | Gets or sets bottom left corner value. |
| [setBottomLeft(double value)](#setBottomLeft-double-) | Gets or sets bottom left corner value. |
| [getBottomRight()](#getBottomRight--) | Gets or sets bottom right corner value. |
| [setBottomRight(double value)](#setBottomRight-double-) | Gets or sets bottom right corner value. |
| [deepClone()](#deepClone--) | Gets a copy of this object. |
| [equals(Object obj)](#equals-java.lang.Object-) | Override equals method |
| [hashCode()](#hashCode--) | Overrides obtaining unique hash code value |
| [toString()](#toString--) | Overrides conversion to string. |
### Corners() {#Corners--}
```
public Corners()
```


Initializes a new instance of Corners class using zero values.

### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


Initializes a new instance of the Corners class using the supplied value for all corners.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| all | double | The value to be used for padding for all corners. |

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


Initializes a new instance of the Corners class using the supplied values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| topLeft | double | Top left corner value. |
| topRight | double | Top right corner value. |
| bottomLeft | double | Bottom left corner value. |
| bottomRight | double | Bottom right corner value. |

### Empty {#Empty}
```
public static final Corners Empty
```


Provides a Corners object with no data.

### getAll() {#getAll--}
```
public final double getAll()
```


Gets or sets the value for all corners. Changing of any partial corner like top right makes this property equal 0;

**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


Gets or sets the value for all corners. Changing of any partial corner like top right makes this property equal 0;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


Gets or sets top left corner value.

**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


Gets or sets top left corner value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


Gets or sets top right corner value.

**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


Gets or sets top right corner value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


Gets or sets bottom left corner value.

**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


Gets or sets bottom left corner value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


Gets or sets bottom right corner value.

**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


Gets or sets bottom right corner value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Gets a copy of this object.

**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Override equals method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Instance to compare with. |

**Returns:**
boolean - Returns true if properties of objects are equal.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Overrides obtaining unique hash code value

**Returns:**
int - 
### toString() {#toString--}
```
public String toString()
```


Overrides conversion to string.

**Returns:**
java.lang.String - 
