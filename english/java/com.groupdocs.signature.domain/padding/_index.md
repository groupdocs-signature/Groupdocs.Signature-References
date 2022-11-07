---
title: Padding
second_title: GroupDocs.Editor for Java API Reference
description: Represents padding or margin information associated with element.
type: docs
weight: 13
url: /java/com.groupdocs.signature.domain/padding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Padding implements Cloneable
```

Represents padding or margin information associated with element.
## Constructors

| Constructor | Description |
| --- | --- |
| [Padding()](#Padding--) | Initializes a new instance of Padding class using zero values. |
| [Padding(int all)](#Padding-int-) | Initializes a new instance of the Padding class using the supplied padding size for all edges. |
| [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | Initializes a new instance of the Padding class using the supplied padding sizes. |
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) | Provides a Padding object with no padding. |
## Methods

| Method | Description |
| --- | --- |
| [getAll()](#getAll--) | Gets or sets the padding value for all the edges. |
| [setAll(int value)](#setAll-int-) | Gets or sets the padding value for all the edges. |
| [getLeft()](#getLeft--) | Gets or sets the padding value for the left edge. |
| [setLeft(int value)](#setLeft-int-) | Gets or sets the padding value for the left edge. |
| [getRight()](#getRight--) | Gets or sets the padding value for the right edge. |
| [setRight(int value)](#setRight-int-) | Gets or sets the padding value for the right edge. |
| [getTop()](#getTop--) | Gets or sets the padding value for the top edge. |
| [setTop(int value)](#setTop-int-) | Gets or sets the padding value for the top edge. |
| [getBottom()](#getBottom--) | Gets or sets the padding value for the bottom edge. |
| [setBottom(int value)](#setBottom-int-) | Gets or sets the padding value for the bottom edge. |
| [getHorizontal()](#getHorizontal--) | Gets the combined padding for the right and left edges. |
| [getVertical()](#getVertical--) | Gets the combined padding for the top and bottom edges. |
| [deepClone()](#deepClone--) | Gets a copy of this object. |
| [toString()](#toString--) | Overrides conversion to string |
### Padding() {#Padding--}
```
public Padding()
```


Initializes a new instance of Padding class using zero values.

### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


Initializes a new instance of the Padding class using the supplied padding size for all edges.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| all | int | The number of measure units to be used for padding for all edges. |

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


Initializes a new instance of the Padding class using the supplied padding sizes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | int | The left padding size. |
| right | int | The right padding size. |
| top | int | The top padding size. |
| bottom | int | The bottom padding size. |

### Empty {#Empty}
```
public static final Padding Empty
```


Provides a Padding object with no padding.

### getAll() {#getAll--}
```
public final int getAll()
```


Gets or sets the padding value for all the edges. Changing of any partial edge like left or top makes this property equal 0;

**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


Gets or sets the padding value for all the edges. Changing of any partial edge like left or top makes this property equal 0;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Gets or sets the padding value for the left edge.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Gets or sets the padding value for the left edge.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


Gets or sets the padding value for the right edge.

**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Gets or sets the padding value for the right edge.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Gets or sets the padding value for the top edge.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Gets or sets the padding value for the top edge.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


Gets or sets the padding value for the bottom edge.

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Gets or sets the padding value for the bottom edge.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


Gets the combined padding for the right and left edges.

**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


Gets the combined padding for the top and bottom edges.

**Returns:**
int
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Gets a copy of this object.

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```


Overrides conversion to string

**Returns:**
java.lang.String - 
