---
title: "Signature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет основной класс, который управляет процессом подписания документа."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

Представляет основной класс, который управляет процессом подписания документа.

<br />

*** ** * ** ***

**Learn more**

* More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide](../https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Signature(InputStream document)](#Signature-java.io.InputStream-) | Инициализирует новый экземпляр класса [Signature](../../com.groupdocs.signature/signature) с документом, предоставленным в виде потока. |
|
|  | [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Инициализирует новый экземпляр класса [Signature](../../com.groupdocs.signature/signature) с документом, предоставленным в виде потока, и параметрами загрузки |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | Инициализирует новый экземпляр класса [Signature](../../com.groupdocs.signature/signature) с документом, предоставленным в виде потока, и [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
|
|  | [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Инициализирует новый экземпляр класса [Signature](../../com.groupdocs.signature/signature) с документом, предоставленным в виде потока, и параметрами загрузки |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) и настройки [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
|  | [Signature(String filePath)](#Signature-java.lang.String-) | Инициализирует новый экземпляр класса [Signature](../../com.groupdocs.signature/signature) с документом, предоставленным по пути к файлу. |
|
|  | [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Инициализирует новый экземпляр класса [Signature](../../com.groupdocs.signature/signature) с документом, предоставленным по пути к файлу, и |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | Инициализирует новый экземпляр класса [Signature](../../com.groupdocs.signature/signature) с документом, предоставленным по пути к файлу, и [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
|
|  | [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Инициализирует новый экземпляр класса [Signature](../../com.groupdocs.signature/signature) с документом, предоставленным по пути к файлу, |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) и [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | Подписывает документ с помощью [SignOptions](../../com.groupdocs.signature.options.sign/signoptions), и сохраняет результат в поток. |
|
|  | [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Подписывает документ с помощью [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) и сохраняет результат в поток с предопределёнными [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Подписывает документ с коллекцией [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) и сохраняет результат в поток. |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Подписывает документ с коллекцией [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) и сохраняет результат в поток с предопределёнными [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
|
|  | [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | Подписывает документ с помощью [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) и сохраняет результат в указанный путь к файлу. |
|
|  | [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Подписывает документ с помощью [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) и сохраняет результат в указанный путь к файлу с предопределёнными [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Подписывает документ с коллекцией [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) и сохраняет результат в указанный путь к файлу. |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Подписывает документ с коллекцией [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) и сохраняет результат в указанный путь к файлу с предопределёнными [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
|
|  | [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | Проверяет подписи документа с заданными данными VerifyOptions. |
|
|  | [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | Проверяет подписи документа со списком данных VerifyOptions. |
|
|  | [verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Проверяет подписи документа, используя предоставленные параметры проверки и фильтры |
успешные результаты по указанному предикату.
|
|  | [verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Проверяет подписи документа, используя список параметров проверки и фильтрует |
успешные результаты по указанному предикату.
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Получает информацию о страницах документа: их размеры, |
максимальная высота страницы, ширина страницы с максимальной высотой.
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | Создаёт предварительный просмотр страниц документа. |
|
|  | [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | Ищет подписи в документе по списку [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
|
|  | [search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Ищет подписи по списку параметров и фильтрует результат по предикату. |
|
|  | [search(Predicate<BaseSignature> predicate)](#search-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Ищет в документе подписи всех типов (текст, изображение, цифровая, штрих‑код, QR‑код и метаданные) |
и фильтрует их по предикату.
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | Ищет подписи в документе по параметрам [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--) | Ищет подписи указанного типа в документе, опционально отфильтрованные по предикату. |
|
|  | [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | Ищет точный тип подписей в документе по значению [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype). |
|
|  | [search(int[] signatureTypes)](#search-int...-) | Ищет указанные типы подписей в документе по значению [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype). |
|
|  | [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Обновляет переданную подпись [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) в документе. |
|
|  | [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Обновляет переданные подписи [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) в документе. |
|
|  | [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Обновляет переданные подписи [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) в документе. |
|
|  | [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Обновляет переданные подписи [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) в документе. |
|
|  | [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Удаляет переданную подпись [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) из документа. |
|
|  | [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Удаляет переданный список подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) из документа. |
|
|  | [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Удаляет переданную подпись [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) из документа. |
|
|  | [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Удаляет переданный список подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) из документа. |
|
|  | [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | Удаляет подписи определённого типа [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) из документа. |
|
|  | [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | Удаляет подписи из списка определённых типов [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) из документа. |
|
|  | [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | Удаляет подписи определённого типа [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) из документа. |
|
|  | [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | Удаляет подписи из списка определённых типов [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) из документа. |
|
|  | [delete(String signatureId)](#delete-java.lang.String-) | Удаляет подпись по конкретному идентификатору подписи из документа. |
|
|  | [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | Удаляет переданный список подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) из документа. |
|
|  | [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | Создаёт предварительный просмотр подписи на основе заданных SignOptions. |
|
|  | [dispose()](#dispose--) | Реализуйте интерфейс IDisposable для очистки внутренних ресурсов |
|
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


Инициализирует новый экземпляр класса [Signature](../../com.groupdocs.signature/signature) с документом, предоставленным в виде потока.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.InputStream | Поток содержимого документа. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(InputStream document, LoadOptions loadOptions) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(InputStream document, LoadOptions loadOptions)
```


Инициализирует новый экземпляр класса [Signature](../../com.groupdocs.signature/signature) с документом, предоставленным в виде потока, и параметрами загрузки
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.InputStream | Поток содержимого документа. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Параметры загрузки документа. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(InputStream document, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, SignatureSettings settings)
```


Инициализирует новый экземпляр класса [Signature](../../com.groupdocs.signature/signature) с документом, предоставленным в виде потока, и [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.InputStream | Поток содержимого документа. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Настройки подписи. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)
```


Инициализирует новый экземпляр класса [Signature](../../com.groupdocs.signature/signature) с документом, предоставленным в виде потока, и параметрами загрузки
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) и настройки [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.InputStream | Поток содержимого документа. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Параметры загрузки документа. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Настройки подписи. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(String filePath) {#Signature-java.lang.String-}
```
public Signature(String filePath)
```


Инициализирует новый экземпляр класса [Signature](../../com.groupdocs.signature/signature) с документом, предоставленным по пути к файлу.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Абсолютный или относительный путь к файлу. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(String filePath, LoadOptions loadOptions) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(String filePath, LoadOptions loadOptions)
```


Инициализирует новый экземпляр класса [Signature](../../com.groupdocs.signature/signature) с документом, предоставленным по пути к файлу, и
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Абсолютный или относительный путь к файлу. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Параметры загрузки документа. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(String filePath, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, SignatureSettings settings)
```


Инициализирует новый экземпляр класса [Signature](../../com.groupdocs.signature/signature) с документом, предоставленным по пути к файлу, и [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Абсолютный или относительный путь к файлу. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Настройки подписи. |

<br />

*** ** * ** ***

 **Learn more** 

* 
* 

<br />

|

### Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)
```


Инициализирует новый экземпляр класса [Signature](../../com.groupdocs.signature/signature) с документом, предоставленным по пути к файлу,
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) и [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Абсолютный или относительный путь к файлу. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Параметры загрузки документа. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Настройки подписи. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### sign(OutputStream document, SignOptions signOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions)
```


Подписывает документ с помощью [SignOptions](../../com.groupdocs.signature.options.sign/signoptions), и сохраняет результат в поток.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.OutputStream | Поток выходного документа. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Параметры подписи. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)
```


Подписывает документ с помощью [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) и сохраняет результат в поток с предопределёнными [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.OutputStream | Поток выходного документа. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Параметры подписи. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Параметры сохранения. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, List<SignOptions> signOptionsList) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList)
```


Подписывает документ с коллекцией [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) и сохраняет результат в поток.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.OutputStream | Поток выходного документа. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Список параметров подписи. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


Подписывает документ с коллекцией [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) и сохраняет результат в поток с предопределёнными [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.OutputStream | Поток выходного документа. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Список параметров подписи. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Параметры сохранения. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, SignOptions signOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions)
```


Подписывает документ с помощью [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) и сохраняет результат в указанный путь к файлу.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к выходному файлу. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Параметры подписи. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)
```


Подписывает документ с помощью [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) и сохраняет результат в указанный путь к файлу с предопределёнными [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к выходному файлу. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Параметры подписи. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Параметры сохранения. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, List<SignOptions> signOptionsList) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList)
```


Подписывает документ с коллекцией [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) и сохраняет результат в указанный путь к файлу.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к выходному файлу. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Список параметров подписи. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - 
### sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


Подписывает документ с коллекцией [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) и сохраняет результат в указанный путь к файлу с предопределёнными [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к выходному файлу. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Список параметров подписи. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Параметры сохранения. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### verify(VerifyOptions verifyOptions) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-}
```
public final VerificationResult verify(VerifyOptions verifyOptions)
```


Проверяет подписи документа с заданными данными VerifyOptions.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | Параметры проверки подписи. |

<br />

*** ** * ** ***

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java](../https://docs.groupdocs.com/signature/java/verify-document-for-signatures/)

<br />

|

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### verify(List<VerifyOptions> verifyOptionsList) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--}
```
public final VerificationResult verify(List<VerifyOptions> verifyOptionsList)
```


Проверяет подписи документа со списком данных VerifyOptions.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | Коллекция параметров проверки подписи. Экземпляр [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection). |

<br />

*** ** * ** ***

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java](../https://docs.groupdocs.com/signature/java/verify-document-for-signatures/)

<br />

|

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)
```


Проверяет подписи документа, используя предоставленные параметры проверки и фильтры
успешные результаты по указанному предикату.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | Параметры проверки подписи. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Предикат фильтра, применяемый к списку проверенных подписей. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - Список подписей, прошедших проверку и удовлетворяющих предикату.

### verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)
```


Проверяет подписи документа, используя список параметров проверки и фильтрует
успешные результаты по указанному предикату.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | Список параметров проверки подписи. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Предикат фильтра, применяемый к списку проверенных подписей. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - Список подписей, прошедших проверку и удовлетворяющих предикату.

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Получает информацию о страницах документа: их размеры,
максимальная высота страницы, ширина страницы с максимальной высотой.


**Returns:**
[IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo) - Information about document.

<br />

*** ** * ** ***

**Learn more**

* Learn more about signed document - file type, pages count and many other format specific properties: [How to get document properties in Java](../https://docs.groupdocs.com/signature/java/get-document-information/)

<br />


### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Создаёт предварительный просмотр страниц документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | Параметры предварительного просмотра. |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/generate-document-pages-preview/)

<br />

|

### search(List<SearchOptions> searchOptionsList) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList)
```


Ищет подписи в документе по списку [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | Коллекция параметров поиска. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found Signatures.

### search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)
```


Ищет подписи по списку параметров и фильтрует результат по предикату.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | Список параметров поиска. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Предикат, используемый для фильтрации полученных подписей. |
|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - SearchResult containing only signatures that match the predicate.

### search(Predicate<BaseSignature> predicate) {#search-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> search(Predicate<BaseSignature> predicate)
```


Ищет в документе подписи всех типов (текст, изображение, цифровая, штрих‑код, QR‑код и метаданные)
и фильтрует их по предикату.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Предикат фильтра, применяемый к списку найденных подписей. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - Возвращает список экземпляров [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), удовлетворяющих заданному предикату.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions)
```


Ищет подписи в документе по параметрам [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | Параметры поиска. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - Возвращает список найденных подписей.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)
```


Ищет подписи указанного типа в документе, опционально отфильтрованные по предикату.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | typeOfT | java.lang.Class<T> | Обобщённый параметр типа [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | Параметры поиска подписи. |
|
|  | predicate | java.util.function.Predicate<T> | Необязательный предикатный фильтр, применяемый после поиска. Может быть null. |
|

**Returns:**
java.util.List<T> - Список найденных подписей, опционально отфильтрованных предикатом.

### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


Ищет точный тип подписей в документе по значению [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | Тип подписей для поиска. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - Возвращает список найденных подписей точного типа.

### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


Ищет указанные типы подписей в документе по значению [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | signatureTypes | int[] | Один или несколько типов подписей для поиска. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found signatures.

### update(OutputStream document, BaseSignature signature) {#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(OutputStream document, BaseSignature signature)
```


Обновляет переданную подпись [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) в документе.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.OutputStream | Поток выходного документа. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Объект подписи, который будет обновлен в документе. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
`boolean` - Возвращает true, если операция прошла успешно.

### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


Обновляет переданные подписи [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) в документе.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.OutputStream | Поток выходного документа. |
|
|  | подписи | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Список подписей для обновления в документе. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### update(String filePath, List<BaseSignature> signatures) {#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(String filePath, List<BaseSignature> signatures)
```


Обновляет переданные подписи [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) в документе.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к выходному файлу. |
|
|  | подписи | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Список подписей для обновления в документе. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### update(String filePath, BaseSignature signature) {#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(String filePath, BaseSignature signature)
```


Обновляет переданные подписи [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) в документе.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к выходному файлу. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Объект подписи, который будет обновлен в документе. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
`boolean` - Возвращает UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) со списком успешно обновлённых подписей и неудачных.

### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


Удаляет переданную подпись [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) из документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.OutputStream | Поток выходного документа. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Объект подписи, который будет удалён из документа. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
`boolean` - Возвращает true, если операция прошла успешно.

### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


Удаляет переданный список подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) из документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.OutputStream | Поток выходного документа. |
|
|  | подписи | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Список подписей для удаления из документа. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String filePath, BaseSignature signature) {#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(String filePath, BaseSignature signature)
```


Удаляет переданную подпись [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) из документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к выходному файлу. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Объект подписи, который будет удалён из документа. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
`boolean` - Возвращает true, если операция прошла успешно.

### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


Удаляет переданный список подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) из документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к выходному файлу. |
|
|  | подписи | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Список подписей для удаления из документа. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(OutputStream document, int signatureType) {#delete-java.io.OutputStream-int-}
```
public final DeleteResult delete(OutputStream document, int signatureType)
```


Удаляет подписи определённого типа [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) из документа.
Только подписи, которые были добавлены методом Sign и помечены как Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) будет удалено.
Поддерживаются следующие типы подписей: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.OutputStream | Поток выходного документа. |
|
|  | signatureType | int | Тип подписей, которые будут удалены из документа. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### deleteByTypes(OutputStream document, List<Integer> signatureTypes) {#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(OutputStream document, List<Integer> signatureTypes)
```


Удаляет подписи из списка определённых типов [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) из документа.
Только подписи, которые были добавлены методом Sign и помечены как Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) будет удалено.
Поддерживаются следующие типы подписей: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.OutputStream | Поток выходного документа. |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | Список типов подписей, которые будут удалены из документа. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String filePath, int signatureType) {#delete-java.lang.String-int-}
```
public final DeleteResult delete(String filePath, int signatureType)
```


Удаляет подписи определённого типа [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) из документа.
Только подписи, которые были добавлены методом Sign и помечены как Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) будет удалено.
Поддерживаются следующие типы подписей: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к выходному файлу. |
|
|  | signatureType | int | Тип подписей, которые будут удалены из документа. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### deleteByTypes(String filePath, List<Integer> signatureTypes) {#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(String filePath, List<Integer> signatureTypes)
```


Удаляет подписи из списка определённых типов [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) из документа.
Только подписи, которые были добавлены методом Sign и помечены как Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) будет удалено.
Поддерживаются следующие типы подписей: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к выходному файлу. |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | Список типов подписей, которые будут удалены из документа. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String signatureId) {#delete-java.lang.String-}
```
public final boolean delete(String signatureId)
```


Удаляет подпись по конкретному идентификатору подписи из документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | signatureId | java.lang.String | Идентификатор (Id) подписи, которую нужно удалить из документа. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting)

<br />

|

**Returns:**
`boolean` - Возвращает true, если операция прошла успешно.

### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


Удаляет переданный список подписей [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) из документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | Список идентификаторов подписей, которые будут удалены из документа. |

<br />

*** ** * ** ***

**Learn more** /// /// /// More about how to delete electronic signature from document in Java: /// [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents) /// /// /// Advanced use cases of deleting document eSignatures: /// [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting) /// /// ///
|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### generateSignaturePreview(PreviewSignatureOptions previewOptions) {#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-}
```
public static void generateSignaturePreview(PreviewSignatureOptions previewOptions)
```


Генерирует предварительный просмотр подписи на основе заданных SignOptions. [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | Предпросмотр подписи с заданными SignOptions. [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews of the signatures:
|

### dispose() {#dispose--}
```
public final void dispose()
```


Реализуйте интерфейс IDisposable для очистки внутренних ресурсов


