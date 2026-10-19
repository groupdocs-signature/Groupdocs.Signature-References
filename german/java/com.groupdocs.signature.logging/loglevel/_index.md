---
title: "LogLevel"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Gibt die verfügbaren Log-Level-Typen an."
type: docs
weight: 12
url: /de/java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Gibt die verfügbaren Log-Level-Typen an.
Diese Aufzählung kann als Flags verwendet werden, um mehrere mögliche Werte als aktivierte Bits festzulegen.
Beispiel: LogLevel.Error \| LogLevel.Warning or LogLevel.Error \| LogLevel.Trace

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [None](#None) | Keine Protokollierungsbeschränkung, alle Informationen werden von Trace über Warnungen bis zu Fehlern protokolliert. |
|
|  | [Error](#Error) | Keine Protokollierungsbeschränkung, alle Informationen werden von Trace über Warnungen bis zu Fehlern protokolliert. |
|
|  | [Warning](#Warning) | Wie das All-Level, werden alle Nachrichten einschließlich des Trace-Levels protokolliert. |
|
|  | [Trace](#Trace) | Das Protokollierungslevel, das Nachrichten von der Warnung bis zum Fehlerlevel einschließt. |
|
|  | [All](#All) | Alle Log-Level-Ereignisse (Error, Warning, Trace) werden in das Protokoll aufgenommen. |
|
### None {#None}
```
public static final int None
```


Keine Protokollierungsbeschränkung, alle Informationen werden von Trace über Warnungen bis zu Fehlern protokolliert.


### Error {#Error}
```
public static final int Error
```


Keine Protokollierungsbeschränkung, alle Informationen werden von Trace über Warnungen bis zu Fehlern protokolliert.


### Warning {#Warning}
```
public static final int Warning
```


Wie das All-Level, werden alle Nachrichten einschließlich des Trace-Levels protokolliert.


### Trace {#Trace}
```
public static final int Trace
```


Das Protokollierungslevel, das Nachrichten von der Warnung bis zum Fehlerlevel einschließt.


### All {#All}
```
public static final int All
```


Alle Log-Level-Ereignisse (Error, Warning, Trace) werden in das Protokoll aufgenommen.


