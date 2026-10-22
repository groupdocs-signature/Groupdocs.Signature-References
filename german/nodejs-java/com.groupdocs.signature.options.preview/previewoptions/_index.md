---
title: "PreviewOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt Dokumentvorschau‑Optionen dar."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Stellt Dokumentvorschau‑Optionen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | Initialisiert PreviewOptions-Objekt. |
| [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | Initialisiert PreviewOptions-Objekt. |
| [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | Initialisiert PreviewOptions-Objekt. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWidth()](#getWidth--) | Lese oder setze Breite der Vorschaubilder. |
| [setWidth(int value)](#setWidth-int-) | Lese oder setze Breite der Vorschaubilder. |
| [getHeight()](#getHeight--) | Lese oder setze Höhe der Vorschaubilder. |
| [setHeight(int value)](#setHeight-int-) | Lese oder setze Höhe der Vorschaubilder. |
| [getPageNumbers()](#getPageNumbers--) | Lese oder setze Seitenzahlen der Vorschaubilder. |
| [setPageNumbers(int[] value)](#setPageNumbers-int---) | Lese oder setze Seitenzahlen der Vorschaubilder. |
| [getPreviewFormat()](#getPreviewFormat--) | Liest oder setzt das Format der Vorschaubilder. |
| [setPreviewFormat(int value)](#setPreviewFormat-int-) | Liest oder setzt das Format der Vorschaubilder. |
| [getHideSignatures()](#getHideSignatures--) | Lese oder setze Flag, um Signaturen im Seitenvorschau-Bild zu verbergen. |
| [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | Lese oder setze Flag, um Signaturen im Seitenvorschau-Bild zu verbergen. |
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


Initialisiert PreviewOptions-Objekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | Schnittstelle, die die Methode zum Erstellen eines Ausgabeseiten‑Vorschau‑Streams definiert. |
| pageNumbers | int[] | Gewünschte Seitenzahlen |

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


Initialisiert PreviewOptions-Objekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | Schnittstelle, die die Methode zum Erstellen eines Ausgabeseiten‑Vorschau‑Streams definiert. |
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


Initialisiert PreviewOptions-Objekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateipfadformat | java.lang.String | Pfad zur Ausgabedatei. |
| pageNumbers | int[] | Gewünschte Seitenzahlen |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Lese oder setze Breite der Vorschaubilder.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Lese oder setze Breite der Vorschaubilder.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Lese oder setze Höhe der Vorschaubilder.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Lese oder setze Höhe der Vorschaubilder.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Lese oder setze Seitenzahlen der Vorschaubilder.

**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Lese oder setze Seitenzahlen der Vorschaubilder.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Liest oder setzt das Format der Vorschaubilder.

**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Liest oder setzt das Format der Vorschaubilder.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


Liest oder setzt das Flag, um Signaturen im Seitenvorschau-Bild auszublenden. Nur Signaturen, die als IsSignature markiert sind, werden im generierten Dokumentseitenbild ausgeblendet.

**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


Liest oder setzt das Flag, um Signaturen im Seitenvorschau-Bild auszublenden. Nur Signaturen, die als IsSignature markiert sind, werden im generierten Dokumentseitenbild ausgeblendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

