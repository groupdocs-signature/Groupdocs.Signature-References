---
title: "PdfTextStickerAppearance"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Beskriver utseendet på PDF-textanteckningsklisterobjektet och dess popup-fönster."
type: docs
weight: 14
url: /sv/java/com.groupdocs.signature.options.appearances/pdftextstickerappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfTextStickerAppearance extends SignatureAppearance
```

Beskriver utseendet på PDF-textanteckningsklisterobjektet och dess popup-fönster.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [PdfTextStickerAppearance()](#PdfTextStickerAppearance--) | Skapar ett PDF‑signaturtext‑annoteringsutseende‑objekt. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getTitle()](#getTitle--) | Hämtar eller anger titel för popup‑fönster. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Hämtar eller anger titel för popup‑fönster. |
|
|  | [getSubject()](#getSubject--) | Hämtar eller anger ämne. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Hämtar eller anger ämne. |
|
|  | [getContents()](#getContents--) | Hämtar eller anger innehållet i popup‑fönstret. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | Hämtar eller anger innehållet i popup‑fönstret. |
|
|  | [getOpened()](#getOpened--) | Ställ in om klistermärke‑popup‑fönstret ska öppnas som standard. |
|
|  | [setOpened(boolean value)](#setOpened-boolean-) | Ställ in om klistermärke‑popup‑fönstret ska öppnas som standard. |
|
|  | [getIcon()](#getIcon--) | Hämtar eller anger ikonen för klistermärket. |
|
|  | [setIcon(int value)](#setIcon-int-) | Hämtar eller anger ikonen för klistermärket. |
|
|  | [getDefaultAppearance()](#getDefaultAppearance--) | Hämtar standardutseende för klistermärket. |
|
|  | [resetDefaultAppearance()](#resetDefaultAppearance--) | Rensar värden för standardutseende för klistermärket. |
|
|  | [toString()](#toString--) | Åsidosätt strängkonvertering. |
|
### PdfTextStickerAppearance() {#PdfTextStickerAppearance--}
```
public PdfTextStickerAppearance()
```


Skapar ett PDF‑signaturtext‑annoteringsutseende‑objekt.


### getTitle() {#getTitle--}
```
public final String getTitle()
```


Hämtar eller anger titel för popup‑fönster.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Hämtar eller anger titel för popup‑fönster.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Hämtar eller anger ämne.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Hämtar eller anger ämne.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getContents() {#getContents--}
```
public final String getContents()
```


Hämtar eller anger innehållet i popup‑fönstret.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Hämtar eller anger innehållet i popup‑fönstret.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getOpened() {#getOpened--}
```
public final boolean getOpened()
```


Ställ in om klistermärke‑popup‑fönstret ska öppnas som standard.


**Returns:**
boolean
### setOpened(boolean value) {#setOpened-boolean-}
```
public final void setOpened(boolean value)
```


Ställ in om klistermärke‑popup‑fönstret ska öppnas som standard.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getIcon() {#getIcon--}
```
public final int getIcon()
```


Hämtar eller anger ikonen för klistermärket.


**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public final void setIcon(int value)
```


Hämtar eller anger ikonen för klistermärket.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public static PdfTextStickerAppearance getDefaultAppearance()
```


Hämtar standardutseende för klistermärket. Dessa egenskaper tillämpas som standard om
Options.SignatureAppearance‑egenskapen är inte specificerad.
Egenskaperna kan ändras av användaren när som helst.


**Returns:**
[PdfTextStickerAppearance](../../com.groupdocs.signature.options.appearances/pdftextstickerappearance)
### resetDefaultAppearance() {#resetDefaultAppearance--}
```
public static void resetDefaultAppearance()
```


Rensar värden för standardutseende för klistermärket.


### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering.


**Returns:**
java.lang.String -
