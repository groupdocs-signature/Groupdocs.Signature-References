---
title: "QrCodeSignature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Содержит свойства подписи QR-кода."
type: docs
weight: 16
url: /ru/java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

Содержит свойства подписи QR-кода.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | Инициализируйте объект QrCodeSignature с идентификатором подписи, полученным после процесса поиска. |
|
| [QrCodeSignature()](#QrCodeSignature--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Указывает тип кодирования QR-кода. |
|
|  | [getText()](#getText--) | Указывает текст QR-кода. |
|
|  | [getFormat()](#getFormat--) | Указывает формат изображения подписи QR-кода. |
|
|  | [getContent()](#getContent--) | Указывает тип содержимого бинарных данных изображения QR-кода |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | Получить объект из текста подписи QR-Code при десериализации. |
|
|  | [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | Получить объект из текста подписи QR-Code при десериализации. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Переопределяет метод Equals для сравнения свойств подписи |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
|  | [deepClone()](#deepClone--) | Клонировать экземпляр подписи QR-Code. |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


Инициализируйте объект QrCodeSignature с идентификатором подписи, полученным после процесса поиска.
Этот уникальный идентификатор используется для поиска дополнительных свойств этой подписи в слое информации о подписи документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | signatureId | java.lang.String | Уникальный идентификатор подписи, полученный методом подписи или поиска. |
|

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Указывает тип кодирования QR-кода.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


Указывает текст QR-кода.


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Указывает формат изображения подписи QR-кода.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Указывает тип содержимого бинарных данных изображения QR-кода
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
По умолчанию это свойство не будет установлено.
Использовать свойство
QrCodeSearchOptions.ReturnContent
([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions#setReturnContent-boolean-)) чтобы включить эту функцию.


**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


Получить объект из текста подписи QR-Code при десериализации.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | java.lang.Class<T> |  |

**Returns:**
T -
T
: Тип объекта для десериализации из текста QR-Code

### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


Получить объект из текста подписи QR-Code при десериализации.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Установить пользовательскую реализацию шифрования данных |


T
: Тип объекта для десериализации из текста QR-Code
|
| тип | java.lang.Class<T> |  |

**Returns:**
T -
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Переопределяет метод Equals для сравнения свойств подписи


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | подпись | java.lang.Object | Объект подписи для сравнения. |
|

**Returns:**
boolean — Возвращает true, если переданный объект подписи имеет тот же тип и все его свойства равны свойствам этого экземпляра.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Переопределяет метод GetHashCode


**Returns:**
int — Хеш‑код подписи

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Клонировать экземпляр подписи QR-Code.


**Returns:**
java.lang.Object - Возвращает клонированный экземпляр подписи QR-code.

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| изображение | java.awt.image.BufferedImage |  |

