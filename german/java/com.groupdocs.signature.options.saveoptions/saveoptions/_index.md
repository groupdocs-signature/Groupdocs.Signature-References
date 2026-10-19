---
title: "SaveOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Ermöglicht das Angeben zusätzlicher Optionen wie z. B. ein Passwort beim Speichern eines zu signierenden Dokuments."
type: docs
weight: 13
url: /de/java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Ermöglicht das Angeben zusätzlicher Optionen (wie z. B. ein Passwort) beim Speichern eines zu signierenden Dokuments.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Initialisiert eine neue Instanz der SaveOptions-Klasse mit Standardwerten. |
|
|  | [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | Initialisiert eine neue Instanz der SaveOptions-Klasse mit angegebenem Ausgabetyp und Überschreibungs-Flag. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | Liest oder setzt, ob eine vorhandene Datei mit der neuen Ausgabedatei überschrieben werden soll. |
|
|  | [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | Liest oder setzt, ob eine vorhandene Datei mit der neuen Ausgabedatei überschrieben werden soll. |
|
|  | [getPassword()](#getPassword--) | Liest oder setzt das Passwort, um das signierte Dokument mit Passwortschutz zu speichern. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Liest oder setzt das Passwort, um das signierte Dokument mit Passwortschutz zu speichern. |
|
|  | [getUseOriginalPassword()](#getUseOriginalPassword--) | Liest oder setzt, ob das Passwort aus LoadOptions verwendet wird, um das signierte Dokument geschützt zu speichern. |
|
|  | [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | Liest oder setzt, ob das Passwort aus LoadOptions verwendet wird, um das signierte Dokument geschützt zu speichern. |
|
|  | [getAddMissingExtenstion()](#getAddMissingExtenstion--) | Liest oder setzt das Flag, um automatisch eine Erweiterung hinzuzufügen, wenn sie im Ausgabedateipfad fehlte. |
Standardwert ist false.
|
|  | [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | Liest oder setzt das Flag, um automatisch eine Erweiterung hinzuzufügen, wenn sie im Ausgabedateipfad fehlte. |
Standardwert ist false.
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Initialisiert eine neue Instanz der SaveOptions-Klasse mit Standardwerten.


### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


Initialisiert eine neue Instanz der SaveOptions-Klasse mit angegebenem Ausgabetyp und Überschreibungs-Flag.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Flag, ob die signierte Datei mit derselben Datei überschrieben werden soll. |
|

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


Liest oder setzt, ob eine vorhandene Datei mit der neuen Ausgabedatei überschrieben werden soll.
Andernfalls wird eine neue Datei mit einer Nummer als Suffix erstellt.


**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


Liest oder setzt, ob eine vorhandene Datei mit der neuen Ausgabedatei überschrieben werden soll.
Andernfalls wird eine neue Datei mit einer Nummer als Suffix erstellt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Liest oder setzt das Passwort, um das signierte Dokument mit Passwortschutz zu speichern.
Diese Eigenschaft wird für Bilddokumente nicht unterstützt.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Liest oder setzt das Passwort, um das signierte Dokument mit Passwortschutz zu speichern.
Diese Eigenschaft wird für Bilddokumente nicht unterstützt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


Liest oder setzt, ob das Passwort aus LoadOptions verwendet wird, um das signierte Dokument geschützt zu speichern.
Standardwert ist true.
Diese Eigenschaft wird für Bilddokumente nicht unterstützt.


**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


Liest oder setzt, ob das Passwort aus LoadOptions verwendet wird, um das signierte Dokument geschützt zu speichern.
Standardwert ist true.
Diese Eigenschaft wird für Bilddokumente nicht unterstützt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


Liest oder setzt das Flag, um automatisch eine Erweiterung hinzuzufügen, wenn sie im Ausgabedateipfad fehlte.
Standardwert ist false.


**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


Liest oder setzt das Flag, um automatisch eine Erweiterung hinzuzufügen, wenn sie im Ausgabedateipfad fehlte.
Standardwert ist false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

