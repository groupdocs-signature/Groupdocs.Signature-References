---
title: "TextFormFieldSignature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Содержит свойства подписи поля формы ввода текста для PDF-документа"
type: docs
weight: 15
url: /ru/java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

Содержит свойства подписи поля формы ввода текста для PDF-документа

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | Создает PdfTextFormFieldSignature с предопределенным именем. |
|
|  | [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | Создает PdfTextFormFieldSignature с предопределенным именем. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getText()](#getText--) | Получает или устанавливает текст ввода текстового поля формы. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Получает или устанавливает текст ввода текстового поля формы. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Переопределяет метод Equals для сравнения свойств подписи |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
|  | [deepClone()](#deepClone--) | Клонирует экземпляр FormField Signature. |
|
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


Создает PdfTextFormFieldSignature с предопределенным именем.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя объекта поля формы. |
|

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


Создает PdfTextFormFieldSignature с предопределенным именем.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя объекта поля формы. |
|
|  | текст | java.lang.String | Текст объекта текстового поля формы. |
|

### getText() {#getText--}
```
public final String getText()
```


Получает или устанавливает текст ввода текстового поля формы.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Получает или устанавливает текст ввода текстового поля формы.


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


Клонирует экземпляр FormField Signature.


**Returns:**
java.lang.Object — Возвращает клонированный экземпляр FormField Signature.

