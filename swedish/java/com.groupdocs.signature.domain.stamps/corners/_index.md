---
title: "Hörn"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar hörnen på ett fyrkantigt grafiskt objekt."
type: docs
weight: 10
url: /sv/java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

Representerar hörnen på ett fyrkantigt grafiskt objekt.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [Corners()](#Corners--) | Initierar en ny instans av Corners-klassen med nollvärden. |
|
|  | [Corners(double all)](#Corners-double-) | Initierar en ny instans av Corners-klassen med det angivna värdet för alla hörn. |
|
|  | [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | Initierar en ny instans av Corners-klassen med de angivna värdena. |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Empty](#Empty) | Tillhandahåller ett Corners-objekt utan data. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getAll()](#getAll--) | Hämtar eller anger värdet för alla hörn. |
|
|  | [setAll(double value)](#setAll-double-) | Hämtar eller anger värdet för alla hörn. |
|
|  | [getTopLeft()](#getTopLeft--) | Hämtar eller anger värdet för övre vänstra hörnet. |
|
|  | [setTopLeft(double value)](#setTopLeft-double-) | Hämtar eller anger värdet för övre vänstra hörnet. |
|
|  | [getTopRight()](#getTopRight--) | Hämtar eller anger värdet för övre högra hörnet. |
|
|  | [setTopRight(double value)](#setTopRight-double-) | Hämtar eller anger värdet för övre högra hörnet. |
|
|  | [getBottomLeft()](#getBottomLeft--) | Hämtar eller anger värdet för nedre vänstra hörnet. |
|
|  | [setBottomLeft(double value)](#setBottomLeft-double-) | Hämtar eller anger värdet för nedre vänstra hörnet. |
|
|  | [getBottomRight()](#getBottomRight--) | Hämtar eller anger värdet för nedre högra hörnet. |
|
|  | [setBottomRight(double value)](#setBottomRight-double-) | Hämtar eller anger värdet för nedre högra hörnet. |
|
|  | [deepClone()](#deepClone--) | Hämtar en kopia av detta objekt. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Åsidosätt equals-metoden |
|
|  | [hashCode()](#hashCode--) | Åsidosätter hämtning av unikt hashkodsvärde |
|
|  | [toString()](#toString--) | Åsidosätter konvertering till sträng. |
|
### Corners() {#Corners--}
```
public Corners()
```


Initierar en ny instans av Corners-klassen med nollvärden.


### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


Initierar en ny instans av Corners-klassen med det angivna värdet för alla hörn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | alla | double | Värdet som ska användas för utfyllnad för alla hörn. |
|

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


Initierar en ny instans av Corners-klassen med de angivna värdena.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | topLeft | double | Värde för övre vänstra hörnet. |
|
|  | topRight | double | Värde för övre högra hörnet. |
|
|  | bottomLeft | double | Värde för nedre vänstra hörnet. |
|
|  | bottomRight | double | Värde för nedre högra hörnet. |
|

### Empty {#Empty}
```
public static final Corners Empty
```


Tillhandahåller ett Corners-objekt utan data.


### getAll() {#getAll--}
```
public final double getAll()
```


Hämtar eller anger värdet för alla hörn.
Att ändra någon del av hörnet, som övre högra, gör att denna egenskap blir 0;


**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


Hämtar eller anger värdet för alla hörn.
Att ändra någon del av hörnet, som övre högra, gör att denna egenskap blir 0;


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


Hämtar eller anger värdet för övre vänstra hörnet.


**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


Hämtar eller anger värdet för övre vänstra hörnet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


Hämtar eller anger värdet för övre högra hörnet.


**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


Hämtar eller anger värdet för övre högra hörnet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


Hämtar eller anger värdet för nedre vänstra hörnet.


**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


Hämtar eller anger värdet för nedre vänstra hörnet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


Hämtar eller anger värdet för nedre högra hörnet.


**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


Hämtar eller anger värdet för nedre högra hörnet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Hämtar en kopia av detta objekt.


**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Åsidosätt equals-metoden


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Instans att jämföra med. |
|

**Returns:**
boolean - Returnerar true om objektens egenskaper är lika.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Åsidosätter hämtning av unikt hashkodsvärde


**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


Åsidosätter konvertering till sträng.


**Returns:**
java.lang.String -
