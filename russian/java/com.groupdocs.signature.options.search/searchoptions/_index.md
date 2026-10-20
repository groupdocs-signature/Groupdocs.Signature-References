---
title: "SearchOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет параметры извлечения подписей из документа."
type: docs
weight: 17
url: /ru/java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)
```
public abstract class SearchOptions extends OptionsExtensions
```

Представляет параметры извлечения подписей из документа.

## Методы

| Метод | Описание |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Получает или задает номер страницы документа для поиска. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Получает или задает номер страницы документа для поиска. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Опции для указания страниц для поиска подписи. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Опции для указания страниц для поиска подписи. |
|
|  | [getAllPages()](#getAllPages--) | Флаг для поиска на каждой странице документа. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Флаг для поиска на каждой странице документа. |
|
|  | [getSkipExternal()](#getSkipExternal--) | Флаг для возврата только подписей, помеченных как IsSignature. |
|
|  | [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | Флаг для возврата только подписей, помеченных как IsSignature. |
|
|  | [getSearchPages(int totalPages)](#getSearchPages-int-) | Виртуальный метод для получения списка страниц для извлечения подписи. |
|
|  | [toString()](#toString--) | Переопределить преобразование строки. |
|
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Получает или задает номер страницы документа для поиска.
Значение является необязательным.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Получает или задает номер страницы документа для поиска.
Значение является необязательным.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Опции для указания страниц для поиска подписи.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Опции для указания страниц для поиска подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Флаг для поиска на каждой странице документа. По умолчанию это значение установлено в true.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Флаг для поиска на каждой странице документа. По умолчанию это значение установлено в true.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


Флаг для возврата только подписей, помеченных как IsSignature. По умолчанию значение false, что означает возврат всех подписей, соответствующих указанным критериям.


**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


Флаг для возврата только подписей, помеченных как IsSignature. По умолчанию значение false, что означает возврат всех подписей, соответствующих указанным критериям.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


Виртуальный метод для получения списка страниц для извлечения подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | totalPages | int | Общее количество страниц |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Список номеров страниц

### toString() {#toString--}
```
public String toString()
```


Переопределить преобразование строки.


**Returns:**
java.lang.String -
