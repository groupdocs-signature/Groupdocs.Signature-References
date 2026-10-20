---
title: "FileLogger"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Записывает сообщения журнала в файл."
type: docs
weight: 11
url: /ru/java/com.groupdocs.signature.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class FileLogger implements ILogger
```

Записывает сообщения журнала в файл.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Создать журнал в файл. |
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
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Создать журнал в файл.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileName | java.lang.String | Полное имя файла с путём |
|

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

