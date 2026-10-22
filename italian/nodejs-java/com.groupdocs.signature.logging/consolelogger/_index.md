---
title: "ConsoleLogger"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Scrive i messaggi di log nel file."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.signature.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Scrive i messaggi di log nel file.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) | Crea logger per la console. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Scrive un messaggio di errore sulla console. |
| [trace(String message)](#trace-java.lang.String-) | Scrive un messaggio di traccia sulla console. |
| [warning(String message)](#warning-java.lang.String-) | Scrive un messaggio di avviso sulla console; i messaggi di log di avviso forniscono informazioni sull'evento inaspettato e recuperabile nel flusso dell'applicazione. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


Crea logger per la console.

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Scrive un messaggio di errore sulla console. I messaggi di log di errore forniscono informazioni sugli eventi non recuperabili nel flusso dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | java.lang.String | Il messaggio di errore. |
| eccezione | java.lang.Exception | L'eccezione. |

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Scrive un messaggio di traccia sulla console. I messaggi di log di traccia forniscono informazioni generalmente utili sul flusso dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | java.lang.String | Il messaggio di traccia. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Scrive un messaggio di avviso sulla console; i messaggi di log di avviso forniscono informazioni sull'evento inaspettato e recuperabile nel flusso dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | java.lang.String | Il messaggio di avviso. |

