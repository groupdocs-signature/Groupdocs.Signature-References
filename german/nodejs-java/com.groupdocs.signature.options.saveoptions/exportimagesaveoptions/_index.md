---
title: "ExportImageSaveOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Speicheroptionen zum Exportieren von Dokumenten als Bild."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
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
| [ExportImageSaveOptions()](#ExportImageSaveOptions--) | Initialisiert eine neue Instanz der Klasse ExportAsImageSaveOptions mit Standardwerten. |
| [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | Initialisiert eine neue Instanz der Klasse ExportAsImageSaveOptions mit dem angegebenen Dateiformat. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | Liest oder setzt die Dokumentseitenzahl für den Export. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Liest oder setzt die Dokumentseitenzahl für den Export. |
| [getExportAllPages()](#getExportAllPages--) | Flag, um jede Seite zu exportieren. |
| [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | Flag, um jede Seite zu exportieren. |
| [getPagesSetup()](#getPagesSetup--) | Optionen, um die zu signierenden Seiten anzugeben. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Optionen, um die zu signierenden Seiten anzugeben. |
| [getPageColumns()](#getPageColumns--) | Liest oder setzt die Anzahl der Spalten für exportierte Bilder. |
| [setPageColumns(int value)](#setPageColumns-int-) | Liest oder setzt die Anzahl der Spalten für exportierte Bilder. |
| [getBorder()](#getBorder--) | Liest oder setzt die Bildecken-Einstellungen. |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Liest oder setzt die Bildecken-Einstellungen. |
| [getTiffMultipage()](#getTiffMultipage--) | Platziert Dokumentseiten in verschiedenen Frames in einem Tiff-Bild. |
| [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | Platziert Dokumentseiten in verschiedenen Frames in einem Tiff-Bild. |
| [toString()](#toString--) | Überschreibe die String-Konvertierung. |
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


Initialisiert eine neue Instanz der Klasse ExportAsImageSaveOptions mit Standardwerten.

### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


Initialisiert eine neue Instanz der Klasse ExportAsImageSaveOptions mit dem angegebenen Dateiformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileFormat | int | Ausgabe-Bilddateiformat. |

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Liest oder setzt die Dokumentseitenzahl für den Export. Minimalwert ist 1.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Liest oder setzt die Dokumentseitenzahl für den Export. Minimalwert ist 1.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


Flag, um jede Seite zu exportieren.

**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


Flag, um jede Seite zu exportieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Optionen, um die zu signierenden Seiten anzugeben.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Optionen, um die zu signierenden Seiten anzugeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


Liest oder setzt die Anzahl der Spalten für exportierte Bilder. Verwenden Sie diese Eigenschaft, wenn Sie Bilder in einer Reihe anordnen möchten.

**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


Liest oder setzt die Anzahl der Spalten für exportierte Bilder. Verwenden Sie diese Eigenschaft, wenn Sie Bilder in einer Reihe anordnen möchten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Liest oder setzt die Bildecken-Einstellungen. Standardmäßig ist dieser Wert nicht gesetzt.

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Liest oder setzt die Bildecken-Einstellungen. Standardmäßig ist dieser Wert nicht gesetzt.

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
