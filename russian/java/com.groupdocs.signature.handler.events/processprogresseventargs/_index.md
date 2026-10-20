---
title: "ProcessProgressEventArgs"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Предоставляет данные для события OnProgress процессов проверки подписи и поиска."
type: docs
weight: 13
url: /ru/java/com.groupdocs.signature.handler.events/processprogresseventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessProgressEventArgs extends ProcessEventArgs
```

Предоставляет данные для события OnProgress процессов подписания, проверки и поиска.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ProcessProgressEventArgs()](#ProcessProgressEventArgs--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getProgress()](#getProgress--) | Представляет прогресс в процентах. |
|
|  | [setProgress(int value)](#setProgress-int-) | Представляет прогресс в процентах. |
|
|  | [getTicks()](#getTicks--) | Представляет затраченное время в миллисекундах с момента события Start процесса. |
|
|  | [setTicks(long value)](#setTicks-long-) | Представляет затраченное время в миллисекундах с момента события Start процесса. |
|
|  | [getProcessedSignatures()](#getProcessedSignatures--) | Представляет количество обработанных подписей. |
|
|  | [setProcessedSignatures(int value)](#setProcessedSignatures-int-) | Представляет количество обработанных подписей. |
|
|  | [getCancel()](#getCancel--) | Указывает, следует ли отменить процесс. |
|
|  | [setCancel(boolean value)](#setCancel-boolean-) | Указывает, следует ли отменить процесс. |
|
### ProcessProgressEventArgs() {#ProcessProgressEventArgs--}
```
public ProcessProgressEventArgs()
```


### getProgress() {#getProgress--}
```
public final int getProgress()
```


Представляет прогресс в процентах. Диапазон значений от 0 до 100.


**Returns:**
int
### setProgress(int value) {#setProgress-int-}
```
public final void setProgress(int value)
```


Представляет прогресс в процентах. Диапазон значений от 0 до 100.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Представляет затраченное время в миллисекундах с момента события Start процесса.


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Представляет затраченное время в миллисекундах с момента события Start процесса.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### getProcessedSignatures() {#getProcessedSignatures--}
```
public final int getProcessedSignatures()
```


Представляет количество обработанных подписей.


**Returns:**
int
### setProcessedSignatures(int value) {#setProcessedSignatures-int-}
```
public final void setProcessedSignatures(int value)
```


Представляет количество обработанных подписей.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getCancel() {#getCancel--}
```
public final boolean getCancel()
```


Указывает, следует ли отменить процесс.


**Returns:**
boolean
### setCancel(boolean value) {#setCancel-boolean-}
```
public final void setCancel(boolean value)
```


Указывает, следует ли отменить процесс.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

