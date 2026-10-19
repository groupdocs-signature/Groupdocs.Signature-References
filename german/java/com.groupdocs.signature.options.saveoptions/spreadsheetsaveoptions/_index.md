---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Speicheroptionen für Tabellenkalkulationsdokumente."
type: docs
weight: 14
url: /de/java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

Speicheroptionen für Tabellenkalkulationsdokumente.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Initialisiert eine neue Instanz der Klasse SpreadsheetSaveOptions mit Standardwerten. |
|
|  | [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | Initialisiert eine neue Instanz der Klasse SpreadsheetSaveOptions mit vordefiniertem Ausgabe-Dateiformat. |
|
|  | [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | Initialisiert eine neue Instanz der Klasse SpreadsheetSaveOptions mit dem angegebenen Ausgabetyp und Überschreibungs-Flag. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Liest oder setzt das Dateiformat des signierten Dokuments. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Liest oder setzt das Dateiformat des signierten Dokuments. |
|
|  | [toString()](#toString--) | Überschreibe die String-Konvertierung. |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Initialisiert eine neue Instanz der Klasse SpreadsheetSaveOptions mit Standardwerten.


### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


Initialisiert eine neue Instanz der Klasse SpreadsheetSaveOptions mit vordefiniertem Ausgabe-Dateiformat.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileFormat | int | Gibt das Ausgabe-Dateiformat an. |
|

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initialisiert eine neue Instanz der Klasse SpreadsheetSaveOptions mit dem angegebenen Ausgabetyp und Überschreibungs-Flag.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileFormat | int | Gibt das Ausgabe-Dateiformat an. |
|
|  | overwriteExistingFile | boolean | Flag, ob die signierte Datei mit derselben Datei überschrieben werden soll. |
|

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
