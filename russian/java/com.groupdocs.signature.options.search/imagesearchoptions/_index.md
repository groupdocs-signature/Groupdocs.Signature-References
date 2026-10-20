---
title: "ImageSearchOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет параметры поиска для подписей изображений."
type: docs
weight: 14
url: /ru/java/com.groupdocs.signature.options.search/imagesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class ImageSearchOptions extends SearchOptions
```

Представляет параметры поиска для подписей изображений.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [ImageSearchOptions()](#ImageSearchOptions--) | Инициализирует новый экземпляр класса ImageSearchOptions со значениями по умолчанию. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getReturnContent()](#getReturnContent--) | Получает или задает флаг для захвата изображения подписи на странице документа. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Получает или задает флаг для захвата изображения подписи на странице документа. |
|
|  | [getMinContentSize()](#getMinContentSize--) | Для ненулевого значения этот флаг указывает минимальный размер изображений для критериев поиска. |
|
|  | [setMinContentSize(long value)](#setMinContentSize-long-) | Для ненулевого значения этот флаг указывает минимальный размер изображений для критериев поиска. |
|
|  | [getMaxContentSize()](#getMaxContentSize--) | Для ненулевого значения этот флаг указывает максимальный размер изображений для критериев поиска. |
|
|  | [setMaxContentSize(long value)](#setMaxContentSize-long-) | Для ненулевого значения этот флаг указывает максимальный размер изображений для критериев поиска. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Указывает тип файла возвращаемого содержимого подписи‑изображения, когда свойство ReturnContent включено. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Указывает тип файла возвращаемого содержимого подписи‑изображения, когда свойство ReturnContent включено. |
|
### ImageSearchOptions() {#ImageSearchOptions--}
```
public ImageSearchOptions()
```


Инициализирует новый экземпляр класса ImageSearchOptions со значениями по умолчанию.


### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Получает или задает флаг для захвата изображения подписи на странице документа.
Если этот флаг установлен в true, содержимое подписи‑изображения будет сохранять необработанные данные изображения в требуемом формате.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
По умолчанию эта опция отключена.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Получает или задает флаг для захвата изображения подписи на странице документа.
Если этот флаг установлен в true, содержимое подписи‑изображения будет сохранять необработанные данные изображения в требуемом формате.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
По умолчанию эта опция отключена.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getMinContentSize() {#getMinContentSize--}
```
public final long getMinContentSize()
```


Для ненулевого значения этот флаг указывает минимальный размер изображений для критериев поиска.
По умолчанию этот флаг установлен в ноль и не влияет на результат поиска.


**Returns:**
long
### setMinContentSize(long value) {#setMinContentSize-long-}
```
public final void setMinContentSize(long value)
```


Для ненулевого значения этот флаг указывает минимальный размер изображений для критериев поиска.
По умолчанию этот флаг установлен в ноль и не влияет на результат поиска.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### getMaxContentSize() {#getMaxContentSize--}
```
public final long getMaxContentSize()
```


Для ненулевого значения этот флаг указывает максимальный размер изображений для критериев поиска.
По умолчанию этот флаг установлен в ноль и не влияет на результат поиска.


**Returns:**
long
### setMaxContentSize(long value) {#setMaxContentSize-long-}
```
public final void setMaxContentSize(long value)
```


Для ненулевого значения этот флаг указывает максимальный размер изображений для критериев поиска.
По умолчанию этот флаг установлен в ноль и не влияет на результат поиска.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Указывает тип файла возвращаемого содержимого подписи‑изображения, когда свойство ReturnContent включено.
По умолчанию он установлен в Null. Это означает возвращать содержимое изображения в оригинальном формате.
Этот формат изображения указан в
ImageSignature.Format

Возможные поддерживаемые значения: FileType.JPEG, FileType.PNG, FileType.BMP.
Если указанный формат не поддерживается, будет возвращено содержимое изображения в оригинальном формате.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Указывает тип файла возвращаемого содержимого подписи‑изображения, когда свойство ReturnContent включено.
По умолчанию он установлен в Null. Это означает возвращать содержимое изображения в оригинальном формате.
Этот формат изображения указан в
ImageSignature.Format

Возможные поддерживаемые значения: FileType.JPEG, FileType.PNG, FileType.BMP.
Если указанный формат не поддерживается, будет возвращено содержимое изображения в оригинальном формате.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

