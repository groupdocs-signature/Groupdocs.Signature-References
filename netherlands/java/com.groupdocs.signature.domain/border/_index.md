---
title: "Border"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Instantie om randlijn-eigenschappen bij te houden."
type: docs
weight: 11
url: /nl/java/com.groupdocs.signature.domain/border/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class Border implements ITransparency
```

Instantie om randlijn-eigenschappen bij te houden.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Border()](#Border--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getDashStyle()](#getDashStyle--) | Krijgt of stelt de stijl van de handtekeningrand in. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | Krijgt of stelt de stijl van de handtekeningrand in. |
|
|  | [getTransparency()](#getTransparency--) | Krijgt of stelt de transparantie van de handtekeningrand in (waarde van 0.0 (ondoorzichtig) tot 1.0 (doorzichtig)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Krijgt of stelt de transparantie van de handtekeningrand in (waarde van 0.0 (ondoorzichtig) tot 1.0 (doorzichtig)). |
|
|  | [getWeight()](#getWeight--) | Krijgt of stelt de dikte van de handtekeningrand in. |
|
|  | [setWeight(double value)](#setWeight-double-) | Krijgt of stelt de dikte van de handtekeningrand in. |
|
|  | [getColor()](#getColor--) | Krijgt of stelt de randkleur van de handtekening in. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Krijgt of stelt de randkleur van de handtekening in. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Krijgt of stelt de randkleur van de handtekening in. |
|
|  | [getVisible()](#getVisible--) | Krijgt of stelt de zichtbaarheid van de rand in. |
|
| [setVisible(boolean value)](#setVisible-boolean-) |  |
|  | [deepClone()](#deepClone--) | Implementeer de IClonable-interface. |
|
### Border() {#Border--}
```
public Border()
```


### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Krijgt of stelt de stijl van de handtekeningrand in.


**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Krijgt of stelt de stijl van de handtekeningrand in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Krijgt of stelt de transparantie van de handtekeningrand in (waarde van 0.0 (ondoorzichtig) tot 1.0 (doorzichtig)).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Krijgt of stelt de transparantie van de handtekeningrand in (waarde van 0.0 (ondoorzichtig) tot 1.0 (doorzichtig)).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### getWeight() {#getWeight--}
```
public final double getWeight()
```


Krijgt of stelt de dikte van de handtekeningrand in.


**Returns:**
double
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Krijgt of stelt de dikte van de handtekeningrand in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Krijgt of stelt de randkleur van de handtekening in.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Krijgt of stelt de randkleur van de handtekening in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Krijgt of stelt de randkleur van de handtekening in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Krijgt of stelt de zichtbaarheid van de rand in.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Implementeer de IClonable-interface.


**Returns:**
java.lang.Object - Nieuw aangemaakte Border-instantie met dezelfde eigenschappen.

