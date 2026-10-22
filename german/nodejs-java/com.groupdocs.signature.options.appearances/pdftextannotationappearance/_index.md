---
title: "PdfTextAnnotationAppearance"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Beschreibt das Aussehen des PDF‑Text‑Anmerkungsobjekts Titel, Betreff, Inhalt."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

Beschreibt das Aussehen des PDF‑Textanmerkungsobjekts (Titel, Betreff, Inhalt).
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | Erstellt ein PDF‑Signatur‑Txt‑Anmerkungs‑Darstellungsobjekt. |
| [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | Erstellt eine PDF‑Signatur‑Txt‑Anmerkung mit angegebenen Werten (Titel, Betreff, Inhalt). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getContents()](#getContents--) | Liest oder setzt den Inhalt des Annotationsobjekts. |
| [setContents(String value)](#setContents-java.lang.String-) | Liest oder setzt den Inhalt des Annotationsobjekts. |
| [getSubject()](#getSubject--) | Liest oder setzt Subject, das die Beschreibung des Objekts darstellt. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Liest oder setzt Subject, das die Beschreibung des Objekts darstellt. |
| [getTitle()](#getTitle--) | Liest oder setzt einen Title, der in der Titelleiste des Annotationsobjekts angezeigt wird. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Liest oder setzt einen Title, der in der Titelleiste des Annotationsobjekts angezeigt wird. |
| [getBorder()](#getBorder--) | Liest oder setzt verschiedene Rahmen-Einstellungen |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Liest oder setzt verschiedene Rahmen-Einstellungen |
| [getBorderEffect()](#getBorderEffect--) | Liest oder setzt den Rahmen-Effekt. |
| [setBorderEffect(int value)](#setBorderEffect-int-) | Liest oder setzt den Rahmen-Effekt. |
| [getBorderEffectIntensity()](#getBorderEffectIntensity--) | Liest oder setzt die Intensität des Rahmen-Effekts. |
| [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | Liest oder setzt die Intensität des Rahmen-Effekts. |
| [getHCornerRadius()](#getHCornerRadius--) | Liest oder setzt den horizontalen Eckradius. |
| [setHCornerRadius(int value)](#setHCornerRadius-int-) | Liest oder setzt den horizontalen Eckradius. |
| [getVCornerRadius()](#getVCornerRadius--) | Liest oder setzt den vertikalen Eckradius. |
| [setVCornerRadius(int value)](#setVCornerRadius-int-) | Liest oder setzt den vertikalen Eckradius. |
| [toString()](#toString--) | Überschreibe die String-Konvertierung. |
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


Erstellt ein PDF‑Signatur‑Txt‑Anmerkungs‑Darstellungsobjekt.

### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


Erstellt eine PDF‑Signatur‑Txt‑Anmerkung mit angegebenen Werten (Titel, Betreff, Inhalt).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Titel | java.lang.String | Titel. |
| Betreff | java.lang.String | Betreff. |
| Inhalt | java.lang.String | Inhalt. |

### getContents() {#getContents--}
```
public final String getContents()
```


Liest oder setzt den Inhalt des Annotationsobjekts.

**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Liest oder setzt den Inhalt des Annotationsobjekts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Liest oder setzt Subject, das die Beschreibung des Objekts darstellt.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Liest oder setzt Subject, das die Beschreibung des Objekts darstellt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Liest oder setzt einen Title, der in der Titelleiste des Annotationsobjekts angezeigt wird.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Liest oder setzt einen Title, der in der Titelleiste des Annotationsobjekts angezeigt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Liest oder setzt verschiedene Rahmen-Einstellungen

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Liest oder setzt verschiedene Rahmen-Einstellungen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


Liest oder setzt den Rahmen-Effekt.

**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


Liest oder setzt den Rahmen-Effekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


Liest oder setzt die Intensität des Rahmen-Effekts. Gültiger Wertebereich ist [0..2].

**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


Liest oder setzt die Intensität des Rahmen-Effekts. Gültiger Wertebereich ist [0..2].

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


Liest oder setzt den horizontalen Eckradius.

**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


Liest oder setzt den horizontalen Eckradius.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


Liest oder setzt den vertikalen Eckradius.

**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


Liest oder setzt den vertikalen Eckradius.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### toString() {#toString--}
```
public String toString()
```


Überschreibe die String-Konvertierung.

**Returns:**
java.lang.String -
