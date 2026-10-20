---
title: "TextSignature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Содержит свойства текстовой подписи."
type: docs
weight: 18
url: /ru/java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

Содержит свойства текстовой подписи.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | Инициализировать объект TextSignature с идентификатором подписи, полученным после процесса поиска. |
|
| [TextSignature()](#TextSignature--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getText()](#getText--) | Указывает текст в подписи. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Указывает текст в подписи. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Указывает реализацию текстовой подписи. |
|
|  | [getNative()](#getNative--) | Указывает собственный атрибут. |
|
|  | [setNative(boolean value)](#setNative-boolean-) | Указывает собственный атрибут. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Переопределяет метод Equals для сравнения свойств подписи |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
|  | [deepClone()](#deepClone--) | Клонировать экземпляр текстовой подписи. |
|
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


Инициализировать объект TextSignature с идентификатором подписи, полученным после процесса поиска.
Этот уникальный идентификатор используется для поиска дополнительных свойств этой подписи в слое информации о подписи документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | signatureId | java.lang.String | Уникальный идентификатор подписи, полученный методом подписи или поиска. |
|

### TextSignature() {#TextSignature--}
```
public TextSignature()
```


### getText() {#getText--}
```
public final String getText()
```


Указывает текст в подписи.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Указывает текст в подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Указывает реализацию текстовой подписи.


**Returns:**
int
### getNative() {#getNative--}
```
public final boolean getNative()
```


Указывает собственный атрибут. Истинно, если подпись специфична для документа.


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Указывает собственный атрибут. Истинно, если подпись специфична для документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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


Клонировать экземпляр текстовой подписи.


**Returns:**
java.lang.Object - Возвращает клонированный экземпляр текстовой подписи.

