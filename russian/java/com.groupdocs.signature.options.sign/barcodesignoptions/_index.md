---
title: "BarcodeSignOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет параметры подписи штрих‑кода."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

Представляет параметры подписи штрих‑кода.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [BarcodeSignOptions()](#BarcodeSignOptions--) | Инициализирует новый экземпляр класса BarcodeSignOptions со значениями по умолчанию. |
|
|  | [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | Инициализирует новый экземпляр класса BarcodeSignOptions с текстом. |
|
|  | [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Инициализирует новый экземпляр класса BarcodeSignOptions с текстом. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Получает или задает тип Barcode. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Получает или задает тип Barcode. |
|
|  | [getForeColor()](#getForeColor--) | Получает или задает цвет передних полос Barcode. |
Использование этого свойства может вызвать проблемы при проверке.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Получает или задает цвет передних полос Barcode. |
Использование этого свойства может вызвать проблемы при проверке.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Получает или задает цвет передних полос Barcode. |
Использование этого свойства может вызвать проблемы при проверке.
|
|  | [getInnerMargins()](#getInnerMargins--) | Получает или задает расстояние между элементами Barcode и границами результирующего изображения. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Получает или задает расстояние между элементами Barcode и границами результирующего изображения. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | Получает или задает выравнивание текста в результирующем изображении Barcode. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Получает или задает выравнивание текста в результирующем изображении Barcode. |
|
|  | [getReturnContent()](#getReturnContent--) | Получает или задает флаг для получения содержимого изображения Barcode подписи, размещённой на странице документа. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Получает или задает флаг для получения содержимого изображения Barcode подписи, размещённой на странице документа. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Указывает тип файла возвращаемого содержимого изображения подписи Barcode, когда свойство ReturnContent включено. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Указывает тип файла возвращаемого содержимого изображения подписи Barcode, когда свойство ReturnContent включено. |
|
|  | [validate()](#validate--) | Внутренний метод для проверки параметров опций Barcode. |
|
|  | [toString()](#toString--) | Переопределить преобразование строки. |
|
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


Инициализирует новый экземпляр класса BarcodeSignOptions со значениями по умолчанию.


### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


Инициализирует новый экземпляр класса BarcodeSignOptions с текстом.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | текст | java.lang.String | Текст Barcode |
|

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


Инициализирует новый экземпляр класса BarcodeSignOptions с текстом.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | текст | java.lang.String | Текст Barcode |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Тип кодирования Barcode см. [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Получает или задает тип Barcode.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Получает или задает тип Barcode.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Получает или задает цвет передних полос Barcode.
Использование этого свойства может вызвать проблемы при проверке. Используйте его осторожно.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Получает или задает цвет передних полос Barcode.
Использование этого свойства может вызвать проблемы при проверке. Используйте его осторожно.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Получает или задает цвет передних полос Barcode.
Использование этого свойства может вызвать проблемы при проверке. Используйте его осторожно.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Получает или задает расстояние между элементами Barcode и границами результирующего изображения.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Получает или задает расстояние между элементами Barcode и границами результирующего изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Получает или задает выравнивание текста в результирующем изображении Barcode.
Значение по умолчанию — None.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Получает или задает выравнивание текста в результирующем изображении Barcode.
Значение по умолчанию — None.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Получает или задает флаг для получения содержимого изображения Barcode подписи, размещённой на странице документа.
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


Получает или задает флаг для получения содержимого изображения Barcode подписи, размещённой на странице документа.
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
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat))
Возможные поддерживаемые значения: FileType.JPEG, FileType.PNG, FileType.BMP.
Если указанный формат не поддерживается, будет возвращено содержимое изображения Barcode в формате .png.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


Внутренний метод для проверки параметров опций Barcode.


### toString() {#toString--}
```
public String toString()
```


Переопределить преобразование строки.


**Returns:**
java.lang.String -
