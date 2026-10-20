---
title: "SignResult"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Результат процесса подписания документа с новыми подписями."
type: docs
weight: 17
url: /ru/java/com.groupdocs.signature.domain/signresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class SignResult implements IResult
```

Результат процесса подписания документа с новыми подписями.

## Методы

| Метод | Описание |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Возвращает время выполнения процесса в миллисекундах |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Возвращает общее количество обработанных подписей |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Возвращает размер исходного документа |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Возвращает размер целевого документа |
|
|  | [getSucceeded()](#getSucceeded--) | Список недавно созданных подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Список подписей, создание которых не удалось. |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Возвращает время выполнения процесса в миллисекундах


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Возвращает общее количество обработанных подписей


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Возвращает размер исходного документа


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Возвращает размер целевого документа


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Список недавно созданных подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Список подписей, создание которых не удалось.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
