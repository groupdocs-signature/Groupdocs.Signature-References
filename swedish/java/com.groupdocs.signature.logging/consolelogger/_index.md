---
title: "ConsoleLogger"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Skriver loggmeddelanden till filen."
type: docs
weight: 10
url: /sv/java/com.groupdocs.signature.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Skriver loggmeddelanden till filen.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [ConsoleLogger()](#ConsoleLogger--) | Skapa logger till konsolen. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Skriver ett felmeddelande till konsolen. |
|
|  | [trace(String message)](#trace-java.lang.String-) | Skriver spårningsmeddelande till konsolen. |
|
|  | [warning(String message)](#warning-java.lang.String-) | Skriver varningsmeddelande till konsolen; |
Varningsloggmeddelanden ger information om den oväntade och återhämtningsbara händelsen i applikationsflödet.
|
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


Skapa logger till konsolen.


### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Skriver ett felmeddelande till konsolen.
Fel-loggmeddelanden ger information om oåterhämtningsbara händelser i applikationsflödet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Felmeddelandet. |
|
|  | undantag | java.lang.Exception | Undantaget. |
|

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Skriver spårningsmeddelande till konsolen.
Spårloggmeddelanden ger generellt användbar information om applikationsflödet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Spårmeddelandet. |
|

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Skriver varningsmeddelande till konsolen;
Varningsloggmeddelanden ger information om den oväntade och återhämtningsbara händelsen i applikationsflödet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Varningsmeddelandet. |
|

