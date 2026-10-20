---
title: "PreviewOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет параметры предварительного просмотра документа."
type: docs
weight: 11
url: /ru/java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Представляет параметры предварительного просмотра документа.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | Инициализирует объект PreviewOptions. |
|
|  | [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | Инициализирует объект PreviewOptions. |
|
|  | [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | Инициализирует объект PreviewOptions. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getWidth()](#getWidth--) | Получает или устанавливает ширину изображений предварительного просмотра. |
|
|  | [setWidth(int value)](#setWidth-int-) | Получает или устанавливает ширину изображений предварительного просмотра. |
|
|  | [getHeight()](#getHeight--) | Получает или устанавливает высоту изображений предварительного просмотра. |
|
|  | [setHeight(int value)](#setHeight-int-) | Получает или устанавливает высоту изображений предварительного просмотра. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Получает или устанавливает номера страниц изображений предварительного просмотра. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Получает или устанавливает номера страниц изображений предварительного просмотра. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Получает или задает формат изображений предварительного просмотра. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Получает или задает формат изображений предварительного просмотра. |
|
|  | [getHideSignatures()](#getHideSignatures--) | Получает или устанавливает флаг скрытия подписей на изображении предварительного просмотра страницы. |
|
|  | [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | Получает или устанавливает флаг скрытия подписей на изображении предварительного просмотра страницы. |
|
|  | [getResolution()](#getResolution--) | Получает разрешение изображений предварительного просмотра в DPI (точек на дюйм). |
|
|  | [setResolution(int value)](#setResolution-int-) | Устанавливает разрешение изображений предварительного просмотра в DPI (точек на дюйм). |
|
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


Инициализирует объект PreviewOptions.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | Интерфейс, определяющий метод создания потока предварительного просмотра выходной страницы. |
|
|  | pageNumbers | int[] | Желаемые номера страниц |
|

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


Инициализирует объект PreviewOptions.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | Интерфейс, определяющий метод создания потока предварительного просмотра выходной страницы. |
|
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


Инициализирует объект PreviewOptions.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Путь к выходному файлу. |
|
|  | pageNumbers | int[] | Желаемые номера страниц |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Получает или устанавливает ширину изображений предварительного просмотра.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Получает или устанавливает ширину изображений предварительного просмотра.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Получает или устанавливает высоту изображений предварительного просмотра.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Получает или устанавливает высоту изображений предварительного просмотра.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Получает или устанавливает номера страниц изображений предварительного просмотра.


**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Получает или устанавливает номера страниц изображений предварительного просмотра.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Получает или задает формат изображений предварительного просмотра.


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Получает или задает формат изображений предварительного просмотра.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


Получает или устанавливает флаг скрытия подписей на изображении предварительного просмотра страницы.
Только подписи, помеченные как IsSignature, будут скрыты на сгенерированном изображении страницы документа.


**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


Получает или устанавливает флаг скрытия подписей на изображении предварительного просмотра страницы.
Только подписи, помеченные как IsSignature, будут скрыты на сгенерированном изображении страницы документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Получает разрешение изображений предварительного просмотра в DPI (точек на дюйм).


**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Устанавливает разрешение изображений предварительного просмотра в DPI (точек на дюйм).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

