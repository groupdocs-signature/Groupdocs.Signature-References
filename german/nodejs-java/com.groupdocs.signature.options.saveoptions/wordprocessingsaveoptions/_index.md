---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Speicheroptionen für Textverarbeitungsdokumente."
type: docs
weight: 15
url: /de/nodejs-java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

Speicheroptionen für Textverarbeitungsdokumente.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Initialisiert eine neue Instanz der Klasse WordProcessingSaveOptions mit Standardwerten. |
| [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | Initialisiert eine neue Instanz der Klasse WordProcessingSaveOptions mit dem angegebenen Ausgabe-Dateiformat. |
| [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | Initialisiert eine neue Instanz der Klasse WordProcessingSaveOptions mit dem angegebenen Ausgabetyp und Überschreiben-Flag. |
| [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | Initialisiert eine neue Instanz der Klasse WordProcessingSaveOptions mit dem angegebenen Ausgabe-Dateiformat und Überschreiben-Flag. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Liest oder setzt das Dateiformat des signierten Dokuments. |
| [setFileFormat(int value)](#setFileFormat-int-) | Liest oder setzt das Dateiformat des signierten Dokuments. |
| [toString()](#toString--) | Überschreibe Zeichenkettenkonvertierung |
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Initialisiert eine neue Instanz der Klasse WordProcessingSaveOptions mit Standardwerten.

### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


Initialisiert eine neue Instanz der Klasse WordProcessingSaveOptions mit dem angegebenen Ausgabe-Dateiformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileFormat | int | Ausgabetyp [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


Initialisiert eine neue Instanz der Klasse WordProcessingSaveOptions mit dem angegebenen Ausgabetyp und Überschreiben-Flag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| overwriteExistingFile | boolean | Flag, ob die signierte Datei mit derselben Datei überschrieben werden soll. |

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initialisiert eine neue Instanz der Klasse WordProcessingSaveOptions mit dem angegebenen Ausgabe-Dateiformat und Überschreiben-Flag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileFormat | int | Ausgabetyp [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
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


Überschreibe Zeichenkettenkonvertierung

**Returns:**
java.lang.String -
