---
title: "TextShadow"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt die Schatteneigenschaften für Textsignaturen dar."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.signature.domain.extensions.signoptions/textshadow/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class TextShadow extends SignatureExtension
```

Stellt die Eigenschaften des Textschattens für Textsignaturen dar. Das Ergebnis kann je nach Signaturtyp und Dokumentformat variieren. TextShadow wird für die Verwendung mit TextAsImage-Signatur für alle unterstützten Dokumenttypen empfohlen, ebenso mit einfacher TextSignature und TextSignature als Wasserzeichen für Cells (.xslx) und Slides (.pptx). Eine einfache TextSignature für Words (.docx) wird ebenfalls empfohlen, hat jedoch eingeschränkte Funktionalität.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextShadow()](#TextShadow--) | Erstellt TextShadow mit Standardoptionen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDistance()](#getDistance--) | Liest oder setzt den Abstand vom Text zum Schatten. |
| [setDistance(double value)](#setDistance-double-) | Liest oder setzt den Abstand vom Text zum Schatten. |
| [getAngle()](#getAngle--) | Liest oder setzt den Winkel für die Platzierung des Schattens relativ zum Text. |
| [setAngle(double value)](#setAngle-double-) | Liest oder setzt den Winkel für die Platzierung des Schattens relativ zum Text. |
| [getColor()](#getColor--) | Liest oder setzt die Farbe des Schattens. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Liest oder setzt die Farbe des Schattens. |
| [setColor(String value)](#setColor-java.lang.String-) | Liest oder setzt die Farbe des Schattens. |
| [getTransparency()](#getTransparency--) | Liest oder setzt die Transparenz des Schattens. |
| [setTransparency(double value)](#setTransparency-double-) | Liest oder setzt die Transparenz des Schattens. |
| [getBlur()](#getBlur--) | Liest oder setzt die Unschärfe des Schattens. |
| [setBlur(double value)](#setBlur-double-) | Liest oder setzt die Unschärfe des Schattens. |
### TextShadow() {#TextShadow--}
```
public TextShadow()
```


Erstellt TextShadow mit Standardoptionen.

### getDistance() {#getDistance--}
```
public final double getDistance()
```


Liest oder setzt den Abstand vom Text zum Schatten. Standardwert ist 1.

**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Liest oder setzt den Abstand vom Text zum Schatten. Standardwert ist 1.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


Liest oder setzt den Winkel für die Platzierung des Schattens relativ zum Text. Standardwert ist 0.

**Returns:**
double
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Liest oder setzt den Winkel für die Platzierung des Schattens relativ zum Text. Standardwert ist 0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Liest oder setzt die Farbe des Schattens. Standardwert ist Schwarz.

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Liest oder setzt die Farbe des Schattens. Standardwert ist Schwarz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Liest oder setzt die Farbe des Schattens. Standardwert ist Schwarz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Liest oder setzt die Transparenz des Schattens. Standardwert ist 0.

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Liest oder setzt die Transparenz des Schattens. Standardwert ist 0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getBlur() {#getBlur--}
```
public final double getBlur()
```


Liest oder setzt die Unschärfe des Schattens. Standardwert ist 4.

**Returns:**
double
### setBlur(double value) {#setBlur-double-}
```
public final void setBlur(double value)
```


Liest oder setzt die Unschärfe des Schattens. Standardwert ist 4.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

