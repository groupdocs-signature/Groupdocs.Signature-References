---
title: "QrCodeSignOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет параметры подписи QR‑кода."
type: docs
weight: 15
url: /ru/java/com.groupdocs.signature.options.sign/qrcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class QrCodeSignOptions extends TextSignOptions
```

Представляет параметры подписи QR‑кода.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [QrCodeSignOptions()](#QrCodeSignOptions--) | Инициализирует новый экземпляр класса QRCodeSignOptions со значениями по умолчанию. |
|
|  | [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | Инициализирует новый экземпляр класса QRCodeSignOptions с текстом. |
|
|  | [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Инициализирует новый экземпляр класса BarcodeSignOptions с текстом. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Получает или задает тип QRCode. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Получает или задает тип QRCode. |
|
|  | [getForeColor()](#getForeColor--) | Получает или задает цвет переднего плана полос QR-Code. |
Использование этого свойства может вызвать проблемы при проверке.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Получает или задает цвет переднего плана полос QR-Code. |
Использование этого свойства может вызвать проблемы при проверке.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Получает или задает цвет переднего плана полос QR-Code. |
Использование этого свойства может вызвать проблемы при проверке.
|
|  | [getInnerMargins()](#getInnerMargins--) | Получает или задает расстояние между элементами QRCode и границами результирующего изображения. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Получает или задает расстояние между элементами QRCode и границами результирующего изображения. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | Получает или задает выравнивание текста в результирующем изображении QR-code. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Получает или задает выравнивание текста в результирующем изображении QR-code. |
|
|  | [getLogoFilePath()](#getLogoFilePath--) | Получает или задает имя файла изображения логотипа QR-code. |
|
|  | [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | Получает или задает имя файла изображения логотипа QR-code. |
|
|  | [getLogoStream()](#getLogoStream--) | Получает или задает поток изображения логотипа QR-code. |
|
|  | [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | Получает или задает поток изображения логотипа QR-code. |
|
|  | [getData()](#getData--) | Получает или задает пользовательский объект для сериализации в содержимое QR-Code. |
|
|  | [setData(Object value)](#setData-java.lang.Object-) | Получает или задает пользовательский объект для сериализации в содержимое QR-Code. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств текста или данных подписи QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств текста или данных подписи QR-Code. |
|
|  | [getReturnContent()](#getReturnContent--) | Получает или задает флаг для получения содержимого изображения QR-Code подписи, размещённой на странице документа. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Получает или задает флаг для получения содержимого изображения QR-Code подписи, размещённой на странице документа. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Указывает тип файла возвращаемого содержимого изображения подписи QR‑Code, когда свойство ReturnContent включено. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Указывает тип файла возвращаемого содержимого изображения подписи QR‑Code, когда свойство ReturnContent включено. |
|
|  | [toString()](#toString--) | Переопределить преобразование строки. |
|
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


Инициализирует новый экземпляр класса QRCodeSignOptions со значениями по умолчанию.


### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


Инициализирует новый экземпляр класса QRCodeSignOptions с текстом.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | текст | java.lang.String | Текст подписи. |
|

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


Инициализирует новый экземпляр класса BarcodeSignOptions с текстом.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | текст | java.lang.String | Текст QR‑Code |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Тип кодирования QR‑Code, см. [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Получает или задает тип QRCode.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Получает или задает тип QRCode.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Получает или задает цвет переднего плана полос QR-Code.
Использование этого свойства может вызвать проблемы при проверке. Используйте его осторожно.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Получает или задает цвет переднего плана полос QR-Code.
Использование этого свойства может вызвать проблемы при проверке. Используйте его осторожно.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Получает или задает цвет переднего плана полос QR-Code.
Использование этого свойства может вызвать проблемы при проверке. Используйте его осторожно.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Получает или задает расстояние между элементами QRCode и границами результирующего изображения.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Получает или задает расстояние между элементами QRCode и границами результирующего изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Получает или задает выравнивание текста в результирующем изображении QR-code.
Значение по умолчанию — None.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Получает или задает выравнивание текста в результирующем изображении QR-code.
Значение по умолчанию — None.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


Получает или задает имя файла изображения логотипа QR-code.
Это свойство используется только если LogoStream не указан.
Использование этого свойства может вызвать проблемы при проверке. Используйте его осторожно.


**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


Получает или задает имя файла изображения логотипа QR-code.
Это свойство используется только если LogoStream не указан.
Использование этого свойства может вызвать проблемы при проверке. Используйте его осторожно.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


Получает или задает поток изображения логотипа QR-code.
Если это свойство указано, оно всегда используется вместо LogoGuid.
Использование этого свойства может вызвать проблемы при проверке. Используйте его осторожно.


**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


Получает или задает поток изображения логотипа QR-code.
Если это свойство указано, оно всегда используется вместо LogoGuid.
Использование этого свойства может вызвать проблемы при проверке. Используйте его осторожно.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


Получает или задает пользовательский объект для сериализации в содержимое QR-Code.


**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


Получает или задает пользовательский объект для сериализации в содержимое QR-Code.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

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


Получает или задает флаг для получения содержимого изображения QR-Code подписи, размещённой на странице документа.
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


Получает или задает флаг для получения содержимого изображения QR-Code подписи, размещённой на странице документа.
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
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
Возможные поддерживаемые значения: FileType.JPEG, FileType.PNG, FileType.BMP.
Если указанный формат не поддерживается, будет возвращено содержимое изображения QR‑Code в формате .png.


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
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
Возможные поддерживаемые значения: FileType.JPEG, FileType.PNG, FileType.BMP.
Если указанный формат не поддерживается, будет возвращено содержимое изображения QR‑Code в формате .png.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


Переопределить преобразование строки.


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
