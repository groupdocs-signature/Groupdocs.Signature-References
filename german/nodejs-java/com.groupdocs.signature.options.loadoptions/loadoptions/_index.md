---
title: "LoadOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Ermöglicht das Angeben zusätzlicher Optionen wie Passwort beim Öffnen eines Dokuments zum Signieren."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Ermöglicht das Angeben zusätzlicher Optionen (wie z. B. ein Passwort) beim Öffnen eines zu signierenden Dokuments.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Initialisiert eine neue Instanz der Klasse LoadOptions. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPassword()](#getPassword--) | Liest oder setzt das Passwort zum Öffnen eines geschützten Dokuments. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Liest oder setzt das Passwort zum Öffnen eines geschützten Dokuments. |
| [getLoadExternalResources()](#getLoadExternalResources--) | Liest oder setzt Optionen, die festlegen, ob externe Dokumentressourcen geladen werden sollen. |
| [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | Liest oder setzt Optionen, die festlegen, ob externe Dokumentressourcen geladen werden sollen. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initialisiert eine neue Instanz der Klasse LoadOptions.

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Liest oder setzt das Passwort zum Öffnen eines geschützten Dokuments. Es wird ebenfalls verwendet, um das signierte Dokument als geschützt zu speichern.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Liest oder setzt das Passwort zum Öffnen eines geschützten Dokuments. Es wird ebenfalls verwendet, um das signierte Dokument als geschützt zu speichern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


Liest oder setzt Optionen, die festlegen, ob externe Dokumentressourcen geladen werden sollen. Diese Option mit deaktiviertem Wert (false) ermöglicht das Einsparen von Ladezeit für Dokumente mit vielen oder großen externen Ressourcenlinks. Standardmäßig ist der Wert aktiviert (true).

**Returns:**
boolean
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


Liest oder setzt Optionen, die festlegen, ob externe Dokumentressourcen geladen werden sollen. Diese Option mit deaktiviertem Wert (false) ermöglicht das Einsparen von Ladezeit für Dokumente mit vielen oder großen externen Ressourcenlinks. Standardmäßig ist der Wert aktiviert (true).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

