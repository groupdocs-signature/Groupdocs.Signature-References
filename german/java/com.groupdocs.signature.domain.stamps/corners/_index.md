---
title: "Ecken"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt die Ecken eines quadratischen grafischen Objekts dar."
type: docs
weight: 10
url: /de/java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

Stellt die Ecken eines quadratischen grafischen Objekts dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Corners()](#Corners--) | Initialisiert eine neue Instanz der Klasse Corners mit Nullwerten. |
|
|  | [Corners(double all)](#Corners-double-) | Initialisiert eine neue Instanz der Klasse Corners mit dem angegebenen Wert für alle Ecken. |
|
|  | [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | Initialisiert eine neue Instanz der Klasse Corners mit den angegebenen Werten. |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Empty](#Empty) | Stellt ein Corners-Objekt ohne Daten bereit. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getAll()](#getAll--) | Liest oder setzt den Wert für alle Ecken. |
|
|  | [setAll(double value)](#setAll-double-) | Liest oder setzt den Wert für alle Ecken. |
|
|  | [getTopLeft()](#getTopLeft--) | Liest oder setzt den Wert der oberen linken Ecke. |
|
|  | [setTopLeft(double value)](#setTopLeft-double-) | Liest oder setzt den Wert der oberen linken Ecke. |
|
|  | [getTopRight()](#getTopRight--) | Liest oder setzt den Wert der oberen rechten Ecke. |
|
|  | [setTopRight(double value)](#setTopRight-double-) | Liest oder setzt den Wert der oberen rechten Ecke. |
|
|  | [getBottomLeft()](#getBottomLeft--) | Liest oder setzt den Wert der unteren linken Ecke. |
|
|  | [setBottomLeft(double value)](#setBottomLeft-double-) | Liest oder setzt den Wert der unteren linken Ecke. |
|
|  | [getBottomRight()](#getBottomRight--) | Liest oder setzt den Wert der unteren rechten Ecke. |
|
|  | [setBottomRight(double value)](#setBottomRight-double-) | Liest oder setzt den Wert der unteren rechten Ecke. |
|
|  | [deepClone()](#deepClone--) | Liest eine Kopie dieses Objekts. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Equals-Methode überschreiben |
|
|  | [hashCode()](#hashCode--) | Überschreibt das Erhalten eines eindeutigen Hashcode-Werts |
|
|  | [toString()](#toString--) | Überschreibt die Konvertierung in einen String. |
|
### Corners() {#Corners--}
```
public Corners()
```


Initialisiert eine neue Instanz der Klasse Corners mit Nullwerten.


### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


Initialisiert eine neue Instanz der Klasse Corners mit dem angegebenen Wert für alle Ecken.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | alle | double | Der Wert, der für das Padding aller Ecken verwendet wird. |
|

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


Initialisiert eine neue Instanz der Klasse Corners mit den angegebenen Werten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | topLeft | double | Wert der oberen linken Ecke. |
|
|  | topRight | double | Wert der oberen rechten Ecke. |
|
|  | bottomLeft | double | Wert der unteren linken Ecke. |
|
|  | bottomRight | double | Wert der unteren rechten Ecke. |
|

### Empty {#Empty}
```
public static final Corners Empty
```


Stellt ein Corners-Objekt ohne Daten bereit.


### getAll() {#getAll--}
```
public final double getAll()
```


Liest oder setzt den Wert für alle Ecken.
Das Ändern einer beliebigen Teil-Ecke wie oben rechts setzt diese Eigenschaft auf 0;


**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


Liest oder setzt den Wert für alle Ecken.
Das Ändern einer beliebigen Teil-Ecke wie oben rechts setzt diese Eigenschaft auf 0;


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


Liest oder setzt den Wert der oberen linken Ecke.


**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


Liest oder setzt den Wert der oberen linken Ecke.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


Liest oder setzt den Wert der oberen rechten Ecke.


**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


Liest oder setzt den Wert der oberen rechten Ecke.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


Liest oder setzt den Wert der unteren linken Ecke.


**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


Liest oder setzt den Wert der unteren linken Ecke.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


Liest oder setzt den Wert der unteren rechten Ecke.


**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


Liest oder setzt den Wert der unteren rechten Ecke.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Liest eine Kopie dieses Objekts.


**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Equals-Methode überschreiben


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Instanz zum Vergleichen mit. |
|

**Returns:**
boolean - Gibt true zurück, wenn die Eigenschaften von Objekten gleich sind.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Überschreibt das Erhalten eines eindeutigen Hashcode-Werts


**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


Überschreibt die Konvertierung in einen String.


**Returns:**
java.lang.String -
