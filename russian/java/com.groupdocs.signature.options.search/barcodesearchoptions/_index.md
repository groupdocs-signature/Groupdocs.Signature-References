---
title: "BarcodeSearchOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет абстрактные параметры поиска для штрих-кодных подписей."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.options.search/barcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class BarcodeSearchOptions extends SearchOptions
```

Представляет абстрактные параметры поиска для штрих-кодных подписей.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [BarcodeSearchOptions()](#BarcodeSearchOptions--) | Инициализирует новый экземпляр класса SearchBarcodeOptions со значениями по умолчанию. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Инициализирует новый экземпляр класса SearchBarcodeOptions со значением типа кодирования. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | Инициализирует новый экземпляр класса SearchBarcodeOptions со значениями типа кодирования и текста. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Указывает свойство Encode Type для поиска штрихкодов. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Указывает свойство Encode Type для поиска штрихкодов. |
|
|  | [getText()](#getText--) | Указывает текст подписи Barcode, если его следует искать и сопоставлять. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Указывает текст подписи Barcode, если его следует искать и сопоставлять. |
|
|  | [getMatchType()](#getMatchType--) | Получает или задает поиск по типу совпадения текста Barcode. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Получает или задает поиск по типу совпадения текста Barcode. |
|
|  | [getReturnContent()](#getReturnContent--) | Получает или задает флаг для получения изображения подписи Barcode на странице документа. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Получает или задает флаг для получения изображения подписи Barcode на странице документа. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Указывает тип файла возвращаемого содержимого изображения подписи Barcode, когда свойство ReturnContent включено. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Указывает тип файла возвращаемого содержимого изображения подписи Barcode, когда свойство ReturnContent включено. |
|
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


Инициализирует новый экземпляр класса SearchBarcodeOptions со значениями по умолчанию.


### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


Инициализирует новый экземпляр класса SearchBarcodeOptions со значением типа кодирования.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Указывает тип кодирования Barcode. |
|

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


Инициализирует новый экземпляр класса SearchBarcodeOptions со значениями типа кодирования и текста.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Указывает тип кодирования Barcode. |
|
|  | текст | java.lang.String | Установить текст подписи штрих‑кода. |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Указывает свойство Encode Type для поиска штрихкодов.
Если это значение не задано, поиск выполняется для всех поддерживаемых типов штрих‑кодов.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Указывает свойство Encode Type для поиска штрихкодов.
Если это значение не задано, поиск выполняется для всех поддерживаемых типов штрих‑кодов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Указывает текст подписи Barcode, если его следует искать и сопоставлять.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Указывает текст подписи Barcode, если его следует искать и сопоставлять.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Получает или задает тип сопоставления текста штрих‑кода при поиске. Используется только когда свойство Text задано.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Получает или задает тип сопоставления текста штрих‑кода при поиске. Используется только когда свойство Text задано.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Получает или задает флаг для получения изображения подписи Barcode на странице документа.
Если этот флаг установлен в true, содержимое изображения подписи Barcode будет сохранять необработанные данные изображения в требуемом формате.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
По умолчанию эта опция отключена.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Получает или задает флаг для получения изображения подписи Barcode на странице документа.
Если этот флаг установлен в true, содержимое изображения подписи Barcode будет сохранять необработанные данные изображения в требуемом формате.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
По умолчанию эта опция отключена.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Указывает тип файла возвращаемого содержимого изображения подписи Barcode, когда свойство ReturnContent включено.
По умолчанию она установлена в Null. Это означает, что содержимое изображения Barcode будет возвращено в оригинальном формате.
Этот формат изображения указан в
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Возможные поддерживаемые значения: FileType.JPEG, FileType.PNG, FileType.BMP.
Если указанный формат не поддерживается, будет возвращено содержимое изображения Barcode в формате .png.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Указывает тип файла возвращаемого содержимого изображения подписи Barcode, когда свойство ReturnContent включено.
По умолчанию она установлена в Null. Это означает, что содержимое изображения Barcode будет возвращено в оригинальном формате.
Этот формат изображения указан в
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Возможные поддерживаемые значения: FileType.JPEG, FileType.PNG, FileType.BMP.
Если указанный формат не поддерживается, будет возвращено содержимое изображения Barcode в формате .png.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

