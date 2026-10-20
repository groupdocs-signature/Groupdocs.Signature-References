---
title: "QrCodeSearchOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет абстрактные параметры поиска для подписей QR‑кода."
type: docs
weight: 16
url: /ru/java/com.groupdocs.signature.options.search/qrcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class QrCodeSearchOptions extends SearchOptions
```

Представляет абстрактные параметры поиска для подписей QR‑кода.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [QrCodeSearchOptions()](#QrCodeSearchOptions--) | Инициализирует новый экземпляр класса QRCodeSearchOptions со значениями по умолчанию. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Инициализирует новый экземпляр класса QRCodeSearchOptions со значением типа кодирования. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | Инициализирует новый экземпляр класса QRCodeSearchOptions со значениями типа кодирования и текста. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Указывает свойство Encode Type для поиска QR‑кодов. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Указывает свойство Encode Type для поиска QR‑кодов. |
|
|  | [getText()](#getText--) | Указывает текст подписи QR‑Code, если его следует искать и сопоставлять. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Указывает текст подписи QR‑Code, если его следует искать и сопоставлять. |
|
|  | [getMatchType()](#getMatchType--) | Получает или задает поиск по типу совпадения текста QR‑Code. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Получает или задает поиск по типу совпадения текста QR‑Code. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств текста или данных подписи QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств текста или данных подписи QR-Code. |
|
|  | [getReturnContent()](#getReturnContent--) | Получает или задает флаг для получения изображения подписи QR‑Code на странице документа. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Получает или задает флаг для получения изображения подписи QR‑Code на странице документа. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Указывает тип файла возвращаемого содержимого изображения подписи QR‑Code, когда свойство ReturnContent включено. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Указывает тип файла возвращаемого содержимого изображения подписи QR‑Code, когда свойство ReturnContent включено. |
|
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


Инициализирует новый экземпляр класса QRCodeSearchOptions со значениями по умолчанию.


### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


Инициализирует новый экземпляр класса QRCodeSearchOptions со значением типа кодирования.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Указывает тип кодирования QR‑Code. |
|

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


Инициализирует новый экземпляр класса QRCodeSearchOptions со значениями типа кодирования и текста.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Указывает тип кодирования QR‑Code. |
|
|  | текст | java.lang.String | Устанавливает текст подписи QR‑Code. |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Указывает свойство Encode Type для поиска QR‑кодов.
Если это значение не задано, поиск выполняется для всех поддерживаемых типов QR‑Code.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Указывает свойство Encode Type для поиска QR‑кодов.
Если это значение не задано, поиск выполняется для всех поддерживаемых типов QR‑Code.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Указывает текст подписи QR‑Code, если его следует искать и сопоставлять.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Указывает текст подписи QR‑Code, если его следует искать и сопоставлять.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Получает или задает поиск по типу совпадения текста QR‑Code. Используется только когда свойство Text установлено.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Получает или задает поиск по типу совпадения текста QR‑Code. Используется только когда свойство Text установлено.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств текста или данных подписи QR-Code.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств текста или данных подписи QR-Code.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Получает или задает флаг для получения изображения подписи QR‑Code на странице документа.
Если этот флаг установлен в true, содержимое изображения подписи QR‑Code будет сохранять необработанные данные изображения в требуемом формате.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
По умолчанию эта опция отключена.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Получает или задает флаг для получения изображения подписи QR‑Code на странице документа.
Если этот флаг установлен в true, содержимое изображения подписи QR‑Code будет сохранять необработанные данные изображения в требуемом формате.
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


Указывает тип файла возвращаемого содержимого изображения подписи QR‑Code, когда свойство ReturnContent включено.
По умолчанию установлено Null. Это означает, что содержимое изображения QR‑Code будет возвращено в оригинальном формате.
Этот формат изображения указан в
QrCodeSignature.Format
()
Возможные поддерживаемые значения: FileType.JPEG, FileType.PNG, FileType.BMP.
Если предоставленный формат не поддерживается, будет возвращено изображение QR‑Code в оригинальном формате .png.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Указывает тип файла возвращаемого содержимого изображения подписи QR‑Code, когда свойство ReturnContent включено.
По умолчанию установлено Null. Это означает, что содержимое изображения QR‑Code будет возвращено в оригинальном формате.
Этот формат изображения указан в
QrCodeSignature.Format
()
Возможные поддерживаемые значения: FileType.JPEG, FileType.PNG, FileType.BMP.
Если предоставленный формат не поддерживается, будет возвращено изображение QR‑Code в оригинальном формате .png.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

