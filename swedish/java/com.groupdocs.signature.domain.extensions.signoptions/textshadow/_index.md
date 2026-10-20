---
title: "TextShadow"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar textskuggningsegenskaper för textsignaturer."
type: docs
weight: 13
url: /sv/java/com.groupdocs.signature.domain.extensions.signoptions/textshadow/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class TextShadow extends SignatureExtension
```

Representerar textskuggningsegenskaper för textsignaturer.
Resultatet kan variera beroende på signaturtyp och dokumentformat.
TextShadow rekommenderas för användning med TextAsImage-signatur för alla stödda dokumenttyper,
också med enkel TextSignature och TextSignature som vattenstämpel för Cells (.xslx) och Slides (.pptx).
Enkel TextSignature för Words (.docx) rekommenderas också, men har begränsad funktionalitet.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [TextShadow()](#TextShadow--) | Skapar TextShadow med standardalternativ. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getDistance()](#getDistance--) | Hämtar eller anger avståndet från text till skugga. |
|
|  | [setDistance(double value)](#setDistance-double-) | Hämtar eller anger avståndet från text till skugga. |
|
|  | [getAngle()](#getAngle--) | Hämtar eller anger vinkeln för placering av skugga relativt texten. |
|
|  | [setAngle(double value)](#setAngle-double-) | Hämtar eller anger vinkeln för placering av skugga relativt texten. |
|
|  | [getColor()](#getColor--) | Hämtar eller anger färgen på skuggan. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Hämtar eller anger färgen på skuggan. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Hämtar eller anger färgen på skuggan. |
|
|  | [getTransparency()](#getTransparency--) | Hämtar eller anger genomskinlighet för skuggan. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Hämtar eller anger genomskinlighet för skuggan. |
|
|  | [getBlur()](#getBlur--) | Hämtar eller anger suddighet för skuggan. |
|
|  | [setBlur(double value)](#setBlur-double-) | Hämtar eller anger suddighet för skuggan. |
|
### TextShadow() {#TextShadow--}
```
public TextShadow()
```


Skapar TextShadow med standardalternativ.


### getDistance() {#getDistance--}
```
public final double getDistance()
```


Hämtar eller anger avståndet från text till skugga.
Standardvärdet är 1.


**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Hämtar eller anger avståndet från text till skugga.
Standardvärdet är 1.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


Hämtar eller anger vinkeln för placering av skugga relativt texten.
Standardvärdet är 0.


**Returns:**
double
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Hämtar eller anger vinkeln för placering av skugga relativt texten.
Standardvärdet är 0.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Hämtar eller anger färgen på skuggan.
Standardvärdet är Svart.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Hämtar eller anger färgen på skuggan.
Standardvärdet är Svart.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Hämtar eller anger färgen på skuggan.
Standardvärdet är Svart.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Hämtar eller anger genomskinlighet för skuggan.
Standardvärdet är 0.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Hämtar eller anger genomskinlighet för skuggan.
Standardvärdet är 0.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getBlur() {#getBlur--}
```
public final double getBlur()
```


Hämtar eller anger suddighet för skuggan.
Standardvärdet är 4.


**Returns:**
double
### setBlur(double value) {#setBlur-double-}
```
public final void setBlur(double value)
```


Hämtar eller anger suddighet för skuggan.
Standardvärdet är 4.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

