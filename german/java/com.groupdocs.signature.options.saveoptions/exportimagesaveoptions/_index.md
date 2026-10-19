---
title: "ExportImageSaveOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Speicheroptionen zum Exportieren von Dokumenten als Bild."
type: docs
weight: 10
url: /de/java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

Speicheroptionen zum Exportieren von Dokumenten als Bild.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ExportImageSaveOptions()](#ExportImageSaveOptions--) | Initialisiert eine neue Instanz der ExportAsImageSaveOptions-Klasse mit Standardwerten. |
|
|  | [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | Initialisiert eine neue Instanz der ExportAsImageSaveOptions-Klasse mit angegebenem Dateiformat. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Liest oder setzt die Dokumentseitenzahl für den Export. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Liest oder setzt die Dokumentseitenzahl für den Export. |
|
|  | [getExportAllPages()](#getExportAllPages--) | Flag zum Export jeder Seite. |
|
|  | [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | Flag zum Export jeder Seite. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Optionen zum Festlegen der zu signierenden Seiten. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Optionen zum Festlegen der zu signierenden Seiten. |
|
|  | [getPageColumns()](#getPageColumns--) | Liest oder setzt die Anzahl der Spalten für exportierte Bilder. |
|
|  | [setPageColumns(int value)](#setPageColumns-int-) | Liest oder setzt die Anzahl der Spalten für exportierte Bilder. |
|
|  | [getBorder()](#getBorder--) | Liest oder setzt die Einstellungen für den Bildrand. |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Liest oder setzt die Einstellungen für den Bildrand. |
|
|  | [getTiffMultipage()](#getTiffMultipage--) | Platziert Dokumentseiten in verschiedenen Frames in einem Tiff-Bild. |
|
|  | [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | Platziert Dokumentseiten in verschiedenen Frames in einem Tiff-Bild. |
|
|  | [toString()](#toString--) | Überschreibe die String-Konvertierung. |
|
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


Initialisiert eine neue Instanz der ExportAsImageSaveOptions-Klasse mit Standardwerten.


### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


Initialisiert eine neue Instanz der ExportAsImageSaveOptions-Klasse mit angegebenem Dateiformat.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileFormat | int | Ausgabe-Bilddateiformat. |
|

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Liest oder setzt die Dokumentseitenzahl für den Export.
Der minimale Wert ist 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Liest oder setzt die Dokumentseitenzahl für den Export.
Der minimale Wert ist 1.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


Flag zum Export jeder Seite.


**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


Flag zum Export jeder Seite.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Optionen zum Festlegen der zu signierenden Seiten.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Optionen zum Festlegen der zu signierenden Seiten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


Liest oder setzt die Anzahl der Spalten für exportierte Bilder.
Verwenden Sie diese Eigenschaft, wenn Sie Bilder in einer Reihe anordnen müssen.


**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


Liest oder setzt die Anzahl der Spalten für exportierte Bilder.
Verwenden Sie diese Eigenschaft, wenn Sie Bilder in einer Reihe anordnen müssen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Liest oder setzt die Bildecken-Einstellungen. Standardmäßig ist dieser Wert nicht festgelegt.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Liest oder setzt die Bildecken-Einstellungen. Standardmäßig ist dieser Wert nicht festgelegt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


Platziert Dokumentseiten in verschiedenen Frames in einem Tiff-Bild.


**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


Platziert Dokumentseiten in verschiedenen Frames in einem Tiff-Bild.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Überschreibe die String-Konvertierung.


**Returns:**
java.lang.String -
