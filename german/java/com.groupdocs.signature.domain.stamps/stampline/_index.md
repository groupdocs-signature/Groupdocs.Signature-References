---
title: "StampLine"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Geben Sie die Stempel-Linieneigenschaften an."
type: docs
weight: 13
url: /de/java/com.groupdocs.signature.domain.stamps/stampline/
---
**Inheritance:**
java.lang.Object
```
public class StampLine
```

Geben Sie die Stempel-Linieneigenschaften an.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [StampLine()](#StampLine--) | Erstelle StampLine mit Standardwerten. |
|
|  | [StampLine(String text)](#StampLine-java.lang.String-) | Erstelle StampLine mit Text. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getHeight()](#getHeight--) | Liest oder setzt die Zeilenhöhe auf dem Stempel. |
|
|  | [setHeight(int value)](#setHeight-int-) | Liest oder setzt die Zeilenhöhe auf dem Stempel. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Liest oder setzt die Hintergrundfarbe der Signatur. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | Liest oder setzt die Hintergrundfarbe der Signatur. |
|
|  | [setBackgroundColor(String value)](#setBackgroundColor-java.lang.String-) | Liest oder setzt die Hintergrundfarbe der Signatur. |
|
|  | [getText()](#getText--) | Liest oder setzt den Text der Stempelzeile. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Liest oder setzt den Text der Stempelzeile. |
|
|  | [getFont()](#getFont--) | Lese oder setze die Schriftart des Stempelzeilentextes. |
|
|  | [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | Lese oder setze die Schriftart des Stempelzeilentextes. |
|
|  | [getTextColor()](#getTextColor--) | Liest oder setzt die Textfarbe der Signatur. |
|
|  | [setTextColor(Color value)](#setTextColor-java.awt.Color-) | Liest oder setzt die Textfarbe der Signatur. |
|
|  | [setTextColor(String value)](#setTextColor-java.lang.String-) | Liest oder setzt die Textfarbe der Signatur. |
|
|  | [getTextBottomIntent()](#getTextBottomIntent--) | Liest oder setzt die untere Ausrichtung des Textes. |
|
|  | [setTextBottomIntent(int value)](#setTextBottomIntent-int-) | Liest oder setzt die untere Ausrichtung des Textes. |
|
|  | [getTextRepeatType()](#getTextRepeatType--) | Liest oder setzt den Textwiederholungstyp. |
|
|  | [setTextRepeatType(int value)](#setTextRepeatType-int-) | Liest oder setzt den Textwiederholungstyp. |
|
|  | [getOuterBorder()](#getOuterBorder--) | Außenrand einrichten. |
|
|  | [setOuterBorder(Border value)](#setOuterBorder-com.groupdocs.signature.domain.Border-) | Außenrand einrichten. |
|
|  | [getInnerBorder()](#getInnerBorder--) | Innenrand einrichten. |
|
|  | [setInnerBorder(Border value)](#setInnerBorder-com.groupdocs.signature.domain.Border-) | Innenrand einrichten. |
|
|  | [getVisible()](#getVisible--) | Sichtbarkeit der Stempelzeile lesen und setzen. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Sichtbarkeit der Stempelzeile lesen und setzen. |
|
### StampLine() {#StampLine--}
```
public StampLine()
```


Erstelle StampLine mit Standardwerten.


### StampLine(String text) {#StampLine-java.lang.String-}
```
public StampLine(String text)
```


Erstelle StampLine mit Text.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Text der Stempelzeile. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Liest oder setzt die Zeilenhöhe auf dem Stempel.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Liest oder setzt die Zeilenhöhe auf dem Stempel.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

### setBackgroundColor(String value) {#setBackgroundColor-java.lang.String-}
```
public final void setBackgroundColor(String value)
```


Liest oder setzt die Hintergrundfarbe der Signatur.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


Liest oder setzt den Text der Stempelzeile.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Liest oder setzt den Text der Stempelzeile.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


Lese oder setze die Schriftart des Stempelzeilentextes.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


Lese oder setze die Schriftart des Stempelzeilentextes.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getTextColor() {#getTextColor--}
```
public final Color getTextColor()
```


Liest oder setzt die Textfarbe der Signatur.


**Returns:**
java.awt.Color
### setTextColor(Color value) {#setTextColor-java.awt.Color-}
```
public final void setTextColor(Color value)
```


Liest oder setzt die Textfarbe der Signatur.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### setTextColor(String value) {#setTextColor-java.lang.String-}
```
public final void setTextColor(String value)
```


Liest oder setzt die Textfarbe der Signatur.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getTextBottomIntent() {#getTextBottomIntent--}
```
public final int getTextBottomIntent()
```


Liest oder setzt die untere Ausrichtung des Textes.


**Returns:**
int
### setTextBottomIntent(int value) {#setTextBottomIntent-int-}
```
public final void setTextBottomIntent(int value)
```


Liest oder setzt die untere Ausrichtung des Textes.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTextRepeatType() {#getTextRepeatType--}
```
public final int getTextRepeatType()
```


Liest oder setzt den Textwiederholungstyp.


**Returns:**
int
### setTextRepeatType(int value) {#setTextRepeatType-int-}
```
public final void setTextRepeatType(int value)
```


Liest oder setzt den Textwiederholungstyp.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getOuterBorder() {#getOuterBorder--}
```
public final Border getOuterBorder()
```


Außenrand einrichten.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setOuterBorder(Border value) {#setOuterBorder-com.groupdocs.signature.domain.Border-}
```
public final void setOuterBorder(Border value)
```


Außenrand einrichten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getInnerBorder() {#getInnerBorder--}
```
public final Border getInnerBorder()
```


Innenrand einrichten.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setInnerBorder(Border value) {#setInnerBorder-com.groupdocs.signature.domain.Border-}
```
public final void setInnerBorder(Border value)
```


Innenrand einrichten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Sichtbarkeit der Stempelzeile lesen und setzen.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Sichtbarkeit der Stempelzeile lesen und setzen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

