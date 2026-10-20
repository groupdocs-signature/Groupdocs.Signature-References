---
title: "ComboboxFormFieldSignature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Содержит свойства подписи поля формы ввода комбобокса."
type: docs
weight: 11
url: /ru/java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

Содержит свойства подписи поля формы ввода комбобокса.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | Создаёт ComboboxFormFieldSignature с предопределённым именем. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Создаёт ComboboxFormFieldSignature с предопределённым именем и списком вариантов. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Создаёт ComboboxFormFieldSignature с предопределённым именем, списком вариантов и выбранным значением. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getSelected()](#getSelected--) | Получить или задать выбранное значение. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | Получить или задать выбранное значение. |
|
|  | [getItems()](#getItems--) | Получить или задать список вариантов combo-box. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Получить или задать список вариантов combo-box. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Переопределяет метод Equals для сравнения свойств подписи |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
|  | [deepClone()](#deepClone--) | Клонирует экземпляр FormField Signature. |
|
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


Создаёт ComboboxFormFieldSignature с предопределённым именем.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя объекта поля формы. |
|

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


Создаёт ComboboxFormFieldSignature с предопределённым именем и списком вариантов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя объекта поля формы. |
|
|  | items | java.util.List<java.lang.String> | Значения списка combo-box. |
|

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


Создаёт ComboboxFormFieldSignature с предопределённым именем, списком вариантов и выбранным значением.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя объекта поля формы. |
|
|  | items | java.util.List<java.lang.String> | Значения списка combo-box. |
|
|  | selected | java.lang.Object | Выбранное значение. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Получить или задать выбранное значение.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Получить или задать выбранное значение.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Получить или задать список вариантов combo-box.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Получить или задать список вариантов combo-box.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.List<java.lang.String> |  |

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

