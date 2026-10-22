---
title: "PdfSaveOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Speicheroptionen für PDF‑Dokumente."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

Speicheroptionen für PDF‑Dokumente.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | Initialisiert eine neue Instanz der Klasse PdfSaveOptions mit Standardwerten. |
| [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | Initialisiert eine neue Instanz der Klasse PdfSaveOptions mit dem angegebenen Ausgabe-Dateiformat. |
| [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | Initialisiert eine neue Instanz der Klasse PdfSaveOptions mit Überschreiben-Flag. |
| [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | Initialisiert eine neue Instanz der Klasse PdfSaveOptions mit dem angegebenen Ausgabe-Dateiformat und Überschreiben-Flag. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Liest oder setzt das Dateiformat des signierten Dokuments. |
| [setFileFormat(int value)](#setFileFormat-int-) | Liest oder setzt das Dateiformat des signierten Dokuments. |
| [toString()](#toString--) | Überschreibe die String-Konvertierung. |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


Initialisiert eine neue Instanz der Klasse PdfSaveOptions mit Standardwerten.

### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


Initialisiert eine neue Instanz der Klasse PdfSaveOptions mit dem angegebenen Ausgabe-Dateiformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileFormat | int | Ausgabetyp [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


Initialisiert eine neue Instanz der Klasse PdfSaveOptions mit Überschreiben-Flag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| overwriteExistingFile | boolean | Flag, ob die signierte Datei mit derselben Datei überschrieben werden soll. |

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initialisiert eine neue Instanz der Klasse PdfSaveOptions mit dem angegebenen Ausgabe-Dateiformat und Überschreiben-Flag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileFormat | int | Ausgabetyp [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
| overwriteExistingFile | boolean | Flag, ob die signierte Datei mit derselben Datei überschrieben werden soll. |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Liest oder setzt das Dateiformat des signierten Dokuments.

**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Liest oder setzt das Dateiformat des signierten Dokuments.

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
