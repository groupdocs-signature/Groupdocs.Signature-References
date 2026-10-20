---
title: "MetadataSignatureCollection"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Коллекция объектов подписи метаданных."
type: docs
weight: 13
url: /ru/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class MetadataSignatureCollection implements Iterable<MetadataSignature>
```

Коллекция объектов подписи метаданных.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [MetadataSignatureCollection()](#MetadataSignatureCollection--) | Создаёт коллекцию подписи Metadata. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getCount()](#getCount--) | Получает количество элементов в коллекции. |
|
|  | [clear()](#clear--) | Удаляет все элементы из коллекции. |
|
|  | [contains(String name)](#contains-java.lang.String-) | Возвращает true, если в коллекции существует Metadata с указанным именем. |
|
|  | [indexOf(String name)](#indexOf-java.lang.String-) | Получает индекс свойства по имени. |
|
|  | [remove(String name)](#remove-java.lang.String-) | Удаляет Metadata Signature с указанным именем из коллекции. |
|
|  | [removeAt(int index)](#removeAt-int-) | Удаляет Metadata Signature по указанному индексу. |
|
|  | [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Добавляет объект Metadata Signature в коллекцию. |
|
|  | [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | Добавляет коллекцию Metadata Signature. |
|
|  | [deepClone()](#deepClone--) | Клонирует класс Metadata Signature Collection с элементами Metadata Signature. |
|
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


Создаёт коллекцию подписи Metadata.


### getCount() {#getCount--}
```
public final int getCount()
```


Получает количество элементов в коллекции.


**Returns:**
int
### clear() {#clear--}
```
public final void clear()
```


Удаляет все элементы из коллекции.


### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Возвращает true, если в коллекции существует Metadata с указанным именем.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Регистронезависимое имя свойства. |
|

**Returns:**
boolean - True, если Metadata существует в коллекции; иначе false.

### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


Получает индекс свойства по имени.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Регистронезависимое имя MetadataSignature. |
|

**Returns:**
int - Индекс, начинающийся с нуля. Отрицательное значение, если не найден.

### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


Удаляет Metadata Signature с указанным именем из коллекции.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Регистронезависимое имя Metadata Signature. |
|

**Returns:**
boolean -
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


Удаляет Metadata Signature по указанному индексу.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | индекс | int | Индекс, начинающийся с нуля. |
|

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


Добавляет объект Metadata Signature в коллекцию.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Metadata signature, добавляемая в коллекцию. |

<br />

*** ** * ** ***

Выбрасывает исключение, если значение имени не уникально во всей существующей коллекции.

<br />

|

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


Добавляет коллекцию Metadata Signature.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Коллекция сигнатур для добавления. |

<br />

*** ** * ** ***

Выбрасывает исключение, если значение имени не уникально во всей существующей коллекции.

<br />

|

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Клонирует класс Metadata Signature Collection с элементами Metadata Signature.


**Returns:**
java.lang.Object - Возвращает скопированный экземпляр с клонированными элементами Signature.

