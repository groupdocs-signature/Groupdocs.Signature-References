---
title: "Hoeken"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Stelt de hoeken van een vierkant grafisch object voor."
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

Stelt de hoeken van een vierkant grafisch object voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Corners()](#Corners--) | Initialiseert een nieuw exemplaar van de klasse Corners met nulwaarden. |
|
|  | [Corners(double all)](#Corners-double-) | Initialiseert een nieuw exemplaar van de klasse Corners met de opgegeven waarde voor alle hoeken. |
|
|  | [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | Initialiseert een nieuw exemplaar van de klasse Corners met de opgegeven waarden. |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Empty](#Empty) | Levert een Corners-object zonder gegevens. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getAll()](#getAll--) | Krijgt of stelt de waarde voor alle hoeken in. |
|
|  | [setAll(double value)](#setAll-double-) | Krijgt of stelt de waarde voor alle hoeken in. |
|
|  | [getTopLeft()](#getTopLeft--) | Krijgt of stelt de waarde van de linkerbovenhoek in. |
|
|  | [setTopLeft(double value)](#setTopLeft-double-) | Krijgt of stelt de waarde van de linkerbovenhoek in. |
|
|  | [getTopRight()](#getTopRight--) | Krijgt of stelt de waarde van de rechterbovenhoek in. |
|
|  | [setTopRight(double value)](#setTopRight-double-) | Krijgt of stelt de waarde van de rechterbovenhoek in. |
|
|  | [getBottomLeft()](#getBottomLeft--) | Krijgt of stelt de waarde van de linksonderhoek in. |
|
|  | [setBottomLeft(double value)](#setBottomLeft-double-) | Krijgt of stelt de waarde van de linksonderhoek in. |
|
|  | [getBottomRight()](#getBottomRight--) | Krijgt of stelt de waarde van de rechtsonderhoek in. |
|
|  | [setBottomRight(double value)](#setBottomRight-double-) | Krijgt of stelt de waarde van de rechtsonderhoek in. |
|
|  | [deepClone()](#deepClone--) | Krijgt een kopie van dit object. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Overschrijf equals-methode |
|
|  | [hashCode()](#hashCode--) | Overschrijft het verkrijgen van een unieke hashcode-waarde |
|
|  | [toString()](#toString--) | Overschrijft conversie naar string. |
|
### Corners() {#Corners--}
```
public Corners()
```


Initialiseert een nieuw exemplaar van de klasse Corners met nulwaarden.


### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


Initialiseert een nieuw exemplaar van de klasse Corners met de opgegeven waarde voor alle hoeken.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | alle | double | De waarde die moet worden gebruikt voor opvulling van alle hoeken. |
|

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


Initialiseert een nieuw exemplaar van de klasse Corners met de opgegeven waarden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | topLeft | double | Waarde van de linkerbovenhoek. |
|
|  | topRight | double | Waarde van de rechterbovenhoek. |
|
|  | bottomLeft | double | Waarde van de linkerbenedenhoek. |
|
|  | bottomRight | double | Waarde van de rechterbenedenhoek. |
|

### Empty {#Empty}
```
public static final Corners Empty
```


Levert een Corners-object zonder gegevens.


### getAll() {#getAll--}
```
public final double getAll()
```


Krijgt of stelt de waarde voor alle hoeken in.
Het wijzigen van een willekeurige deelhoek, zoals rechtsboven, maakt deze eigenschap gelijk aan 0;


**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


Krijgt of stelt de waarde voor alle hoeken in.
Het wijzigen van een willekeurige deelhoek, zoals rechtsboven, maakt deze eigenschap gelijk aan 0;


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


Krijgt of stelt de waarde van de linkerbovenhoek in.


**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


Krijgt of stelt de waarde van de linkerbovenhoek in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


Krijgt of stelt de waarde van de rechterbovenhoek in.


**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


Krijgt of stelt de waarde van de rechterbovenhoek in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


Krijgt of stelt de waarde van de linksonderhoek in.


**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


Krijgt of stelt de waarde van de linksonderhoek in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


Krijgt of stelt de waarde van de rechtsonderhoek in.


**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


Krijgt of stelt de waarde van de rechtsonderhoek in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Krijgt een kopie van dit object.


**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Overschrijf equals-methode


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | obj | java.lang.Object | Instantie om mee te vergelijken. |
|

**Returns:**
boolean - Retourneert true als de eigenschappen van objecten gelijk zijn.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Overschrijft het verkrijgen van een unieke hashcode-waarde


**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


Overschrijft conversie naar string.


**Returns:**
java.lang.String -
