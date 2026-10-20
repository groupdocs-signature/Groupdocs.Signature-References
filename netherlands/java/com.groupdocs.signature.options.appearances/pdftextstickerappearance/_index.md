---
title: "PdfTextStickerAppearance"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Beschrijft de weergave van een PDF‑tekstannotatie‑sticker‑object en het pop‑up‑venster van de sticker."
type: docs
weight: 14
url: /nl/java/com.groupdocs.signature.options.appearances/pdftextstickerappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfTextStickerAppearance extends SignatureAppearance
```

Beschrijft de weergave van een PDF‑tekstannotatie‑sticker‑object en het pop‑up‑venster van de sticker.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PdfTextStickerAppearance()](#PdfTextStickerAppearance--) | Maakt een PDF-handtekeningtekstannotatie-uiterlijkobject aan. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getTitle()](#getTitle--) | Haalt op of stelt de titel van het pop-upvenster in. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Haalt op of stelt de titel van het pop-upvenster in. |
|
|  | [getSubject()](#getSubject--) | Haalt op of stelt het onderwerp in. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Haalt op of stelt het onderwerp in. |
|
|  | [getContents()](#getContents--) | Haalt op of stelt de inhoud van het pop-upvenster in. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | Haalt op of stelt de inhoud van het pop-upvenster in. |
|
|  | [getOpened()](#getOpened--) | Stel in of het sticker-pop-upvenster standaard wordt geopend. |
|
|  | [setOpened(boolean value)](#setOpened-boolean-) | Stel in of het sticker-pop-upvenster standaard wordt geopend. |
|
|  | [getIcon()](#getIcon--) | Haalt op of stelt het pictogram van de sticker in. |
|
|  | [setIcon(int value)](#setIcon-int-) | Haalt op of stelt het pictogram van de sticker in. |
|
|  | [getDefaultAppearance()](#getDefaultAppearance--) | Haalt het standaarduiterlijk voor de sticker op. |
|
|  | [resetDefaultAppearance()](#resetDefaultAppearance--) | Wis de waarden van het standaarduiterlijk voor de sticker. |
|
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie. |
|
### PdfTextStickerAppearance() {#PdfTextStickerAppearance--}
```
public PdfTextStickerAppearance()
```


Maakt een PDF-handtekeningtekstannotatie-uiterlijkobject aan.


### getTitle() {#getTitle--}
```
public final String getTitle()
```


Haalt op of stelt de titel van het pop-upvenster in.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Haalt op of stelt de titel van het pop-upvenster in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Haalt op of stelt het onderwerp in.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Haalt op of stelt het onderwerp in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getContents() {#getContents--}
```
public final String getContents()
```


Haalt op of stelt de inhoud van het pop-upvenster in.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Haalt op of stelt de inhoud van het pop-upvenster in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getOpened() {#getOpened--}
```
public final boolean getOpened()
```


Stel in of het sticker-pop-upvenster standaard wordt geopend.


**Returns:**
boolean
### setOpened(boolean value) {#setOpened-boolean-}
```
public final void setOpened(boolean value)
```


Stel in of het sticker-pop-upvenster standaard wordt geopend.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getIcon() {#getIcon--}
```
public final int getIcon()
```


Haalt op of stelt het pictogram van de sticker in.


**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public final void setIcon(int value)
```


Haalt op of stelt het pictogram van de sticker in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public static PdfTextStickerAppearance getDefaultAppearance()
```


Haalt het standaarduiterlijk voor de sticker op. Deze eigenschappen worden als standaard toegepast als
Options.SignatureAppearance-eigenschap is niet gespecificeerd.
De eigenschappen kunnen op elk moment door de gebruiker worden gewijzigd.


**Returns:**
[PdfTextStickerAppearance](../../com.groupdocs.signature.options.appearances/pdftextstickerappearance)
### resetDefaultAppearance() {#resetDefaultAppearance--}
```
public static void resetDefaultAppearance()
```


Wis de waarden van het standaarduiterlijk voor de sticker.


### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie.


**Returns:**
java.lang.String -
