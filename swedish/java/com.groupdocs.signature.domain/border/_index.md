---
title: "Kant"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Instans för att behålla kantlinjens egenskaper."
type: docs
weight: 11
url: /sv/java/com.groupdocs.signature.domain/border/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class Border implements ITransparency
```

Instans för att behålla kantlinjens egenskaper.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Border()](#Border--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getDashStyle()](#getDashStyle--) | Hämtar eller anger signaturens kantstil. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | Hämtar eller anger signaturens kantstil. |
|
|  | [getTransparency()](#getTransparency--) | Hämtar eller anger signaturens kanttransparens (värde från 0.0 (opak) till 1.0 (klar)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Hämtar eller anger signaturens kanttransparens (värde från 0.0 (opak) till 1.0 (klar)). |
|
|  | [getWeight()](#getWeight--) | Hämtar eller anger tjockleken på signaturens kant. |
|
|  | [setWeight(double value)](#setWeight-double-) | Hämtar eller anger tjockleken på signaturens kant. |
|
|  | [getColor()](#getColor--) | Hämtar eller anger kantfärgen på signaturen. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Hämtar eller anger kantfärgen på signaturen. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Hämtar eller anger kantfärgen på signaturen. |
|
|  | [getVisible()](#getVisible--) | Hämtar eller anger kantens synlighet. |
|
| [setVisible(boolean value)](#setVisible-boolean-) |  |
|  | [deepClone()](#deepClone--) | Implementera IClonable-gränssnittet. |
|
### Border() {#Border--}
```
public Border()
```


### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Hämtar eller anger signaturens kantstil.


**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Hämtar eller anger signaturens kantstil.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Hämtar eller anger signaturens kanttransparens (värde från 0.0 (opak) till 1.0 (klar)).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Hämtar eller anger signaturens kanttransparens (värde från 0.0 (opak) till 1.0 (klar)).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getWeight() {#getWeight--}
```
public final double getWeight()
```


Hämtar eller anger tjockleken på signaturens kant.


**Returns:**
double
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Hämtar eller anger tjockleken på signaturens kant.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Hämtar eller anger kantfärgen på signaturen.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Hämtar eller anger kantfärgen på signaturen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Hämtar eller anger kantfärgen på signaturen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Hämtar eller anger kantens synlighet.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Implementera IClonable-gränssnittet.


**Returns:**
java.lang.Object - Nytt Border-objekt skapat med samma egenskaper

