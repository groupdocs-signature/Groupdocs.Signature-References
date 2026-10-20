---
title: "PreviewSignatureOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет параметры предварительного просмотра подписи."
type: docs
weight: 12
url: /ru/java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

Представляет параметры предварительного просмотра подписи.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | Инициализирует объект PreviewSignatureOptions. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getSignatureId()](#getSignatureId--) | Уникальное значение для различения подписи. |
|
|  | [setSignatureId(String value)](#setSignatureId-java.lang.String-) | Уникальное значение для различения подписи. |
|
|  | [getSignOptions()](#getSignOptions--) | Параметры подписи для генерации предварительного просмотра. |
|
|  | [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | Параметры подписи для генерации предварительного просмотра. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Получает или задает формат изображений предварительного просмотра. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Получает или задает формат изображений предварительного просмотра. |
|
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


Инициализирует объект PreviewSignatureOptions.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Параметры подписи, для которой генерируется предварительный просмотр. |
|
|  | pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | Интерфейс, определяющий метод создания потока предварительного просмотра выходной страницы. |
|

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Уникальное значение для различения подписи.
Используйте SignatureId для идентификации параметров предварительного просмотра.


**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


Уникальное значение для различения подписи.
Используйте SignatureId для идентификации параметров предварительного просмотра.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


Параметры подписи для генерации предварительного просмотра.


**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


Параметры подписи для генерации предварительного просмотра.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Получает или задает формат изображений предварительного просмотра.
Значение по умолчанию — PNG


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Получает или задает формат изображений предварительного просмотра.
Значение по умолчанию — PNG


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

