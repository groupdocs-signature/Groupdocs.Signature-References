---
title: "LoadOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Ermöglicht das Festlegen zusätzlicher Optionen wie ein Passwort beim Öffnen eines zu signierenden Dokuments."
type: docs
weight: 10
url: /de/java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Ermöglicht das Angeben zusätzlicher Optionen (wie z.B. Passwort) beim Öffnen eines Dokuments zum Signieren.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Initialisiert eine neue Instanz der Klasse LoadOptions. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPassword()](#getPassword--) | Liest oder setzt das Passwort zum Öffnen eines geschützten Dokuments. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Liest oder setzt das Passwort zum Öffnen eines geschützten Dokuments. |
|
|  | [getLoadExternalResources()](#getLoadExternalResources--) | Liest oder setzt Optionen, die festlegen, ob externe Dokumentressourcen geladen werden sollen. |
|
|  | [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | Liest oder setzt Optionen, die festlegen, ob externe Dokumentressourcen geladen werden sollen. |
|
|  | [getPermissions()](#getPermissions--) | Die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Interner Setter, verwendet von Dokumentladeprozessoren, um aus der Datei gelesene Berechtigungen zu protokollieren. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initialisiert eine neue Instanz der Klasse LoadOptions.


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Liest oder setzt das Passwort zum Öffnen eines geschützten Dokuments.
Wird außerdem verwendet, um das signierte Dokument als geschützt zu speichern.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Liest oder setzt das Passwort zum Öffnen eines geschützten Dokuments.
Wird außerdem verwendet, um das signierte Dokument als geschützt zu speichern.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


Liest oder setzt Optionen, die festlegen, ob externe Dokumentressourcen geladen werden sollen.
Diese Option mit deaktiviertem Wert (false) ermöglicht es, Ladezeit für Dokumente mit vielen oder großen externen Ressourcenlinks zu sparen.
Standardmäßig ist der Wert aktiviert (true).


**Returns:**
boolean
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


Liest oder setzt Optionen, die festlegen, ob externe Dokumentressourcen geladen werden sollen.
Diese Option mit deaktiviertem Wert (false) ermöglicht es, Ladezeit für Dokumente mit vielen oder großen externen Ressourcenlinks zu sparen.
Standardmäßig ist der Wert aktiviert (true).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


Die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion.
Nur für PDF-Dokumente. Nur lesbar \\u2014 wird beim Laden des Dokuments automatisch gefüllt.
Der Wert ist eine Flag-Kombination aus [Permissions](../../com.groupdocs.signature.options/permissions).


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Interner Setter, verwendet von Dokumentladeprozessoren, um aus der Datei gelesene Berechtigungen zu protokollieren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Integer |  |

