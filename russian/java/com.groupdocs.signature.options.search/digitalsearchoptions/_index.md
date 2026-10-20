---
title: "DigitalSearchOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет базовые параметры для поиска цифровых подписей."
type: docs
weight: 12
url: /ru/java/com.groupdocs.signature.options.search/digitalsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class DigitalSearchOptions extends SearchOptions
```

Представляет базовые параметры для поиска цифровых подписей.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [DigitalSearchOptions()](#DigitalSearchOptions--) | Инициализирует новый экземпляр класса DigitalSearchOptions со значениями по умолчанию. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getComments()](#getComments--) | Комментарии цифровой подписи для поиска. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Комментарии цифровой подписи для поиска. |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Диапазон даты и времени цифровой подписи для поиска. |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Диапазон даты и времени цифровой подписи для поиска. |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | Диапазон даты и времени цифровой подписи для поиска. |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Диапазон даты и времени цифровой подписи для поиска. |
|
|  | [getSubjectName()](#getSubjectName--) | Для непустых значений указывает отличительное имя субъекта сертификата для поиска. |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Для непустых значений указывает отличительное имя субъекта сертификата для поиска. |
|
|  | [getIssuerName()](#getIssuerName--) | Для непустых значений указывает отличительное имя издателя сертификата для поиска. |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Для непустых значений указывает отличительное имя издателя сертификата для поиска. |
|
### DigitalSearchOptions() {#DigitalSearchOptions--}
```
public DigitalSearchOptions()
```


Инициализирует новый экземпляр класса DigitalSearchOptions со значениями по умолчанию.


### getComments() {#getComments--}
```
public final String getComments()
```


Комментарии цифровой подписи для поиска.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Комментарии цифровой подписи для поиска.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public final Date getSignDateTimeFrom()
```


Диапазон даты и времени цифровой подписи для поиска. Значения null будут игнорироваться.


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public final void setSignDateTimeFrom(Date value)
```


Диапазон даты и времени цифровой подписи для поиска. Значения null будут игнорироваться.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public final Date getSignDateTimeTo()
```


Диапазон даты и времени цифровой подписи для поиска. Значения null будут игнорироваться.


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public final void setSignDateTimeTo(Date value)
```


Диапазон даты и времени цифровой подписи для поиска. Значения null будут игнорироваться.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Date |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Для непустых значений указывает отличительное имя субъекта сертификата для поиска.


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Для непустых значений указывает отличительное имя субъекта сертификата для поиска.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Для непустых значений указывает отличительное имя издателя сертификата для поиска.


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Для непустых значений указывает отличительное имя издателя сертификата для поиска.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

