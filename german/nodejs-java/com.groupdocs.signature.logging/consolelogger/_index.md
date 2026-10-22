---
title: "ConsoleLogger"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Schreibt Protokollnachrichten in die Datei."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.signature.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Schreibt Protokollnachrichten in die Datei.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) | Logger für die Konsole erstellen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Schreibt eine Fehlermeldung in die Konsole. |
| [trace(String message)](#trace-java.lang.String-) | Schreibt eine Trace‑Nachricht in die Konsole. |
| [warning(String message)](#warning-java.lang.String-) | Schreibt eine Warnmeldung in die Konsole; Warn-Lognachrichten liefern Informationen über unerwartete und wiederherstellbare Ereignisse im Anwendungsablauf. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


Logger für die Konsole erstellen.

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Schreibt eine Fehlermeldung in die Konsole. Fehler-Lognachrichten liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | java.lang.String | Die Fehlermeldung. |
| Ausnahme | java.lang.Exception | Die Ausnahme. |

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Schreibt eine Trace‑Nachricht in die Konsole. Trace‑Lognachrichten liefern allgemein nützliche Informationen über den Anwendungsablauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | java.lang.String | Die Trace‑Nachricht. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Schreibt eine Warnmeldung in die Konsole; Warn-Lognachrichten liefern Informationen über unerwartete und wiederherstellbare Ereignisse im Anwendungsablauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | java.lang.String | Die Warnmeldung. |

