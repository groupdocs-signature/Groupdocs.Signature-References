---
title: "CheckboxFormFieldSignature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Содержит свойства подписи поля формы ввода чек-бокса."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

Содержит свойства подписи поля формы ввода чек-бокса.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | Создаёт PdfCheckboxFormFieldSignature с предопределённым именем. |
|
|  | [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | Создаёт PdfCheckboxFormFieldSignature с предопределённым именем и значением |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getChecked()](#getChecked--) | Получает или задаёт отмеченное значение поля формы типа чек-бокс. |
|
|  | [setChecked(boolean value)](#setChecked-boolean-) | Получает или задаёт отмеченное значение поля формы типа чек-бокс. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Переопределяет метод Equals для сравнения свойств подписи |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
|  | [deepClone()](#deepClone--) | Клонирует экземпляр FormField Signature. |
|
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


Создаёт PdfCheckboxFormFieldSignature с предопределённым именем.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя объекта поля формы. |
|

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


Создаёт PdfCheckboxFormFieldSignature с предопределённым именем и значением


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя объекта поля формы. |
|
|  | isChecked | boolean | Значение, если чек-бокс отмечен |
|

### getChecked() {#getChecked--}
```
public final boolean getChecked()
```


Получает или задаёт отмеченное значение поля формы типа чек-бокс.


**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public final void setChecked(boolean value)
```


Получает или задаёт отмеченное значение поля формы типа чек-бокс.


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


Клонирует экземпляр FormField Signature.


**Returns:**
java.lang.Object — Возвращает клонированный экземпляр FormField Signature.

