---
title: "Hintergrund"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt das Hintergrund‑Erscheinungsbild dar"
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.signature.domain/background/
---
**Inheritance:**
java.lang.Object
```
public class Background
```

Stellt das Hintergrund‑Erscheinungsbild dar
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Background()](#Background--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColor()](#getColor--) | Liest oder setzt die Hintergrundfarbe der Signatur. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Liest oder setzt die Hintergrundfarbe der Signatur. |
| [setColor(String value)](#setColor-java.lang.String-) | Liest oder setzt die Hintergrundfarbe der Signatur. |
| [getTransparency()](#getTransparency--) | Liest oder setzt die Hintergrundtransparenz (Wert von 0.0 (undurchsichtig) bis 1.0 (transparent)). |
| [setTransparency(double value)](#setTransparency-double-) | Liest oder setzt die Hintergrundtransparenz (Wert von 0.0 (undurchsichtig) bis 1.0 (transparent)). |
| [getBrush()](#getBrush--) | Liest oder setzt den Hintergrundpinsel. |
| [setBrush(Brush value)](#setBrush-com.groupdocs.signature.domain.extensions.Brush-) | Liest oder setzt den Hintergrundpinsel. |
### Background() {#Background--}
```
public Background()
```


### getColor() {#getColor--}
```
public final Color getColor()
```


Liest oder setzt die Hintergrundfarbe der Signatur.

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Liest oder setzt die Hintergrundfarbe der Signatur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Liest oder setzt die Hintergrundfarbe der Signatur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Liest oder setzt die Hintergrundtransparenz (Wert von 0.0 (undurchsichtig) bis 1.0 (transparent)).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Liest oder setzt die Hintergrundtransparenz (Wert von 0.0 (undurchsichtig) bis 1.0 (transparent)).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Liest oder setzt den Hintergrundpinsel. Der Standardwert ist null. Diese Eigenschaft erwartet eine Instanz von Brush-Objektimplementierungen. Siehe verschiedene Brush-Klassen.

**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBrush(Brush value) {#setBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBrush(Brush value)
```


Liest oder setzt den Hintergrundpinsel. Der Standardwert ist null. Diese Eigenschaft erwartet eine Instanz von Brush-Objektimplementierungen. Siehe verschiedene Brush-Klassen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

