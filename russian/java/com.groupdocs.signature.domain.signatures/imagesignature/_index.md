---
title: "ImageSignature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Содержит свойства подписи изображения."
type: docs
weight: 14
url: /ru/java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

Содержит свойства подписи изображения.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | Инициализировать объект ImageSignature с идентификатором подписи, полученным после процесса поиска. |
|
|  | [ImageSignature()](#ImageSignature--) | Инициализировать ImageSignature с параметрами по умолчанию. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getSize()](#getSize--) | Указывает размер изображения подписи в байтах. |
|
|  | [setSize(int value)](#setSize-int-) | Указывает размер изображения подписи в байтах. |
|
|  | [getFormat()](#getFormat--) | Указывает формат изображения подписи. |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | Указывает формат изображения подписи. |
|
|  | [getContent()](#getContent--) | Указывает двоичные данные изображения типа |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Переопределяет метод Equals для сравнения свойств подписи |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
|  | [deepClone()](#deepClone--) | Создать копию экземпляра подписи штрих‑кода. |
|
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


Инициализировать объект ImageSignature с идентификатором подписи, полученным после процесса поиска.
Этот уникальный идентификатор используется для поиска дополнительных свойств этой подписи в слое информации о подписи документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | signatureId | java.lang.String | Уникальный идентификатор подписи, полученный методом Sign или Search класса Signature [Signature](../../com.groupdocs.signature/signature). |
|

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


Инициализировать ImageSignature с параметрами по умолчанию.


### getSize() {#getSize--}
```
public final int getSize()
```


Указывает размер изображения подписи в байтах.


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Указывает размер изображения подписи в байтах.



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Указывает формат изображения подписи.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFormat(FileType value)
```


Указывает формат изображения подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getContent() {#getContent--}
```
public final byte[] getContent()
```


Указывает двоичные данные изображения типа
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
По умолчанию это свойство не будет установлено.
Использовать свойство
ImageSearchOptions.ReturnContent
({ ImageSearchOptions#getReturnContent}/{ ImageSearchOptions#setReturnContent(boolean)}) чтобы включить эту функцию.


**Returns:**
byte[]
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
int — Хеш‑код подписи

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создать копию экземпляра подписи штрих‑кода.


**Returns:**
java.lang.Object - Возвращает клонированный экземпляр подписи штрих‑кода.

