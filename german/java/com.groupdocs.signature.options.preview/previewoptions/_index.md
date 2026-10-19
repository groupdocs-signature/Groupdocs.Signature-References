---
title: "PreviewOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt Optionen für die Dokumentvorschau dar."
type: docs
weight: 11
url: /de/java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Stellt Optionen für die Dokumentvorschau dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | Initialisiert das PreviewOptions-Objekt. |
|
|  | [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | Initialisiert das PreviewOptions-Objekt. |
|
|  | [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | Initialisiert das PreviewOptions-Objekt. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWidth()](#getWidth--) | Liest oder setzt die Breite der Vorschaubilder. |
|
|  | [setWidth(int value)](#setWidth-int-) | Liest oder setzt die Breite der Vorschaubilder. |
|
|  | [getHeight()](#getHeight--) | Liest oder setzt die Höhe der Vorschaubilder. |
|
|  | [setHeight(int value)](#setHeight-int-) | Liest oder setzt die Höhe der Vorschaubilder. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Liest oder setzt die Seitenzahlen der Vorschaubilder. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Liest oder setzt die Seitenzahlen der Vorschaubilder. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Ruft das Format der Vorschaubilder ab oder legt es fest. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Ruft das Format der Vorschaubilder ab oder legt es fest. |
|
|  | [getHideSignatures()](#getHideSignatures--) | Liest oder setzt das Flag, um Signaturen im Seitenvorschau‑Bild zu verbergen. |
|
|  | [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | Liest oder setzt das Flag, um Signaturen im Seitenvorschau‑Bild zu verbergen. |
|
|  | [getResolution()](#getResolution--) | Liest die Auflösung der Vorschaubilder in DPI (dots per inch). |
|
|  | [setResolution(int value)](#setResolution-int-) | Setzt die Auflösung der Vorschaubilder in DPI (dots per inch). |
|
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


Initialisiert das PreviewOptions-Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | Schnittstelle, die die Methode zum Erstellen eines Ausgabeseiten-Vorschau-Streams definiert. |
|
|  | pageNumbers | int[] | Gewünschte Seitenzahlen |
|

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


Initialisiert das PreviewOptions-Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | Schnittstelle, die die Methode zum Erstellen eines Ausgabeseiten-Vorschau-Streams definiert. |
|
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


Initialisiert das PreviewOptions-Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Pfad zur Ausgabedatei. |
|
|  | pageNumbers | int[] | Gewünschte Seitenzahlen |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Liest oder setzt die Breite der Vorschaubilder.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Liest oder setzt die Breite der Vorschaubilder.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Liest oder setzt die Höhe der Vorschaubilder.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Liest oder setzt die Höhe der Vorschaubilder.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Liest oder setzt die Seitenzahlen der Vorschaubilder.


**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Liest oder setzt die Seitenzahlen der Vorschaubilder.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Ruft das Format der Vorschaubilder ab oder legt es fest.


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Ruft das Format der Vorschaubilder ab oder legt es fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


Liest oder setzt das Flag, um Signaturen im Seitenvorschau‑Bild zu verbergen.
Nur Signaturen, die als IsSignature markiert sind, werden im generierten Dokumentseitenbild ausgeblendet.


**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


Liest oder setzt das Flag, um Signaturen im Seitenvorschau‑Bild zu verbergen.
Nur Signaturen, die als IsSignature markiert sind, werden im generierten Dokumentseitenbild ausgeblendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Liest die Auflösung der Vorschaubilder in DPI (dots per inch).


**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Setzt die Auflösung der Vorschaubilder in DPI (dots per inch).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

