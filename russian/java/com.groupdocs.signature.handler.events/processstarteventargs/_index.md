---
title: "ProcessStartEventArgs"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Предоставляет данные для события Start процесса проверки подписи и поиска."
type: docs
weight: 15
url: /ru/java/com.groupdocs.signature.handler.events/processstarteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessStartEventArgs extends ProcessEventArgs
```

Предоставляет данные для события Start процессов подписания, проверки и поиска

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ProcessStartEventArgs()](#ProcessStartEventArgs--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getStarted()](#getStarted--) | Представляет отметку времени начала процесса. |
|
|  | [setStarted(Date value)](#setStarted-java.util.Date-) | Представляет отметку времени начала процесса. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Представляет общее количество подписей, подлежащих обработке. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | Представляет общее количество подписей, подлежащих обработке. |
|
### ProcessStartEventArgs() {#ProcessStartEventArgs--}
```
public ProcessStartEventArgs()
```


### getStarted() {#getStarted--}
```
public final Date getStarted()
```


Представляет отметку времени начала процесса.


**Returns:**
java.util.Date
### setStarted(Date value) {#setStarted-java.util.Date-}
```
public final void setStarted(Date value)
```


Представляет отметку времени начала процесса.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Date |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Представляет общее количество подписей, подлежащих обработке.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Представляет общее количество подписей, подлежащих обработке.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

