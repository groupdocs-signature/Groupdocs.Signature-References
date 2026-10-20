---
title: "BarcodeVerifyOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет параметры проверки штрихкода."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.options.verify/barcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class BarcodeVerifyOptions extends TextVerifyOptions
```

Представляет параметры проверки штрихкода.

<br />

*** ** * ** ***

 **Learn more**  **Learn more**

* Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](../https://docs.groupdocs.com/signature/java/verify-barcode-signatures-in-the-document)
* Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](../)

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [BarcodeVerifyOptions()](#BarcodeVerifyOptions--) | Создает параметр проверки по умолчанию для штрихкода подписи. |
|
|  | [BarcodeVerifyOptions(String text)](#BarcodeVerifyOptions-java.lang.String-) | Создает параметр проверки по умолчанию с текстом проверки |
|
|  | [BarcodeVerifyOptions(BarcodeType encodeType)](#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Создает параметр проверки по умолчанию с проверкой типа штрихкода |
|
|  | [BarcodeVerifyOptions(String text, BarcodeType encodeType)](#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Создает параметр проверки по умолчанию с проверкой типа штрихкода и текстом |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Получает или задает проверку типа штрихкода. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Получает или задает проверку типа штрихкода. |
|
|  | [toString()](#toString--) | Переопределяет преобразование в строку. |
|
### BarcodeVerifyOptions() {#BarcodeVerifyOptions--}
```
public BarcodeVerifyOptions()
```


Создает параметр проверки по умолчанию для штрихкода подписи.


### BarcodeVerifyOptions(String text) {#BarcodeVerifyOptions-java.lang.String-}
```
public BarcodeVerifyOptions(String text)
```


Создает параметр проверки по умолчанию с текстом проверки


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | текст | java.lang.String | Текст штрихкода для проверки |
|

### BarcodeVerifyOptions(BarcodeType encodeType) {#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(BarcodeType encodeType)
```


Создает параметр проверки по умолчанию с проверкой типа штрихкода


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Проверка типа штрихкода |
|

### BarcodeVerifyOptions(String text, BarcodeType encodeType) {#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(String text, BarcodeType encodeType)
```


Создает параметр проверки по умолчанию с проверкой типа штрихкода и текстом


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | текст | java.lang.String | Текст штрихкода для проверки |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Проверка типа штрихкода |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Получает или задает проверку типа штрихкода.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Получает или задает проверку типа штрихкода.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### toString() {#toString--}
```
public String toString()
```


Переопределяет преобразование в строку.


**Returns:**
java.lang.String -
