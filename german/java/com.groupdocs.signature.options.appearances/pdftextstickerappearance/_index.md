---
title: "PdfTextStickerAppearance"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Beschreibt das Erscheinungsbild von PDF‑Textanmerkungs‑Sticker‑Objekten und dem Popup‑Fenster des Stickers."
type: docs
weight: 14
url: /de/java/com.groupdocs.signature.options.appearances/pdftextstickerappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfTextStickerAppearance extends SignatureAppearance
```

Beschreibt das Erscheinungsbild von PDF‑Textanmerkungs‑Sticker‑Objekten und dem Popup‑Fenster des Stickers.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfTextStickerAppearance()](#PdfTextStickerAppearance--) | Erstellt ein PDF‑Signatur‑Text‑Anmerkungs‑Erscheinungs‑Objekt. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getTitle()](#getTitle--) | Liest oder setzt den Titel des Pop‑up‑Fensters. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Liest oder setzt den Titel des Pop‑up‑Fensters. |
|
|  | [getSubject()](#getSubject--) | Liest oder setzt den Betreff. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Liest oder setzt den Betreff. |
|
|  | [getContents()](#getContents--) | Liest oder setzt den Inhalt des Pop‑up‑Fensters. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | Liest oder setzt den Inhalt des Pop‑up‑Fensters. |
|
|  | [getOpened()](#getOpened--) | Konfiguriert, ob das Sticker‑Pop‑up‑Fenster standardmäßig geöffnet wird. |
|
|  | [setOpened(boolean value)](#setOpened-boolean-) | Konfiguriert, ob das Sticker‑Pop‑up‑Fenster standardmäßig geöffnet wird. |
|
|  | [getIcon()](#getIcon--) | Liest oder setzt das Symbol des Stickers. |
|
|  | [setIcon(int value)](#setIcon-int-) | Liest oder setzt das Symbol des Stickers. |
|
|  | [getDefaultAppearance()](#getDefaultAppearance--) | Liest das Standard‑Erscheinungsbild für den Sticker. |
|
|  | [resetDefaultAppearance()](#resetDefaultAppearance--) | Löscht die Werte des Standard‑Erscheinungsbildes für den Sticker. |
|
|  | [toString()](#toString--) | Überschreibe die String-Konvertierung. |
|
### PdfTextStickerAppearance() {#PdfTextStickerAppearance--}
```
public PdfTextStickerAppearance()
```


Erstellt ein PDF‑Signatur‑Text‑Anmerkungs‑Erscheinungs‑Objekt.


### getTitle() {#getTitle--}
```
public final String getTitle()
```


Liest oder setzt den Titel des Pop‑up‑Fensters.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Liest oder setzt den Titel des Pop‑up‑Fensters.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Liest oder setzt den Betreff.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Liest oder setzt den Betreff.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getContents() {#getContents--}
```
public final String getContents()
```


Liest oder setzt den Inhalt des Pop‑up‑Fensters.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Liest oder setzt den Inhalt des Pop‑up‑Fensters.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getOpened() {#getOpened--}
```
public final boolean getOpened()
```


Konfiguriert, ob das Sticker‑Pop‑up‑Fenster standardmäßig geöffnet wird.


**Returns:**
boolean
### setOpened(boolean value) {#setOpened-boolean-}
```
public final void setOpened(boolean value)
```


Konfiguriert, ob das Sticker‑Pop‑up‑Fenster standardmäßig geöffnet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getIcon() {#getIcon--}
```
public final int getIcon()
```


Liest oder setzt das Symbol des Stickers.


**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public final void setIcon(int value)
```


Liest oder setzt das Symbol des Stickers.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public static PdfTextStickerAppearance getDefaultAppearance()
```


Liest das Standard‑Erscheinungsbild für den Sticker. Diese Eigenschaften werden standardmäßig angewendet, wenn
Die Options.SignatureAppearance‑Eigenschaft ist nicht angegeben.
Die Eigenschaften können vom Benutzer jederzeit geändert werden.


**Returns:**
[PdfTextStickerAppearance](../../com.groupdocs.signature.options.appearances/pdftextstickerappearance)
### resetDefaultAppearance() {#resetDefaultAppearance--}
```
public static void resetDefaultAppearance()
```


Löscht die Werte des Standard‑Erscheinungsbildes für den Sticker.


### toString() {#toString--}
```
public String toString()
```


Überschreibe die String-Konvertierung.


**Returns:**
java.lang.String -
