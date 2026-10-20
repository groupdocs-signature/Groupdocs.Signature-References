---
title: "SearchResult"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Результат поиска подписей в указанном документе."
type: docs
weight: 16
url: /ru/java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

Результат поиска подписей в указанном документе.

## Методы

| Метод | Описание |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Возвращает время выполнения процесса поиска в миллисекундах. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Возвращает общее количество обработанных подписей процессом поиска |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Возвращает размер исходного документа |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Возвращает размер целевого документа. |
|
|  | [getSucceeded()](#getSucceeded--) | Список найденных подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Список подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), которые не прошли процесс поиска по критериям. |
|
|  | [getSignatures()](#getSignatures--) | Список обнаруженных подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | Обеспечивает преобразование в строго типизированный список подписей. |
|
| [updateContextData(SearchContext context, int documentType)](#updateContextData-com.groupdocs.signature.provider.SearchContext-int-) |  |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Возвращает время выполнения процесса поиска в миллисекундах.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Возвращает общее количество обработанных подписей процессом поиска


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


Возвращает размер целевого документа. Для метода Search он всегда возвращает 0.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Список найденных подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Этот список всегда будет равен
Подписи
(#getSignatures.getSignatures/#setSignatures(List).setSignatures(List)) свойство.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Список подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), которые не прошли процесс поиска по критериям.
Не поддерживается в текущей версии.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Список обнаруженных подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### <T>toList(Class<T> typeOfT) {#-T-toList-java.lang.Class-T--}
```
public final List<T> <T>toList(Class<T> typeOfT)
```


Обеспечивает преобразование в строго типизированный список подписей.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Возвращает список заданного типа подписи.


T
: Тип подписей в списке.

### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

