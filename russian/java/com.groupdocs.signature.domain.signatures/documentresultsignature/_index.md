---
title: "DocumentResultSignature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Результат обработки процесса подписи архивного документа для документа с недавно созданными подписями."
type: docs
weight: 13
url: /ru/java/com.groupdocs.signature.domain.signatures/documentresultsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DocumentResultSignature extends BaseSignature
```

Результат обработки процесса подписи архивного документа для документа с недавно созданными подписями.

## Методы

| Метод | Описание |
| --- | --- |
|  | [getFileName()](#getFileName--) | Имя файла документа |
|
|  | [getProcessingTime()](#getProcessingTime--) | Возвращает время выполнения процесса в миллисекундах |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Возвращает общее количество обработанных подписей |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Возвращает размер исходного документа |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Возвращает размер целевого документа |
|
|  | [getSucceeded()](#getSucceeded--) | Список успешно обработанных подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Список подписей, которые не удалось обработать во время процесса [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getErrorMessage()](#getErrorMessage--) | Если документ был обработан с ошибкой, это свойство будет содержать сообщение об ошибке |
|
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Имя файла документа


**Returns:**
java.lang.String
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


Список успешно обработанных подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Список подписей, которые не удалось обработать во время процесса [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getErrorMessage() {#getErrorMessage--}
```
public final String getErrorMessage()
```


Если документ был обработан с ошибкой, это свойство будет содержать сообщение об ошибке


**Returns:**
java.lang.String
