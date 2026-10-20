---
title: "FileLogger"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Escribe mensajes de registro en el archivo."
type: docs
weight: 11
url: /es/java/com.groupdocs.signature.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class FileLogger implements ILogger
```

Escribe mensajes de registro en el archivo.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Crear logger en un archivo. |
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
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Crear logger en un archivo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileName | java.lang.String | Nombre completo del archivo con ruta |
|

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

