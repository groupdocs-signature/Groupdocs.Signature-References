---
title: "FileLogger"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Schreibt Protokollnachrichten in die Datei."
type: docs
weight: 11
url: /de/java/com.groupdocs.signature.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class FileLogger implements ILogger
```

Schreibt Protokollnachrichten in die Datei.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Logger in Datei erstellen. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Schreibt eine Fehlermeldung in die Konsole. |
|
|  | [trace(String message)](#trace-java.lang.String-) | Schreibt eine Trace‑Nachricht in die Konsole. |
|
|  | [warning(String message)](#warning-java.lang.String-) | Schreibt eine Warnmeldung in die Konsole; |
Warnlog‑Nachrichten liefern Informationen über unerwartete und wiederherstellbare Ereignisse im Anwendungsablauf.
|
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Logger in Datei erstellen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileName | java.lang.String | Vollständiger Dateiname mit Pfad |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Schreibt eine Fehlermeldung in die Konsole.
Fehlerlog‑Nachrichten liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Nachricht | java.lang.String | Die Fehlermeldung. |
|
|  | Ausnahme | java.lang.Exception | Die Ausnahme. |
|

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Schreibt eine Trace‑Nachricht in die Konsole.
Trace‑Log‑Nachrichten liefern allgemein nützliche Informationen über den Anwendungsablauf.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Nachricht | java.lang.String | Die Trace-Nachricht. |
|

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Schreibt eine Warnmeldung in die Konsole;
Warnlog‑Nachrichten liefern Informationen über unerwartete und wiederherstellbare Ereignisse im Anwendungsablauf.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Nachricht | java.lang.String | Die Warnmeldung. |
|

