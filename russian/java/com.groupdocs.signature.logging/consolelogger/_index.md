---
title: "ConsoleLogger"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Записывает сообщения журнала в файл."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Записывает сообщения журнала в файл.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [ConsoleLogger()](#ConsoleLogger--) | Создать логгер в консоль. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Записывает сообщение об ошибке в консоль. |
|
|  | [trace(String message)](#trace-java.lang.String-) | Записывает трассировочное сообщение в консоль. |
|
|  | [warning(String message)](#warning-java.lang.String-) | Записывает предупреждающее сообщение в консоль; |
Предупреждающие сообщения журнала предоставляют информацию о непредвиденных и восстанавливаемых событиях в потоке приложения.
|
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


Создать логгер в консоль.


### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Записывает сообщение об ошибке в консоль.
Сообщения об ошибках журнала предоставляют информацию о невосстанавливаемых событиях в потоке приложения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Сообщение об ошибке. |
|
|  | исключение | java.lang.Exception | Исключение. |
|

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Записывает трассировочное сообщение в консоль.
Сообщения трассировки журнала обычно предоставляют полезную информацию о ходе работы приложения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Сообщение трассировки. |
|

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Записывает предупреждающее сообщение в консоль;
Предупреждающие сообщения журнала предоставляют информацию о непредвиденных и восстанавливаемых событиях в потоке приложения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Сообщение предупреждения. |
|

