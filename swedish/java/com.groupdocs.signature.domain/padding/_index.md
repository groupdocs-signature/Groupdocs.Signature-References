---
title: "Fyllnad"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar utfyllnads‑ eller marginalinformation som är associerad med elementet."
type: docs
weight: 13
url: /sv/java/com.groupdocs.signature.domain/padding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Padding implements Cloneable
```

Representerar utfyllnads‑ eller marginalinformation som är associerad med elementet.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [Padding()](#Padding--) | Initierar en ny instans av Padding-klassen med nollvärden. |
|
|  | [Padding(int all)](#Padding-int-) | Initierar en ny instans av Padding-klassen med den angivna fyllnadsstorleken för alla kanter. |
|
|  | [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | Initierar en ny instans av Padding-klassen med de angivna fyllnadsstorlekarna. |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Empty](#Empty) | Tillhandahåller ett Padding-objekt utan fyllnad. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getAll()](#getAll--) | Hämtar eller anger fyllnadsvärdet för alla kanter. |
|
|  | [setAll(int value)](#setAll-int-) | Hämtar eller anger fyllnadsvärdet för alla kanter. |
|
|  | [getLeft()](#getLeft--) | Hämtar eller anger fyllnadsvärdet för vänster kant. |
|
|  | [setLeft(int value)](#setLeft-int-) | Hämtar eller anger fyllnadsvärdet för vänster kant. |
|
|  | [getRight()](#getRight--) | Hämtar eller anger fyllnadsvärdet för höger kant. |
|
|  | [setRight(int value)](#setRight-int-) | Hämtar eller anger fyllnadsvärdet för höger kant. |
|
|  | [getTop()](#getTop--) | Hämtar eller anger fyllnadsvärdet för övre kant. |
|
|  | [setTop(int value)](#setTop-int-) | Hämtar eller anger fyllnadsvärdet för övre kant. |
|
|  | [getBottom()](#getBottom--) | Hämtar eller anger fyllnadsvärdet för nedre kant. |
|
|  | [setBottom(int value)](#setBottom-int-) | Hämtar eller anger fyllnadsvärdet för nedre kant. |
|
|  | [getHorizontal()](#getHorizontal--) | Hämtar den kombinerade fyllnaden för höger och vänster kant. |
|
|  | [getVertical()](#getVertical--) | Hämtar den kombinerade fyllnaden för övre och nedre kant. |
|
|  | [deepClone()](#deepClone--) | Hämtar en kopia av detta objekt. |
|
|  | [toString()](#toString--) | Åsidosätter konvertering till sträng |
|
### Padding() {#Padding--}
```
public Padding()
```


Initierar en ny instans av Padding-klassen med nollvärden.


### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


Initierar en ny instans av Padding-klassen med den angivna fyllnadsstorleken för alla kanter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | alla | int | Antalet måttenheter som ska användas för fyllnad för alla kanter. |
|

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


Initierar en ny instans av Padding-klassen med de angivna fyllnadsstorlekarna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | vänster | int | Den vänstra fyllnadsstorleken. |
|
|  | höger | int | Den högra utfyllnadsstorleken. |
|
|  | övre | int | Den övre utfyllnadsstorleken. |
|
|  | nedre | int | Den nedre utfyllnadsstorleken. |
|

### Empty {#Empty}
```
public static final Padding Empty
```


Tillhandahåller ett Padding-objekt utan fyllnad.


### getAll() {#getAll--}
```
public final int getAll()
```


Hämtar eller anger fyllnadsvärdet för alla kanter.
Ändring av någon delkant som vänster eller topp gör att denna egenskap blir 0;


**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


Hämtar eller anger fyllnadsvärdet för alla kanter.
Ändring av någon delkant som vänster eller topp gör att denna egenskap blir 0;


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Hämtar eller anger fyllnadsvärdet för vänster kant.


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Hämtar eller anger fyllnadsvärdet för vänster kant.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


Hämtar eller anger fyllnadsvärdet för höger kant.


**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Hämtar eller anger fyllnadsvärdet för höger kant.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Hämtar eller anger fyllnadsvärdet för övre kant.


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Hämtar eller anger fyllnadsvärdet för övre kant.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


Hämtar eller anger fyllnadsvärdet för nedre kant.


**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Hämtar eller anger fyllnadsvärdet för nedre kant.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


Hämtar den kombinerade fyllnaden för höger och vänster kant.


**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


Hämtar den kombinerade fyllnaden för övre och nedre kant.


**Returns:**
int
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Hämtar en kopia av detta objekt.


**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```


Åsidosätter konvertering till sträng


**Returns:**
java.lang.String -
