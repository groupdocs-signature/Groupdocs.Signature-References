---
title: ILogger
second_title: GroupDocs.Signature for Java API Reference
description: Defines the methods that are used to perform logging.
type: docs
weight: 13
url: /java/com.groupdocs.signature.logging/ilogger/
---```
public interface ILogger
```

Defines the methods that are used to perform logging.
## Methods

| Method | Description |
| --- | --- |
| [error(String message, Exception ex)](#error-java.lang.String-java.lang.Exception-) | Writes error log message; Error log messages provides information about unrecoverable events in application flow. |
| [trace(String message)](#trace-java.lang.String-) | Writes a trace message. |
| [warning(String message)](#warning-java.lang.String-) | Writes warning log message; Warning log messages provides information about unexpected and recoverable event in application flow. |
### error(String message, Exception ex) {#error-java.lang.String-java.lang.Exception-}
```
public abstract void error(String message, Exception ex)
```


Writes error log message; Error log messages provides information about unrecoverable events in application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The error message. |
| ex | java.lang.Exception | The exception. |

### trace(String message) {#trace-java.lang.String-}
```
public abstract void trace(String message)
```


Writes a trace message. Trace log messages provide generally useful information about application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The trace message. |

### warning(String message) {#warning-java.lang.String-}
```
public abstract void warning(String message)
```


Writes warning log message; Warning log messages provides information about unexpected and recoverable event in application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The warning message. |

