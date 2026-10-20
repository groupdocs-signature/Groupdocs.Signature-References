---
title: "FileLogger"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Scrive i messaggi di log nel file."
type: docs
weight: 11
url: /it/java/com.groupdocs.signature.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class FileLogger implements ILogger
```

Scrive i messaggi di log nel file.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Crea logger su file. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Scrive un messaggio di errore sulla console. |
|
|  | [trace(String message)](#trace-java.lang.String-) | Scrive un messaggio di traccia sulla console. |
|
|  | [warning(String message)](#warning-java.lang.String-) | Scrive un messaggio di avviso sulla console; |
I messaggi di log di avviso forniscono informazioni sull'evento inaspettato e recuperabile nel flusso dell'applicazione.
|
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Crea logger su file.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileName | java.lang.String | Nome file completo con percorso |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Scrive un messaggio di errore sulla console.
I messaggi di log di errore forniscono informazioni sugli eventi non recuperabili nel flusso dell'applicazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | message | java.lang.String | Il messaggio di errore. |
|
|  | eccezione | java.lang.Exception | L'eccezione. |
|

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Scrive un messaggio di traccia sulla console.
I messaggi di log di traccia forniscono informazioni generalmente utili sul flusso dell'applicazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | message | java.lang.String | Il messaggio di traccia. |
|

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Scrive un messaggio di avviso sulla console;
I messaggi di log di avviso forniscono informazioni sull'evento inaspettato e recuperabile nel flusso dell'applicazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | message | java.lang.String | Il messaggio di avviso. |
|

