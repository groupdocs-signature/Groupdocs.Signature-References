---
title: "TextSearchOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет параметры поиска для текстовых подписей."
type: docs
weight: 18
url: /ru/java/com.groupdocs.signature.options.search/textsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class TextSearchOptions extends SearchOptions
```

Представляет параметры поиска для текстовых подписей.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [TextSearchOptions()](#TextSearchOptions--) | Инициализирует новый экземпляр класса TextSearchOptions со значениями по умолчанию. |
|
|  | [TextSearchOptions(String text)](#TextSearchOptions-java.lang.String-) | Инициализирует новый экземпляр класса TextSearchOptions со значением текста. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getText()](#getText--) | Указывает текст подписи для сопоставления при поиске. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Указывает текст подписи для сопоставления при поиске. |
|
|  | [getMatchType()](#getMatchType--) | Получает или задает тип сопоставления текста при поиске. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Получает или задает тип сопоставления текста при поиске. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Указывает реализацию текстовой подписи для поиска. |
|
|  | [setSignatureImplementation(Integer value)](#setSignatureImplementation-java.lang.Integer-) | Указывает реализацию текстовой подписи для поиска. |
|
### TextSearchOptions() {#TextSearchOptions--}
```
public TextSearchOptions()
```


Инициализирует новый экземпляр класса TextSearchOptions со значениями по умолчанию.


### TextSearchOptions(String text) {#TextSearchOptions-java.lang.String-}
```
public TextSearchOptions(String text)
```


Инициализирует новый экземпляр класса TextSearchOptions со значением текста.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | текст | java.lang.String | Установить текст текстовой подписи. |
|

### getText() {#getText--}
```
public final String getText()
```


Указывает текст подписи для сопоставления при поиске.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Указывает текст подписи для сопоставления при поиске.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Получает или задает тип сопоставления текста при поиске.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Получает или задает тип сопоставления текста при поиске.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final Integer getSignatureImplementation()
```


Указывает реализацию текстовой подписи для поиска.


**Returns:**
java.lang.Integer
### setSignatureImplementation(Integer value) {#setSignatureImplementation-java.lang.Integer-}
```
public final void setSignatureImplementation(Integer value)
```


Указывает реализацию текстовой подписи для поиска.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Integer |  |

