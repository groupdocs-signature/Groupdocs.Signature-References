---
title: "ConsoleLogger"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Escribe mensajes de registro en el archivo."
type: docs
weight: 10
url: /es/java/com.groupdocs.signature.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Escribe mensajes de registro en el archivo.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ConsoleLogger()](#ConsoleLogger--) | Crear logger en la consola. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Escribe un mensaje de error en la consola. |
|
|  | [trace(String message)](#trace-java.lang.String-) | Escribe un mensaje de traza en la consola. |
|
|  | [warning(String message)](#warning-java.lang.String-) | Escribe un mensaje de advertencia en la consola; |
Los mensajes de registro de advertencia proporcionan información sobre eventos inesperados y recuperables en el flujo de la aplicación.
|
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


Crear logger en la consola.


### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Escribe un mensaje de error en la consola.
Los mensajes de registro de error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | message | java.lang.String | El mensaje de error. |
|
|  | excepción | java.lang.Exception | La excepción. |
|

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Escribe un mensaje de traza en la consola.
Los mensajes de registro de traza proporcionan información generalmente útil sobre el flujo de la aplicación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | message | java.lang.String | El mensaje de traza. |
|

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Escribe un mensaje de advertencia en la consola;
Los mensajes de registro de advertencia proporcionan información sobre eventos inesperados y recuperables en el flujo de la aplicación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | message | java.lang.String | El mensaje de advertencia. |
|

