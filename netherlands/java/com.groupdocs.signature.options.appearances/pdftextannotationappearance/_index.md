---
title: "PdfTextAnnotationAppearance"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Beschrijft het uiterlijk van het PDF‑tekstannotatie‑object Title Subject Content."
type: docs
weight: 13
url: /nl/java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

Beschrijft de weergave van een PDF‑tekstannotatie‑object (Titel, Onderwerp, Inhoud).

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | Maakt PDF‑handtekening‑txt‑annotatie‑uiterlijk‑object. |
|
|  | [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | Maakt PDF‑handtekening‑txt‑annotatie met opgegeven waarden (title, subject, contents). |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getContents()](#getContents--) | Haalt op of stelt de inhoud van het annotatie‑object in. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | Haalt op of stelt de inhoud van het annotatie‑object in. |
|
|  | [getSubject()](#getSubject--) | Haalt op of stelt Subject in, die de beschrijving van het object weergeeft. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Haalt op of stelt Subject in, die de beschrijving van het object weergeeft. |
|
|  | [getTitle()](#getTitle--) | Haalt op of stelt een Title in die wordt weergegeven in de titelbalk van het annotatie‑object. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Haalt op of stelt een Title in die wordt weergegeven in de titelbalk van het annotatie‑object. |
|
|  | [getBorder()](#getBorder--) | Haalt op of stelt verschillende randinstellingen in |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Haalt op of stelt verschillende randinstellingen in |
|
|  | [getBorderEffect()](#getBorderEffect--) | Haalt op of stelt rand‑effect in. |
|
|  | [setBorderEffect(int value)](#setBorderEffect-int-) | Haalt op of stelt rand‑effect in. |
|
|  | [getBorderEffectIntensity()](#getBorderEffectIntensity--) | Haalt op of stelt intensiteit van het rand‑effect in. |
|
|  | [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | Haalt op of stelt intensiteit van het rand‑effect in. |
|
|  | [getHCornerRadius()](#getHCornerRadius--) | Haalt op of stelt horizontale hoekstraal in. |
|
|  | [setHCornerRadius(int value)](#setHCornerRadius-int-) | Haalt op of stelt horizontale hoekstraal in. |
|
|  | [getVCornerRadius()](#getVCornerRadius--) | Haalt op of stelt verticale hoekstraal in. |
|
|  | [setVCornerRadius(int value)](#setVCornerRadius-int-) | Haalt op of stelt verticale hoekstraal in. |
|
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie. |
|
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


Maakt PDF‑handtekening‑txt‑annotatie‑uiterlijk‑object.


### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


Maakt PDF‑handtekening‑txt‑annotatie met opgegeven waarden (title, subject, contents).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | title | java.lang.String | Title. |
|
|  | subject | java.lang.String | Subject. |
|
|  | contents | java.lang.String | Inhoud. |
|

### getContents() {#getContents--}
```
public final String getContents()
```


Haalt op of stelt de inhoud van het annotatie‑object in.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Haalt op of stelt de inhoud van het annotatie‑object in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Haalt op of stelt Subject in, die de beschrijving van het object weergeeft.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Haalt op of stelt Subject in, die de beschrijving van het object weergeeft.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Haalt op of stelt een Title in die wordt weergegeven in de titelbalk van het annotatie‑object.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Haalt op of stelt een Title in die wordt weergegeven in de titelbalk van het annotatie‑object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Haalt op of stelt verschillende randinstellingen in


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Haalt op of stelt verschillende randinstellingen in


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


Haalt op of stelt rand‑effect in.


**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


Haalt op of stelt rand‑effect in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


Haalt de intensiteit van het randeffect op of stelt deze in. Geldig bereik van de waarde is [0..2].


**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


Haalt de intensiteit van het randeffect op of stelt deze in. Geldig bereik van de waarde is [0..2].


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


Haalt op of stelt horizontale hoekstraal in.


**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


Haalt op of stelt horizontale hoekstraal in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


Haalt op of stelt verticale hoekstraal in.


**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


Haalt op of stelt verticale hoekstraal in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie.


**Returns:**
java.lang.String -
