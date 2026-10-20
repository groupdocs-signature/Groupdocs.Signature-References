---
title: "Achtergrond"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Geeft weer achtergrondweergave"
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature.domain/background/
---
**Inheritance:**
java.lang.Object
```
public class Background
```

Geeft weer achtergrondweergave

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Background()](#Background--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getColor()](#getColor--) | Haalt op of stelt de achtergrondkleur van de handtekening in. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Haalt op of stelt de achtergrondkleur van de handtekening in. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Haalt op of stelt de achtergrondkleur van de handtekening in. |
|
|  | [getTransparency()](#getTransparency--) | Haalt de achtergrondtransparantie op of stelt deze in (waarde van 0.0 (ondoorzichtig) tot 1.0 (doorzichtig)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Haalt de achtergrondtransparantie op of stelt deze in (waarde van 0.0 (ondoorzichtig) tot 1.0 (doorzichtig)). |
|
|  | [getBrush()](#getBrush--) | Krijgt of stelt de achtergrondkwast in. |
|
|  | [setBrush(Brush value)](#setBrush-com.groupdocs.signature.domain.extensions.Brush-) | Krijgt of stelt de achtergrondkwast in. |
|
### Background() {#Background--}
```
public Background()
```


### getColor() {#getColor--}
```
public final Color getColor()
```


Haalt op of stelt de achtergrondkleur van de handtekening in.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Haalt op of stelt de achtergrondkleur van de handtekening in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Haalt op of stelt de achtergrondkleur van de handtekening in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Haalt de achtergrondtransparantie op of stelt deze in (waarde van 0.0 (ondoorzichtig) tot 1.0 (doorzichtig)).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Haalt de achtergrondtransparantie op of stelt deze in (waarde van 0.0 (ondoorzichtig) tot 1.0 (doorzichtig)).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Krijgt of stelt de achtergrondkwast in. Standaardwaarde is null.
Deze eigenschap verwacht een instantie van Brush-objectimplementaties.
Zie verschillende Brush-klassen.


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBrush(Brush value) {#setBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBrush(Brush value)
```


Krijgt of stelt de achtergrondkwast in. Standaardwaarde is null.
Deze eigenschap verwacht een instantie van Brush-objectimplementaties.
Zie verschillende Brush-klassen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

