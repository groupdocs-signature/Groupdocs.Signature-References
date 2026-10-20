---
title: "FileLogger"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Schrijft logberichten naar het bestand."
type: docs
weight: 11
url: /nl/java/com.groupdocs.signature.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class FileLogger implements ILogger
```

Schrijft logberichten naar het bestand.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Maak een logger naar bestand. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Schrijft een foutmelding naar de console. |
|
|  | [trace(String message)](#trace-java.lang.String-) | Schrijft een trace-bericht naar de console. |
|
|  | [warning(String message)](#warning-java.lang.String-) | Schrijft een waarschuwingsbericht naar de console; |
Waarschuwingslogberichten geven informatie over onverwachte en herstelbare gebeurtenissen in de applicatiestroom.
|
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Maak een logger naar bestand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileName | java.lang.String | Volledige bestandsnaam met pad |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Schrijft een foutmelding naar de console.
Foutlogberichten geven informatie over onherstelbare gebeurtenissen in de applicatiestroom.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | message | java.lang.String | De foutmelding. |
|
|  | uitzondering | java.lang.Exception | De uitzondering. |
|

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Schrijft een trace-bericht naar de console.
Trace‑logberichten bieden over het algemeen nuttige informatie over de applicatiestroom.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | message | java.lang.String | Het trace‑bericht. |
|

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Schrijft een waarschuwingsbericht naar de console;
Waarschuwingslogberichten geven informatie over onverwachte en herstelbare gebeurtenissen in de applicatiestroom.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | message | java.lang.String | Het waarschuwingsbericht. |
|

