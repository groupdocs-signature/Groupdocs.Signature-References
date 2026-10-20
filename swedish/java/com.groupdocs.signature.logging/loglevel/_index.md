---
title: "LogLevel"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Anger vilka typer av meddelanden som skickas till loggaren som är inställd i SignatureSettings."
type: docs
weight: 12
url: /sv/java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Anger vilka typer av meddelanden som skickas till loggern som är inställd i
SignatureSettings
.
Värdena är flaggor och kan kombineras, till exempel
LogLevel.Error \| LogLevel.Warning
.

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [None](#None) | Inget loggas. |
|
|  | [Error](#Error) | Fel: en operation misslyckades. |
|
|  | [Warning](#Warning) | Varningar: en operation lyckades, men dess resultat kanske inte är vad du förväntar dig. |
|
|  | [Trace](#Trace) | Spår: stegen i en operation, såsom dess start och slut. |
|
|  | [All](#All) | Fel, varningar och spår. |
|
### None {#None}
```
public static final int None
```


Inget loggas.


### Error {#Error}
```
public static final int Error
```


Fel: en operation misslyckades.


### Warning {#Warning}
```
public static final int Warning
```


Varningar: en operation lyckades, men dess resultat kanske inte är vad du förväntar dig.


### Trace {#Trace}
```
public static final int Trace
```


Spår: stegen i en operation, såsom dess start och slut.


### All {#All}
```
public static final int All
```


Fel, varningar och spår. Detta är standard.


