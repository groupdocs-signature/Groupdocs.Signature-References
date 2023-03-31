---
title: FileLogger
second_title: GroupDocs.Signature for Java API Reference
description: Writes log messages to the file.
type: docs
weight: 11
url: /java/com.groupdocs.signature.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class FileLogger implements ILogger
```

Writes log messages to the file.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Create logger to file. |
## Methods

| Method | Description |
| --- | --- |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Writes an error message to the console. |
| [trace(String message)](#trace-java.lang.String-) | Writes trace message to the console. |
| [warning(String message)](#warning-java.lang.String-) | Writes warning message to the console; Warning log messages provide information about the unexpected and recoverable event in application flow. |
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Create logger to file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Full file name with path |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Writes an error message to the console. Error log messages provide information about unrecoverable events in application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The error message. |
| exception | java.lang.Exception | The exception. |

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Writes trace message to the console. Trace log messages provide generally useful information about application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The trace message. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Writes warning message to the console; Warning log messages provide information about the unexpected and recoverable event in application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The warning message. |

