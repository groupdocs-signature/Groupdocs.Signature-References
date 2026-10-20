---
title: "ProcessLog"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет детали процесса документа."
type: docs
weight: 15
url: /ru/java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

Представляет детали процесса документа.

## Методы

| Метод | Описание |
| --- | --- |
|  | [getDate()](#getDate--) | Получить дату и время процесса. |
|
|  | [getType()](#getType--) | Получить тип процесса. |
|
|  | [getMessage()](#getMessage--) | Получить описание процесса. |
|
|  | [getSucceeded()](#getSucceeded--) | Количество успешно обработанных подписей. |
|
|  | [getFailed()](#getFailed--) | Количество подписей, которые не прошли обработку. |
|
|  | [getSignatures()](#getSignatures--) | Список успешно обработанных подписей. |
|
### getDate() {#getDate--}
```
public final Date getDate()
```


Получить дату и время процесса.


**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


Получить тип процесса.


**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


Получить описание процесса.


**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


Количество успешно обработанных подписей.


**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


Количество подписей, которые не прошли обработку.


**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Список успешно обработанных подписей.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
