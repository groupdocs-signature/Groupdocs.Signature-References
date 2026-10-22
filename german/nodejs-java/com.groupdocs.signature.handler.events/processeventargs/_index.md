---
title: "ProcessEventArgs"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt Daten für verschiedene Ereignisse der Signaturüberprüfung und Suchprozesse bereit."
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.signature.handler.events/processeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ProcessEventArgs extends System.EventArgs
```

Stellt Daten für verschiedene Ereignisse von Signatur-, Verifizierungs- und Suchvorgängen bereit.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ProcessEventArgs()](#ProcessEventArgs--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFilePath()](#getFilePath--) | Stellt den Dateinamen der Dokumentenverarbeitung dar. |
| [setFilePath(String value)](#setFilePath-java.lang.String-) | Stellt den Dateinamen der Dokumentenverarbeitung dar. |
| [getStatus()](#getStatus--) | Gibt den aktuellen Prozesszustand an. |
| [setStatus(int value)](#setStatus-int-) | Gibt den aktuellen Prozesszustand an. |
### ProcessEventArgs() {#ProcessEventArgs--}
```
public ProcessEventArgs()
```


### getFilePath() {#getFilePath--}
```
public final String getFilePath()
```


Stellt den Dateinamen der Dokumentenverarbeitung dar.

**Returns:**
java.lang.String
### setFilePath(String value) {#setFilePath-java.lang.String-}
```
public final void setFilePath(String value)
```


Stellt den Dateinamen der Dokumentenverarbeitung dar.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getStatus() {#getStatus--}
```
public final int getStatus()
```


Gibt den aktuellen Prozesszustand an.

**Returns:**
int
### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


Gibt den aktuellen Prozesszustand an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

