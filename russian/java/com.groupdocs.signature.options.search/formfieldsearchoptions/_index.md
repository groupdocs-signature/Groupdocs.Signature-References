---
title: "FormFieldSearchOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет абстрактные параметры поиска для подписей полей формы."
type: docs
weight: 13
url: /ru/java/com.groupdocs.signature.options.search/formfieldsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class FormFieldSearchOptions extends SearchOptions
```

Представляет абстрактные параметры поиска для подписей полей формы.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [FormFieldSearchOptions()](#FormFieldSearchOptions--) | Инициализирует новый экземпляр класса SearchFormFieldOptions со значениями по умолчанию. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getType()](#getType--) | Указывает тип подписи поля формы, если его следует искать. |
|
|  | [setType(Integer value)](#setType-java.lang.Integer-) | Указывает тип подписи поля формы, если его следует искать. |
|
|  | [getName()](#getName--) | Указывает шаблон регулярного выражения имени подписи поля формы, если его следует искать. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Указывает шаблон регулярного выражения имени подписи поля формы, если его следует искать. |
|
|  | [getValue()](#getValue--) | Указывает значение подписи поля формы, если его следует искать. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Указывает значение подписи поля формы, если его следует искать. |
|
### FormFieldSearchOptions() {#FormFieldSearchOptions--}
```
public FormFieldSearchOptions()
```


Инициализирует новый экземпляр класса SearchFormFieldOptions со значениями по умолчанию.


### getType() {#getType--}
```
public final Integer getType()
```


Указывает тип подписи поля формы, если его следует искать. Значение по умолчанию — null.


**Returns:**
java.lang.Integer
### setType(Integer value) {#setType-java.lang.Integer-}
```
public final void setType(Integer value)
```


Указывает тип подписи поля формы, если его следует искать. Значение по умолчанию — null.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Integer |  |

### getName() {#getName--}
```
public final String getName()
```


Указывает шаблон регулярного выражения имени подписи поля формы, если его следует искать.
Можно использовать его просто как "text" или регулярное выражение, например "abc\\d+". Значение по умолчанию — пустая строка.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Указывает шаблон регулярного выражения имени подписи поля формы, если его следует искать.
Можно использовать его просто как "text" или регулярное выражение, например "abc\\d+". Значение по умолчанию — пустая строка.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Указывает значение подписи поля формы, если его следует искать. Значение по умолчанию — null.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Указывает значение подписи поля формы, если его следует искать. Значение по умолчанию — null.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

