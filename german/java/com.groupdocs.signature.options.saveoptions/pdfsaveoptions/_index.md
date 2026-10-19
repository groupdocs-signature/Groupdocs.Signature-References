---
title: "PdfSaveOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Speicheroptionen für PDF-Dokumente."
type: docs
weight: 11
url: /de/java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

Speicheroptionen für PDF-Dokumente.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfSaveOptions()](#PdfSaveOptions--) | Initialisiert eine neue Instanz der Klasse PdfSaveOptions mit Standardwerten. |
|
|  | [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | Initialisiert eine neue Instanz der Klasse PdfSaveOptions mit dem angegebenen Ausgabe-Dateiformat. |
|
|  | [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | Initialisiert eine neue Instanz der Klasse PdfSaveOptions mit Überschreibungs-Flag. |
|
|  | [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | Initialisiert eine neue Instanz der Klasse PdfSaveOptions mit dem angegebenen Ausgabe-Dateiformat und Überschreibungs-Flag. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Liest oder setzt das Dateiformat des signierten Dokuments. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Liest oder setzt das Dateiformat des signierten Dokuments. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | Ein Berechtigungspasswort (das primäre Passwort) erfordert ein Passwort, um die Berechtigungseinstellungen zu ändern. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Ein Berechtigungspasswort (das primäre Passwort) erfordert ein Passwort, um die Berechtigungseinstellungen zu ändern. |
|
|  | [getPermissions()](#getPermissions--) | Die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion. |
|
|  | [toString()](#toString--) | Überschreibe die String-Konvertierung. |
|
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
|  | fileFormat | int | Ausgabetyp [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


Initialisiert eine neue Instanz der Klasse PdfSaveOptions mit Überschreibungs-Flag.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Flag, ob die signierte Datei mit derselben Datei überschrieben werden soll. |
|

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initialisiert eine neue Instanz der Klasse PdfSaveOptions mit dem angegebenen Ausgabe-Dateiformat und Überschreibungs-Flag.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileFormat | int | Ausgabetyp [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
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

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Ein Berechtigungspasswort (das primäre Passwort) erfordert ein Passwort, um die Berechtigungseinstellungen zu ändern.


**Returns:**
java.lang.String
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Ein Berechtigungspasswort (das primäre Passwort) erfordert ein Passwort, um die Berechtigungseinstellungen zu ändern.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


Die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion.


Um diese Berechtigungen zu ändern, die
PermissionsPassword
muss gesetzt werden.
Der Wert ist eine Flag-Kombination aus [Permissions](../../com.groupdocs.signature.options/permissions).
Ein
null
Wert bedeutet, dass keine expliziten Berechtigungen angewendet werden.


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


Überschreibe die String-Konvertierung.


**Returns:**
java.lang.String -
