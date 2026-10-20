---
title: "StampTypes"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Контейнер типов штампов."
type: docs
weight: 16
url: /ru/java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

Контейнер типов штампов.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## Поля

| Поле | Описание |
| --- | --- |
|  | [Round](#Round) | Объект типа круглой печати. |
|
|  | [Square](#Square) | Объект типа квадратной печати. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Все типы печатей. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | Возвращает тип штампа с именем pasringType. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | Возвращает тип штампа с именем pasringType. |
|
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


Объект типа круглой печати.


### Square {#Square}
```
public static final StampType Square
```


Объект типа квадратной печати.


### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


Все типы печатей.


**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


Возвращает тип штампа с именем pasringType. Когда имя штампа неизвестно — выбрасывается исключение.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | parsingType | java.lang.String | Исходная строка имени типа штампа. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


Возвращает тип штампа с именем pasringType. Когда имя штампа неизвестно — исключение не выбрасывается, и метод возвращает значение null.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | parsingType | java.lang.String | Исходная строка имени типа штампа. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

