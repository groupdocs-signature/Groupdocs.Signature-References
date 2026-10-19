---
title: "Rahmen"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Instanz zur Speicherung von Rahmenlinien‑Eigenschaften."
type: docs
weight: 11
url: /de/java/com.groupdocs.signature.domain/border/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class Border implements ITransparency
```

Instanz zur Speicherung von Rahmenlinien‑Eigenschaften.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Border()](#Border--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getDashStyle()](#getDashStyle--) | Liest oder legt den Signaturrahmenstil fest. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | Liest oder legt den Signaturrahmenstil fest. |
|
|  | [getTransparency()](#getTransparency--) | Liest oder legt die Transparenz des Signaturrahmens fest (Wert von 0.0 (undurchsichtig) bis 1.0 (transparent)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Liest oder legt die Transparenz des Signaturrahmens fest (Wert von 0.0 (undurchsichtig) bis 1.0 (transparent)). |
|
|  | [getWeight()](#getWeight--) | Liest oder legt die Stärke des Signaturrahmens fest. |
|
|  | [setWeight(double value)](#setWeight-double-) | Liest oder legt die Stärke des Signaturrahmens fest. |
|
|  | [getColor()](#getColor--) | Liest oder legt die Rahmenfarbe der Signatur fest. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Liest oder legt die Rahmenfarbe der Signatur fest. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Liest oder legt die Rahmenfarbe der Signatur fest. |
|
|  | [getVisible()](#getVisible--) | Liest oder legt die Sichtbarkeit des Rahmens fest. |
|
| [setVisible(boolean value)](#setVisible-boolean-) |  |
|  | [deepClone()](#deepClone--) | Implementiere das IClonable-Interface |
|
### Border() {#Border--}
```
public Border()
```


### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Liest oder legt den Signaturrahmenstil fest.


**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Liest oder legt den Signaturrahmenstil fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Liest oder legt die Transparenz des Signaturrahmens fest (Wert von 0.0 (undurchsichtig) bis 1.0 (transparent)).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Liest oder legt die Transparenz des Signaturrahmens fest (Wert von 0.0 (undurchsichtig) bis 1.0 (transparent)).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getWeight() {#getWeight--}
```
public final double getWeight()
```


Liest oder legt die Stärke des Signaturrahmens fest.


**Returns:**
double
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Liest oder legt die Stärke des Signaturrahmens fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Liest oder legt die Rahmenfarbe der Signatur fest.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Liest oder legt die Rahmenfarbe der Signatur fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Liest oder legt die Rahmenfarbe der Signatur fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Liest oder legt die Sichtbarkeit des Rahmens fest.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Implementiere das IClonable-Interface


**Returns:**
java.lang.Object - Neu erstellte Border-Instanz mit denselben Eigenschaften

