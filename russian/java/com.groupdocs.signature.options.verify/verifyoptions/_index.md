---
title: "VerifyOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Сохраняет параметры для проверки документа."
type: docs
weight: 15
url: /ru/java/com.groupdocs.signature.options.verify/verifyoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class VerifyOptions
```

Сохраняет параметры для проверки документа.

## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid()](#isValid--) | Флаг действительного свойства. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Флаг действительного свойства. |
|
|  | [getPageNumber()](#getPageNumber--) | Номер страницы документа для проверки. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Номер страницы документа для проверки. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Параметры страниц для указания страниц, подлежащих проверке. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Параметры страниц для указания страниц, подлежащих проверке. |
|
|  | [getAllPages()](#getAllPages--) | Флаг для проверки каждой страницы документа. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Флаг для проверки каждой страницы документа. |
|
|  | [getExtensions()](#getExtensions--) | Дополнительные расширения для проверки альтернативных параметров подписи. |
|
|  | [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | Дополнительные расширения для проверки альтернативных параметров подписи. |
|
|  | [toString()](#toString--) | Переопределить преобразование строки. |
|
### isValid() {#isValid--}
```
public final boolean isValid()
```


Флаг действительного свойства.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Флаг действительного свойства.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Номер страницы документа для проверки. Если свойство не установлено — все страницы
Документ будет проверен при первом вхождении.
Минимальное значение равно 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


Номер страницы документа для проверки. Если свойство не установлено — все страницы
Документ будет проверен при первом вхождении.
Минимальное значение равно 1.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Параметры страниц для указания страниц, подлежащих проверке.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Параметры страниц для указания страниц, подлежащих проверке.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Флаг для проверки каждой страницы документа. По умолчанию значение истинно.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Флаг для проверки каждой страницы документа. По умолчанию значение истинно.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


Дополнительные расширения для проверки альтернативных параметров подписи.


**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


Дополнительные расширения для проверки альтернативных параметров подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


Переопределить преобразование строки.


**Returns:**
java.lang.String -
