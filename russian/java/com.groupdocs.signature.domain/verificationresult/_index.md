---
title: "VerificationResult"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Экземпляр для хранения результатов процесса проверки."
type: docs
weight: 20
url: /ru/java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

Экземпляр для хранения результатов процесса проверки.

## Методы

| Метод | Описание |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Возвращает время выполнения процесса в миллисекундах. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Возвращает общее количество обработанных подписей |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Возвращает размер исходного документа в байтах |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Возвращает размер целевого документа. |
|
|  | [getSucceeded()](#getSucceeded--) | Список успешно проверенных подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Список подписей, для которых процесс проверки не удался. |
|
|  | [isValid()](#isValid--) | Возвращает true, если процесс проверки был успешным, иначе false. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Возвращает true, если процесс проверки был успешным, иначе false. |
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


Возвращает общее количество обработанных подписей


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Возвращает размер исходного документа в байтах


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Возвращает размер целевого документа. Для проверки эта переменная всегда содержит ноль.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Список успешно проверенных подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).
В настоящее время это свойство не поддерживается.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Список подписей, для которых процесс проверки не удался.
В настоящее время это свойство не поддерживается.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### isValid() {#isValid--}
```
public final boolean isValid()
```


Возвращает true, если процесс проверки был успешным, иначе false.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Возвращает true, если процесс проверки был успешным, иначе false.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

