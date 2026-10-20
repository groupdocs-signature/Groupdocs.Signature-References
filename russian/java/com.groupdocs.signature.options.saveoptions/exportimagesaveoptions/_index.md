---
title: "ExportImageSaveOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Параметры сохранения для экспорта документов в изображение."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

Параметры сохранения для экспорта документов в изображение.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [ExportImageSaveOptions()](#ExportImageSaveOptions--) | Инициализирует новый экземпляр класса ExportAsImageSaveOptions со значениями по умолчанию. |
|
|  | [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | Инициализирует новый экземпляр класса ExportAsImageSaveOptions с указанным форматом файла. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Получает или задает номер страницы документа для экспорта. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Получает или задает номер страницы документа для экспорта. |
|
|  | [getExportAllPages()](#getExportAllPages--) | Флаг для экспорта каждой страницы. |
|
|  | [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | Флаг для экспорта каждой страницы. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Параметры для указания страниц, которые необходимо подписать. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Параметры для указания страниц, которые необходимо подписать. |
|
|  | [getPageColumns()](#getPageColumns--) | Получает или задает количество колонок для экспортированных изображений. |
|
|  | [setPageColumns(int value)](#setPageColumns-int-) | Получает или задает количество колонок для экспортированных изображений. |
|
|  | [getBorder()](#getBorder--) | Получает или задает настройки границы изображения. |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Получает или задает настройки границы изображения. |
|
|  | [getTiffMultipage()](#getTiffMultipage--) | Размещает страницы документа в разных кадрах TIFF‑изображения. |
|
|  | [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | Размещает страницы документа в разных кадрах TIFF‑изображения. |
|
|  | [toString()](#toString--) | Переопределить преобразование строки. |
|
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


Инициализирует новый экземпляр класса ExportAsImageSaveOptions со значениями по умолчанию.


### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


Инициализирует новый экземпляр класса ExportAsImageSaveOptions с указанным форматом файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileFormat | int | Формат выходного файла изображения. |
|

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Получает или задает номер страницы документа для экспорта.
Минимальное значение равно 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Получает или задает номер страницы документа для экспорта.
Минимальное значение равно 1.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


Флаг для экспорта каждой страницы.


**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


Флаг для экспорта каждой страницы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Параметры для указания страниц, которые необходимо подписать.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Параметры для указания страниц, которые необходимо подписать.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


Получает или задает количество колонок для экспортированных изображений.
Используйте это свойство, если нужно разместить изображения в ряд.


**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


Получает или задает количество колонок для экспортированных изображений.
Используйте это свойство, если нужно разместить изображения в ряд.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Получает или задает настройки границы изображения. По умолчанию это значение не установлено.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Получает или задает настройки границы изображения. По умолчанию это значение не установлено.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


Размещает страницы документа в разных кадрах TIFF‑изображения.


**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


Размещает страницы документа в разных кадрах TIFF‑изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Переопределить преобразование строки.


**Returns:**
java.lang.String -
