---
title: "Padding"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Geeft weer opvul- of marge-informatie die aan een element is gekoppeld."
type: docs
weight: 13
url: /nl/java/com.groupdocs.signature.domain/padding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Padding implements Cloneable
```

Geeft weer opvul- of marge-informatie die aan een element is gekoppeld.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Padding()](#Padding--) | Initialiseert een nieuw exemplaar van de Padding-klasse met nulwaarden. |
|
|  | [Padding(int all)](#Padding-int-) | Initialiseert een nieuw exemplaar van de Padding-klasse met de opgegeven paddinggrootte voor alle randen. |
|
|  | [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | Initialiseert een nieuw exemplaar van de Padding-klasse met de opgegeven paddinggroottes. |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Empty](#Empty) | Levert een Padding-object zonder padding. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getAll()](#getAll--) | Haalt op of stelt de paddingwaarde in voor alle randen. |
|
|  | [setAll(int value)](#setAll-int-) | Haalt op of stelt de paddingwaarde in voor alle randen. |
|
|  | [getLeft()](#getLeft--) | Haalt op of stelt de paddingwaarde in voor de linkerrand. |
|
|  | [setLeft(int value)](#setLeft-int-) | Haalt op of stelt de paddingwaarde in voor de linkerrand. |
|
|  | [getRight()](#getRight--) | Haalt op of stelt de paddingwaarde in voor de rechterrand. |
|
|  | [setRight(int value)](#setRight-int-) | Haalt op of stelt de paddingwaarde in voor de rechterrand. |
|
|  | [getTop()](#getTop--) | Haalt op of stelt de paddingwaarde in voor de bovenrand. |
|
|  | [setTop(int value)](#setTop-int-) | Haalt op of stelt de paddingwaarde in voor de bovenrand. |
|
|  | [getBottom()](#getBottom--) | Haalt op of stelt de paddingwaarde in voor de onderrand. |
|
|  | [setBottom(int value)](#setBottom-int-) | Haalt op of stelt de paddingwaarde in voor de onderrand. |
|
|  | [getHorizontal()](#getHorizontal--) | Haalt de gecombineerde padding op voor de rechter- en linkerrand. |
|
|  | [getVertical()](#getVertical--) | Haalt de gecombineerde padding op voor de boven- en onderrand. |
|
|  | [deepClone()](#deepClone--) | Krijgt een kopie van dit object. |
|
|  | [toString()](#toString--) | Overschrijft conversie naar string |
|
### Padding() {#Padding--}
```
public Padding()
```


Initialiseert een nieuw exemplaar van de Padding-klasse met nulwaarden.


### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


Initialiseert een nieuw exemplaar van de Padding-klasse met de opgegeven paddinggrootte voor alle randen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | alle | int | Het aantal meeteenheden dat moet worden gebruikt voor padding voor alle randen. |
|

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


Initialiseert een nieuw exemplaar van de Padding-klasse met de opgegeven paddinggroottes.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | links | int | De linkerpaddingsgrootte. |
|
|  | rechts | int | De rechterpaddingsgrootte. |
|
|  | boven | int | De bovenpaddingsgrootte. |
|
|  | onderkant | int | De grootte van de onderkantvulling. |
|

### Empty {#Empty}
```
public static final Padding Empty
```


Levert een Padding-object zonder padding.


### getAll() {#getAll--}
```
public final int getAll()
```


Haalt op of stelt de paddingwaarde in voor alle randen.
Het wijzigen van een willekeurige deelrand, zoals links of boven, maakt deze eigenschap gelijk aan 0;


**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


Haalt op of stelt de paddingwaarde in voor alle randen.
Het wijzigen van een willekeurige deelrand, zoals links of boven, maakt deze eigenschap gelijk aan 0;


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Haalt op of stelt de paddingwaarde in voor de linkerrand.


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Haalt op of stelt de paddingwaarde in voor de linkerrand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


Haalt op of stelt de paddingwaarde in voor de rechterrand.


**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Haalt op of stelt de paddingwaarde in voor de rechterrand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Haalt op of stelt de paddingwaarde in voor de bovenrand.


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Haalt op of stelt de paddingwaarde in voor de bovenrand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


Haalt op of stelt de paddingwaarde in voor de onderrand.


**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Haalt op of stelt de paddingwaarde in voor de onderrand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


Haalt de gecombineerde padding op voor de rechter- en linkerrand.


**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


Haalt de gecombineerde padding op voor de boven- en onderrand.


**Returns:**
int
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Krijgt een kopie van dit object.


**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```


Overschrijft conversie naar string


**Returns:**
java.lang.String -
