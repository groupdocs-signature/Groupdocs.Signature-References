---
title: "BarcodeSignature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Содержит свойства подписи штрихкода."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

Содержит свойства подписи штрихкода.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | Инициализировать объект BarcodeSignature с идентификатором подписи, полученным после процесса поиска. |
|
|  | [BarcodeSignature()](#BarcodeSignature--) | Инициализировать BarcodeSignature с параметрами по умолчанию. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Указывает тип кодирования штрих‑кода. |
|
|  | [getText()](#getText--) | Указывает текст штрих‑кода. |
|
|  | [getFormat()](#getFormat--) | Указывает формат изображения подписи штрих‑кода. |
|
|  | [getContent()](#getContent--) | Указывает двоичные данные изображения штрих‑кода типа |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Переопределяет метод Equals для сравнения свойств подписи |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
|  | [deepClone()](#deepClone--) | Создать копию экземпляра подписи штрих‑кода. |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


Инициализировать объект BarcodeSignature с идентификатором подписи, полученным после процесса поиска.
Этот уникальный идентификатор используется для поиска дополнительных свойств этой подписи в слое информации о подписи документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | signatureId | java.lang.String | Уникальный идентификатор подписи, полученный методом Sign или Search класса Signature [Signature](../../com.groupdocs.signature/signature). |
|

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


Инициализировать BarcodeSignature с параметрами по умолчанию.


### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Указывает тип кодирования штрих‑кода.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


Указывает текст штрих‑кода.


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Указывает формат изображения подписи штрих‑кода.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Указывает двоичные данные изображения штрих‑кода типа
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
По умолчанию это свойство не будет установлено.
Использовать свойство
BarcodeSearchOptions.ReturnContent
([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions#setReturnContent-boolean-)) для включения этой функции.


**Returns:**
byte[]
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


Создать копию экземпляра подписи штрих‑кода.


**Returns:**
java.lang.Object - Возвращает клонированный экземпляр подписи штрих‑кода.

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| изображение | java.awt.image.BufferedImage |  |

