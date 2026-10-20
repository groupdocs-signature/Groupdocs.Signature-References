---
title: "DeleteResult"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Результат удаления подписей из документа."
type: docs
weight: 12
url: /ru/java/com.groupdocs.signature.domain/deleteresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class DeleteResult implements IResult
```

Результат удаления подписи(й) из документа.

## Методы

| Метод | Описание |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Возвращает время выполнения процесса в миллисекундах. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Возвращает общее количество обработанных подписей. |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Возвращает размер исходного документа. |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Возвращает размер обновлённого документа. |
|
|  | [getSucceeded()](#getSucceeded--) | Список успешно удалённых подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Список подписей, которые не были удалены [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Возвращает время выполнения процесса в миллисекундах.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Возвращает общее количество обработанных подписей.


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Возвращает размер исходного документа.


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Возвращает размер обновлённого документа.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Список успешно удалённых подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Список подписей, которые не были удалены [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
