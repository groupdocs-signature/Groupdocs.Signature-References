---
title: "StampSignOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt die Stempel-Signaturoptionen dar."
type: docs
weight: 17
url: /de/java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

Stellt die Stempel-Signaturoptionen dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [StampSignOptions()](#StampSignOptions--) | Initialisiert eine neue Instanz der Klasse StampSignOptions mit Standardwerten. |
|
|  | [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | Initialisiert eine neue Instanz der Klasse StampSignOptions mit Ausrichtungsoptionen. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getStampType()](#getStampType--) | Liest oder setzt den Stempeltyp. |
|
|  | [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | Liest oder setzt den Stempeltyp. |
|
|  | [getOuterLines()](#getOuterLines--) | Liste der äußeren Linien, die als konzentrische Kreise dargestellt werden. |
|
|  | [getInnerLines()](#getInnerLines--) | Liste der inneren Linien, die als Satz von Rechtecken dargestellt werden. |
|
|  | [getBackground()](#getBackground--) | Liest oder setzt den Stempel‑Hintergrund. |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Liest oder setzt den Stempel‑Hintergrund. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Liest oder setzt die Hintergrundfarbe der Signatur. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | Liest oder setzt die Hintergrundfarbe der Signatur. |
|
|  | [getBackgroundBrush()](#getBackgroundBrush--) | Liest oder setzt den Hintergrund‑Pinsel der Signatur. |
|
|  | [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | Liest oder setzt den Hintergrund‑Pinsel der Signatur. |
|
|  | [getBackgroundColorCropType()](#getBackgroundColorCropType--) | Liest oder setzt den Zuschnitttyp der Hintergrundfarbe der Signatur. |
|
|  | [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | Liest oder setzt den Zuschnitttyp der Hintergrundfarbe der Signatur. |
|
|  | [getBackgroundImageCropType()](#getBackgroundImageCropType--) | Liest oder setzt den Zuschnitttyp des Hintergrundbildes der Signatur. |
|
|  | [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | Liest oder setzt den Zuschnitttyp des Hintergrundbildes der Signatur. |
|
|  | [toString()](#toString--) | Überschreibe die String-Konvertierung |
|
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


Initialisiert eine neue Instanz der Klasse StampSignOptions mit Standardwerten.


### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


Initialisiert eine neue Instanz der Klasse StampSignOptions mit Ausrichtungsoptionen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | links | int | Die x‑Koordinate der linken oberen Kante der Stempel‑Signatur. |
|
|  | oben | int | Die y‑Koordinate der linken oberen Kante der Stempel‑Signatur |
|
|  | Breite | int | Die Breite der Stempel‑Signatur |
|
|  | Höhe | int | Die Höhe der Stempel‑Signatur |
|

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


Liest oder setzt den Stempeltyp.
Der Standardwert ist Rund.


**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


Liest oder setzt den Stempeltyp.
Der Standardwert ist Rund.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


Liste der äußeren Linien, die als konzentrische Kreise dargestellt werden.


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


Liste der inneren Linien, die als Satz von Rechtecken dargestellt werden.


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Liest oder setzt den Stempel‑Hintergrund.


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Liest oder setzt den Stempel‑Hintergrund.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Liest oder setzt die Hintergrundfarbe der Signatur.


**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


Liest oder setzt die Hintergrundfarbe der Signatur.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


Liest oder setzt den Hintergrundpinsel der Signatur. Der Standardwert ist null.


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


Liest oder setzt den Hintergrundpinsel der Signatur. Der Standardwert ist null.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


Liest oder setzt den Zuschnitttyp der Hintergrundfarbe der Signatur.


**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


Liest oder setzt den Zuschnitttyp der Hintergrundfarbe der Signatur.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


Liest oder setzt den Zuschnitttyp des Hintergrundbildes der Signatur.


**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


Liest oder setzt den Zuschnitttyp des Hintergrundbildes der Signatur.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### toString() {#toString--}
```
public String toString()
```


Überschreibe die String-Konvertierung


**Returns:**
java.lang.String -
