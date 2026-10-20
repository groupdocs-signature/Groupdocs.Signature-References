---
title: "ProcessCompleteEventArgs"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Предоставляет данные о событии завершения процессов проверки подписи и поиска."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

Предоставляет данные о завершении процессов подписания, проверки и поиска.

## Методы

| Метод | Описание |
| --- | --- |
|  | [getCompleted()](#getCompleted--) | Представляет отметку времени завершения процесса. |
|
|  | [setCompleted(Date value)](#setCompleted-java.util.Date-) | Представляет отметку времени завершения процесса. |
|
|  | [getTicks()](#getTicks--) | Представляет время в миллисекундах, затраченное с момента события начала процесса. |
|
|  | [setTicks(long value)](#setTicks-long-) | Представляет время в миллисекундах, затраченное с момента события начала процесса. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Представляет общее количество обработанных подписей. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | Представляет общее количество обработанных подписей. |
|
|  | [getCanceled()](#getCanceled--) | Указывает, был ли процесс отменён. |
|
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


Представляет отметку времени завершения процесса.


**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


Представляет отметку времени завершения процесса.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Представляет время в миллисекундах, затраченное с момента события начала процесса.


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Представляет время в миллисекундах, затраченное с момента события начала процесса.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Представляет общее количество обработанных подписей.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Представляет общее количество обработанных подписей.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


Указывает, был ли процесс отменён.


**Returns:**
boolean
