---
title: "Rahmen"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Instanz zum Speichern von Randlinien‑Eigenschaften."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.signature.domain/border/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class Border implements ITransparency
```

Instanz zum Speichern von Randlinien‑Eigenschaften.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Border()](#Border--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDashStyle()](#getDashStyle--) | Liest oder setzt den Signaturrahmenstil. |
| [setDashStyle(int value)](#setDashStyle-int-) | Liest oder setzt den Signaturrahmenstil. |
| [getTransparency()](#getTransparency--) | Liest oder setzt die Signaturrahmen-Transparenz (Wert von 0.0 (undurchsichtig) bis 1.0 (transparent)). |
| [setTransparency(double value)](#setTransparency-double-) | Liest oder setzt die Signaturrahmen-Transparenz (Wert von 0.0 (undurchsichtig) bis 1.0 (transparent)). |
| [getWeight()](#getWeight--) | Liest oder setzt die Stärke des Signaturrahmens. |
| [setWeight(double value)](#setWeight-double-) | Liest oder setzt die Stärke des Signaturrahmens. |
| [getColor()](#getColor--) | Liest oder setzt die Rahmenfarbe der Signatur. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Liest oder setzt die Rahmenfarbe der Signatur. |
| [setColor(String value)](#setColor-java.lang.String-) | Liest oder setzt die Rahmenfarbe der Signatur. |
| [getVisible()](#getVisible--) | Liest oder setzt die Sichtbarkeit des Rahmens. |
| [setVisible(boolean value)](#setVisible-boolean-) |  |
| [deepClone()](#deepClone--) | Implementiert das IClonable-Interface |
### Border() {#Border--}
```
public Border()
```


### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Liest oder setzt den Signaturrahmenstil.

**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Liest oder setzt den Signaturrahmenstil.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Liest oder setzt die Signaturrahmen-Transparenz (Wert von 0.0 (undurchsichtig) bis 1.0 (transparent)).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Liest oder setzt die Signaturrahmen-Transparenz (Wert von 0.0 (undurchsichtig) bis 1.0 (transparent)).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getWeight() {#getWeight--}
```
public final double getWeight()
```


Liest oder setzt die Stärke des Signaturrahmens.

**Returns:**
double
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Liest oder setzt die Stärke des Signaturrahmens.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Liest oder setzt die Rahmenfarbe der Signatur.

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Liest oder setzt die Rahmenfarbe der Signatur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Liest oder setzt die Rahmenfarbe der Signatur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Liest oder setzt die Sichtbarkeit des Rahmens.

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


Implementiert das IClonable-Interface

**Returns:**
java.lang.Object - Neu erstellte Rahmeninstanz mit denselben Eigenschaften
