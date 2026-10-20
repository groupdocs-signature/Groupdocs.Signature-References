---
title: "BaseSignature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Описывает базовый класс для подписей."
type: docs
weight: 11
url: /ru/java/com.groupdocs.signature.domain.signatures/basesignature/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseSignature
```

Описывает базовый класс для подписей.

## Методы

| Метод | Описание |
| --- | --- |
|  | [getSignatureType()](#getSignatureType--) | Указывает тип подписи. |
|
|  | [getPageNumber()](#getPageNumber--) | Указывает страницу, на которой была найдена подпись. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Указывает страницу, на которой была найдена подпись. |
|
|  | [getSignatureId()](#getSignatureId--) | Уникальный идентификатор подписи для изменения подписи в документе с помощью методов Update или Delete. |
|
|  | [isSignature()](#isSignature--) | Получить или установить флаг, указывающий, является ли этот компонент подписью или содержимым документа. |
|
|  | [setSignature(boolean value)](#setSignature-boolean-) | Получить или установить флаг, указывающий, является ли этот компонент подписью или содержимым документа. |
|
|  | [getDeleted()](#getDeleted--) | Получить или установить флаг, указывающий, была ли эта подпись удалена из документа. |
|
|  | [getCreatedOn()](#getCreatedOn--) | Получить или установить дату создания подписи. |
|
|  | [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | Получить или установить дату создания подписи. |
|
|  | [getModifiedOn()](#getModifiedOn--) | Получить или установить дату изменения подписи. |
|
|  | [setModifiedOn(Date value)](#setModifiedOn-java.util.Date-) | Получить или установить дату изменения подписи. |
|
|  | [getTop()](#getTop--) | Указывает верхнюю позицию подписи. |
|
|  | [setTop(int value)](#setTop-int-) | Указывает верхнюю позицию подписи. |
|
|  | [getLeft()](#getLeft--) | Указывает левую позицию подписи. |
|
|  | [setLeft(int value)](#setLeft-int-) | Указывает левую позицию подписи. |
|
|  | [getWidth()](#getWidth--) | Указывает ширину подписи. |
|
|  | [setWidth(int value)](#setWidth-int-) | Указывает ширину подписи. |
|
|  | [getHeight()](#getHeight--) | Указывает высоту подписи. |
|
|  | [setHeight(int value)](#setHeight-int-) | Указывает высоту подписи. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Переопределяет метод Equals для сравнения свойств подписи |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
| [supportMetaInfoLayer()](#supportMetaInfoLayer--) |  |
|  | [toString()](#toString--) | <br /> |

|
### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Указывает тип подписи. Цифровая подпись будет иметь это свойство.


**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Указывает страницу, на которой была найдена подпись.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Указывает страницу, на которой была найдена подпись.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Integer |  |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Уникальный идентификатор подписи для изменения подписи в документе с помощью методов Update или Delete.
Это свойство будет установлено автоматически после вызова метода Sign или Search.
Если это свойство было сохранено ранее, его можно установить вручную для манипуляции подписью.


**Returns:**
java.lang.String
### isSignature() {#isSignature--}
```
public final boolean isSignature()
```


Получить или установить флаг, указывающий, является ли этот компонент подписью или содержимым документа.
Это свойство используется методом Update для установки элемента как подписи (true) или элемента документа (false).


**Returns:**
boolean
### setSignature(boolean value) {#setSignature-boolean-}
```
public final void setSignature(boolean value)
```


Получить или установить флаг, указывающий, является ли этот компонент подписью или содержимым документа.
Это свойство используется методом Update для установки элемента как подписи (true) или элемента документа (false).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


Получить или установить флаг, указывающий, была ли эта подпись удалена из документа.
Это свойство используется только для записей журнала истории документа, чтобы хранить список удалённых подписей.


**Returns:**
boolean
### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


Получить или установить дату создания подписи.


**Returns:**
java.util.Date
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


Получить или установить дату создания подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Date |  |

### getModifiedOn() {#getModifiedOn--}
```
public final Date getModifiedOn()
```


Получить или установить дату изменения подписи.


**Returns:**
java.util.Date
### setModifiedOn(Date value) {#setModifiedOn-java.util.Date-}
```
public final void setModifiedOn(Date value)
```


Получить или установить дату изменения подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Date |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Указывает верхнюю позицию подписи.


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Указывает верхнюю позицию подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Указывает левую позицию подписи.


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Указывает левую позицию подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Указывает ширину подписи.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Указывает ширину подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Указывает высоту подписи.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Указывает высоту подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Переопределяет метод Equals для сравнения свойств подписи


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | подпись | java.lang.Object | Объект подписи для сравнения. |
|

**Returns:**
boolean — Возвращает true, если переданный объект подписи имеет тот же тип и все его свойства равны свойствам этого экземпляра.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Переопределяет метод GetHashCode


**Returns:**
int -
### supportMetaInfoLayer() {#supportMetaInfoLayer--}
```
public boolean supportMetaInfoLayer()
```




**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String -
