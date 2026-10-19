---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Speicheroptionen für Präsentationsdokumente."
type: docs
weight: 12
url: /de/java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

Speicheroptionen für Präsentationsdokumente.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Initialisiert eine neue Instanz der Klasse PresentationSaveOptions mit Standardwerten. |
|
|  | [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | Initialisiert eine neue Instanz der Klasse PresentationSaveOptions mit dem angegebenen Ausgabe-Dateiformat. |
|
|  | [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | Initialisiert eine neue Instanz der Klasse PresentationSaveOptions mit dem angegebenen Ausgabetyp und Überschreibungs-Flag. |
|
|  | [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | Initialisiert eine neue Instanz der Klasse PresentationSaveOptions mit dem angegebenen Ausgabe-Dateiformat und Überschreibungs-Flag. |
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
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Initialisiert eine neue Instanz der Klasse PresentationSaveOptions mit Standardwerten.


### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


Initialisiert eine neue Instanz der Klasse PresentationSaveOptions mit dem angegebenen Ausgabe-Dateiformat.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileFormat | int | Ausgabetyp [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
|

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


Initialisiert eine neue Instanz der Klasse PresentationSaveOptions mit dem angegebenen Ausgabetyp und Überschreibungs-Flag.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Flag, ob die signierte Datei mit derselben Datei überschrieben werden soll. |
|

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initialisiert eine neue Instanz der Klasse PresentationSaveOptions mit dem angegebenen Ausgabe-Dateiformat und Überschreibungs-Flag.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileFormat | int | Ausgabetyp [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
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
