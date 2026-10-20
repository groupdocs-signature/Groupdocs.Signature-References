---
title: "FormFieldSignature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Содержит свойства подписи поля формы."
type: docs
weight: 13
url: /ru/java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class FormFieldSignature extends BaseSignature
```

Содержит свойства подписи поля формы.

## Методы

| Метод | Описание |
| --- | --- |
|  | [getName()](#getName--) | Указывает уникальное имя поля формы. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Указывает уникальное имя поля формы. |
|
|  | [getType()](#getType--) | Указывает тип поля формы. |
|
|  | [getValue()](#getValue--) | Указывает объект данных поля формы. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Указывает объект данных поля формы. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Переопределяет метод Equals для сравнения свойств подписи |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
|  | [deepClone()](#deepClone--) | Клонирует экземпляр FormField Signature. |
|
### getName() {#getName--}
```
public final String getName()
```


Указывает уникальное имя поля формы.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Указывает уникальное имя поля формы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Указывает тип поля формы.


**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


Указывает объект данных поля формы.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Указывает объект данных поля формы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

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


Клонирует экземпляр FormField Signature.


**Returns:**
java.lang.Object — Возвращает клонированный экземпляр FormField Signature.

