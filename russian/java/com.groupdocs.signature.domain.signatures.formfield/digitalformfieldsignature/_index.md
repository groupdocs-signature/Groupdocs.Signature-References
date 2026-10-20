---
title: "DigitalFormFieldSignature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Содержит свойства подписи поля формы ввода цифровой подписи для PDF-документов."
type: docs
weight: 12
url: /ru/java/com.groupdocs.signature.domain.signatures.formfield/digitalformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class DigitalFormFieldSignature extends FormFieldSignature
```

Содержит свойства подписи поля формы ввода цифровой подписи для PDF-документов.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [DigitalFormFieldSignature(String name)](#DigitalFormFieldSignature-java.lang.String-) | Создаёт PdfDigitalFormFieldSignature с предопределённым именем. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getSigned()](#getSigned--) | Только для чтения свойство, показывающее, был ли Form-field Signature подписан цифровым сертификатом. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Переопределяет метод Equals для сравнения свойств подписи |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
|  | [deepClone()](#deepClone--) | Клонирует экземпляр FormField Signature. |
|
### DigitalFormFieldSignature(String name) {#DigitalFormFieldSignature-java.lang.String-}
```
public DigitalFormFieldSignature(String name)
```


Создаёт PdfDigitalFormFieldSignature с предопределённым именем.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя объекта поля формы. |
|

### getSigned() {#getSigned--}
```
public final boolean getSigned()
```


Только для чтения свойство, показывающее, был ли Form-field Signature подписан цифровым сертификатом.


**Returns:**
boolean
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

