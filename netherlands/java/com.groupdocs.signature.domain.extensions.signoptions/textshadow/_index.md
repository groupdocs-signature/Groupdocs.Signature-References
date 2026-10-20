---
title: "TextShadow"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Vertegenwoordigt tekstschaduw‑eigenschappen voor tekst‑handtekeningen."
type: docs
weight: 13
url: /nl/java/com.groupdocs.signature.domain.extensions.signoptions/textshadow/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class TextShadow extends SignatureExtension
```

Vertegenwoordigt tekstschaduw‑eigenschappen voor tekst‑handtekeningen.
Het resultaat kan variëren afhankelijk van het type handtekening en het documentformaat.
TextShadow wordt aanbevolen voor gebruik met de TextAsImage-handtekening voor alle ondersteunde documenttypen,
ook met eenvoudige TextSignature en TextSignature als watermerk voor Cells (.xslx) en Slides (.pptx).
Eenvoudige TextSignature voor Words (.docx) wordt ook aanbevolen, maar heeft beperkte functionaliteit.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [TextShadow()](#TextShadow--) | Maakt TextShadow aan met standaardopties. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getDistance()](#getDistance--) | Haalt de afstand van de tekst tot de schaduw op of stelt deze in. |
|
|  | [setDistance(double value)](#setDistance-double-) | Haalt de afstand van de tekst tot de schaduw op of stelt deze in. |
|
|  | [getAngle()](#getAngle--) | Haalt de hoek voor het plaatsen van de schaduw ten opzichte van de tekst op of stelt deze in. |
|
|  | [setAngle(double value)](#setAngle-double-) | Haalt de hoek voor het plaatsen van de schaduw ten opzichte van de tekst op of stelt deze in. |
|
|  | [getColor()](#getColor--) | Haalt de kleur van de schaduw op of stelt deze in. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Haalt de kleur van de schaduw op of stelt deze in. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Haalt de kleur van de schaduw op of stelt deze in. |
|
|  | [getTransparency()](#getTransparency--) | Haalt de transparantie van de schaduw op of stelt deze in. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Haalt de transparantie van de schaduw op of stelt deze in. |
|
|  | [getBlur()](#getBlur--) | Haalt de vervaging van de schaduw op of stelt deze in. |
|
|  | [setBlur(double value)](#setBlur-double-) | Haalt de vervaging van de schaduw op of stelt deze in. |
|
### TextShadow() {#TextShadow--}
```
public TextShadow()
```


Maakt TextShadow aan met standaardopties.


### getDistance() {#getDistance--}
```
public final double getDistance()
```


Haalt de afstand van de tekst tot de schaduw op of stelt deze in.
Standaardwaarde is 1.


**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Haalt de afstand van de tekst tot de schaduw op of stelt deze in.
Standaardwaarde is 1.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


Haalt de hoek voor het plaatsen van de schaduw ten opzichte van de tekst op of stelt deze in.
Standaardwaarde is 0.


**Returns:**
double
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Haalt de hoek voor het plaatsen van de schaduw ten opzichte van de tekst op of stelt deze in.
Standaardwaarde is 0.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Haalt de kleur van de schaduw op of stelt deze in.
Standaardwaarde is Zwart.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Haalt de kleur van de schaduw op of stelt deze in.
Standaardwaarde is Zwart.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Haalt de kleur van de schaduw op of stelt deze in.
Standaardwaarde is Zwart.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Haalt de transparantie van de schaduw op of stelt deze in.
Standaardwaarde is 0.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Haalt de transparantie van de schaduw op of stelt deze in.
Standaardwaarde is 0.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### getBlur() {#getBlur--}
```
public final double getBlur()
```


Haalt de vervaging van de schaduw op of stelt deze in.
Standaardwaarde is 4.


**Returns:**
double
### setBlur(double value) {#setBlur-double-}
```
public final void setBlur(double value)
```


Haalt de vervaging van de schaduw op of stelt deze in.
Standaardwaarde is 4.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

