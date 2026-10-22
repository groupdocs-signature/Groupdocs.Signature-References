---
title: "LogLevel"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Gibt die verfügbaren Log-Level-Typen an."
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Gibt die verfügbaren Log-Level-Typen an. Diese Aufzählung kann als Flags verwendet werden, um mehrere mögliche Werte als aktivierte Bits festzulegen. Beispiel: LogLevel.Error | LogLevel.Warning oder LogLevel.Error | LogLevel.Trace
## Felder

| Feld | Beschreibung |
| --- | --- |
| [None](#None) | Keine Protokollbeschränkung, alle Informationen werden von Trace über Warning bis zu Errors protokolliert |
| [Error](#Error) | Keine Protokollbeschränkung, alle Informationen werden von Trace über Warning bis zu Errors protokolliert |
| [Warning](#Warning) | Wie das All-Level, werden alle Nachrichten einschließlich des Trace-Levels protokolliert |
| [Trace](#Trace) | Das Protokollierungslevel, das Nachrichten von Warning bis Error einschließt |
| [All](#All) | Alle Log-Level-Ereignisse (Error, Warning, Trace) werden in das Protokoll aufgenommen |
### None {#None}
```
public static final int None
```


Keine Protokollbeschränkung, alle Informationen werden von Trace über Warning bis zu Errors protokolliert

### Error {#Error}
```
public static final int Error
```


Keine Protokollbeschränkung, alle Informationen werden von Trace über Warning bis zu Errors protokolliert

### Warning {#Warning}
```
public static final int Warning
```


Wie das All-Level, werden alle Nachrichten einschließlich des Trace-Levels protokolliert

### Trace {#Trace}
```
public static final int Trace
```


Das Protokollierungslevel, das Nachrichten von Warning bis Error einschließt

### All {#All}
```
public static final int All
```


Alle Log-Level-Ereignisse (Error, Warning, Trace) werden in das Protokoll aufgenommen

