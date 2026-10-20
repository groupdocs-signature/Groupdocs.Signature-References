---
title: "PdfMetadataSignature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Содержит свойства подписи метаданных PDF."
type: docs
weight: 14
url: /ru/java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

Содержит свойства подписи метаданных PDF.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | Создаёт подпись Pdf Metadata с предопределённым именем и пустым значением |
|
|  | [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | Создаёт подпись Pdf Metadata с предопределёнными значениями |
|
|  | [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | Создаёт подпись Pdf Metadata с предопределёнными значениями |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getTagPrefix()](#getTagPrefix--) | Префиксный тег имени подписи Pdf Metadata. |
|
|  | [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | Префиксный тег имени подписи Pdf Metadata. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Переопределяет метод Equals для сравнения свойств подписи |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
|  | [deepClone()](#deepClone--) | Клонировать экземпляр Metadata Signature. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Клонировать экземпляр Pdf Metadata Signature с заданным значением. |
|
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


Создаёт подпись Pdf Metadata с предопределённым именем и пустым значением


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя подписи Pdf Metadata Signature |
|

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


Создаёт подпись Pdf Metadata с предопределёнными значениями


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя объекта подписи Metadata. |
|
|  | значение | java.lang.Object | Значение подписи Metadata. |
|

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


Создаёт подпись Pdf Metadata с предопределёнными значениями


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя объекта подписи Metadata. |
|
|  | значение | java.lang.Object | Значение подписи Metadata. |
|
|  | tag | java.lang.String | Префиксный тег подписи Metadata. |
|

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


Префиксный тег имени подписи Pdf Metadata. По умолчанию это свойство установлено в "xmp".
Возможные значения:


**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


Префиксный тег имени подписи Pdf Metadata. По умолчанию это свойство установлено в "xmp".
Возможные значения:


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

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


Клонировать экземпляр Metadata Signature.


**Returns:**
java.lang.Object — Возвращает клонированный экземпляр Metadata Signature

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Клонировать экземпляр Pdf Metadata Signature с заданным значением.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.Object | Значение для нового клонированного объекта. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

