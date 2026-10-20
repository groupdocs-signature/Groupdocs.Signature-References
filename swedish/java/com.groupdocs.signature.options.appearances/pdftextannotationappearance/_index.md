---
title: "PdfTextAnnotationAppearance"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Beskriver utseendet för PDF-textannoteringsobjektet Title Subject Content."
type: docs
weight: 13
url: /sv/java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

Beskriver utseendet på PDF-textanteckningsobjektet (Titel, Ämne, Innehåll).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | Skapar PDF signature txt annotation appearance object. |
|
|  | [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | Skapar PDF signature txt annotation med angivna värden (title, subject, contents). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getContents()](#getContents--) | Hämtar eller anger innehåll för annoteringsobjektet. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | Hämtar eller anger innehåll för annoteringsobjektet. |
|
|  | [getSubject()](#getSubject--) | Hämtar eller anger Subject som representerar objektets beskrivning. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Hämtar eller anger Subject som representerar objektets beskrivning. |
|
|  | [getTitle()](#getTitle--) | Hämtar eller anger en Title som kommer att visas i titelraden för annoteringsobjektet. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Hämtar eller anger en Title som kommer att visas i titelraden för annoteringsobjektet. |
|
|  | [getBorder()](#getBorder--) | Hämtar eller anger olika kantinställningar |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Hämtar eller anger olika kantinställningar |
|
|  | [getBorderEffect()](#getBorderEffect--) | Hämtar eller anger kant-effekt. |
|
|  | [setBorderEffect(int value)](#setBorderEffect-int-) | Hämtar eller anger kant-effekt. |
|
|  | [getBorderEffectIntensity()](#getBorderEffectIntensity--) | Hämtar eller anger intensitet för kant-effekt. |
|
|  | [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | Hämtar eller anger intensitet för kant-effekt. |
|
|  | [getHCornerRadius()](#getHCornerRadius--) | Hämtar eller anger horisontell hörnradie. |
|
|  | [setHCornerRadius(int value)](#setHCornerRadius-int-) | Hämtar eller anger horisontell hörnradie. |
|
|  | [getVCornerRadius()](#getVCornerRadius--) | Hämtar eller anger vertikal hörnradie. |
|
|  | [setVCornerRadius(int value)](#setVCornerRadius-int-) | Hämtar eller anger vertikal hörnradie. |
|
|  | [toString()](#toString--) | Åsidosätt strängkonvertering. |
|
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


Skapar PDF signature txt annotation appearance object.


### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


Skapar PDF signature txt annotation med angivna värden (title, subject, contents).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | titel | java.lang.String | Titel. |
|
|  | ämne | java.lang.String | Ämne. |
|
|  | innehåll | java.lang.String | Innehåll. |
|

### getContents() {#getContents--}
```
public final String getContents()
```


Hämtar eller anger innehåll för annoteringsobjektet.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Hämtar eller anger innehåll för annoteringsobjektet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Hämtar eller anger Subject som representerar objektets beskrivning.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Hämtar eller anger Subject som representerar objektets beskrivning.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Hämtar eller anger en Title som kommer att visas i titelraden för annoteringsobjektet.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Hämtar eller anger en Title som kommer att visas i titelraden för annoteringsobjektet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Hämtar eller anger olika kantinställningar


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Hämtar eller anger olika kantinställningar


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


Hämtar eller anger kant-effekt.


**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


Hämtar eller anger kant-effekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


Hämtar eller anger intensiteten för kantens effekt. Giltigt värdeintervall är [0..2].


**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


Hämtar eller anger intensiteten för kantens effekt. Giltigt värdeintervall är [0..2].


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


Hämtar eller anger horisontell hörnradie.


**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


Hämtar eller anger horisontell hörnradie.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


Hämtar eller anger vertikal hörnradie.


**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


Hämtar eller anger vertikal hörnradie.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering.


**Returns:**
java.lang.String -
