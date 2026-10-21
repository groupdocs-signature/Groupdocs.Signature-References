---
title: "Подпись"
second_title: "GroupDocs.Signature for .NET API Reference"
description: "Представляет основной класс, который управляет процессом подписи документа."
type: docs
weight: 2170
url: /ru/net/groupdocs.signature/signature/
---
## Signature class

Представляет основной класс, который управляет процессом подписи документа.

```csharp
public class Signature : IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Инициализирует новый экземпляр класса [`Signature`](../signature) с документом, предоставленным через поток. |
| [Signature](signature#constructor_4)(string) | Инициализирует новый экземпляр класса [`Signature`](../signature) с документом, предоставленным по пути к файлу. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Инициализирует новый экземпляр класса [`Signature`](../signature) с документом, предоставленным через поток, и параметрами загрузки LoadOptions. |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Инициализирует новый экземпляр класса [`Signature`](../signature) с документом, предоставленным через поток, и [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_5)(string, LoadOptions) | Инициализирует новый экземпляр класса [`Signature`](../signature) с документом, предоставленным по пути к файлу, и LoadOptions. |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Инициализирует новый экземпляр класса [`Signature`](../signature) с документом, предоставленным по пути к файлу, и [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Инициализирует новый экземпляр класса [`Signature`](../signature) с документом, предоставленным через поток, параметрами загрузки LoadOptions и настройками [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Инициализирует новый экземпляр класса [`Signature`](../signature) с документом, предоставленным по пути к файлу, LoadOptions и [`SignatureSettings`](../signaturesettings). |

## Методы

| Имя | Описание |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Удаляет переданную подпись [`BaseSignature`](../../groupdocs.signature.domain/basesignature) из документа. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Удаляет переданный список подписей [`BaseSignature`](../../groupdocs.signature.domain/basesignature) из документа. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Удаляет подписи из списка определённых типов [`SignatureType`](../../groupdocs.signature.domain/signaturetype) из документа. Будут удалены только подписи, добавленные методом Sign и помеченные как подписи [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature). Поддерживаются следующие типы подписей: Text, Image, Digital, Barcode, QR-Code. |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Удаляет переданный список подписей [`BaseSignature`](../../groupdocs.signature.domain/basesignature) из документа. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Удаляет подписи определённого типа [`SignatureType`](../../groupdocs.signature.domain/signaturetype) из документа. Будут удалены только подписи, добавленные методом Sign и помеченные как подписи [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature). Поддерживаются следующие типы подписей: Text, Image, Digital, Barcode, QR-Code. |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Удаляет подпись по её конкретному идентификатору из документа. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Реализует интерфейс IDisposable для очистки внутренних ресурсов |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Создаёт предварительный просмотр страниц документа. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Получает информацию о страницах документа: их размеры, максимальную высоту страницы, ширину страницы с максимальной высотой. |
| [Search](../../groupdocs.signature/signature/search#search_3)(Func&lt;BaseSignature, bool&gt;) | Ищет подписи в документе, используя все доступные параметры поиска, и фильтрует результаты на основе указанного предиката. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Ищет подписи в документе по списку [`SearchOptions`](../../groupdocs.signature.options/searchoptions). |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Ищет указанные типы подписей в документе по значению [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Search](../../groupdocs.signature/signature/search#search_2)(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Ищет подписи в документе, используя предоставленные параметры поиска, и фильтрует результаты на основе указанного предиката. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_5)(SearchOptions) | Ищет подписи в документе по параметрам [`SearchOptions`](../../groupdocs.signature.options/searchoptions). |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_4)(SignatureType) | Ищет точный тип подписей в документе по значению [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Подписывает документ набором [`SignOptions`](../../groupdocs.signature.options/signoptions) и сохраняет результат в поток. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Подписывает документ с помощью [`SignOptions`](../../groupdocs.signature.options/signoptions) и сохраняет результат в поток. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Подписывает документ набором [`SignOptions`](../../groupdocs.signature.options/signoptions) и сохраняет результат по указанному пути к файлу. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Подписывает документ с помощью [`SignOptions`](../../groupdocs.signature.options/signoptions) и сохраняет результат по указанному пути к файлу. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Подписывает документ набором [`SignOptions`](../../groupdocs.signature.options/signoptions) и сохраняет результат в поток с предопределёнными [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Подписывает документ с помощью [`SignOptions`](../../groupdocs.signature.options/signoptions) и сохраняет результат в поток с предопределёнными [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Подписывает документ набором [`SignOptions`](../../groupdocs.signature.options/signoptions) и сохраняет результат по указанному пути к файлу с предопределёнными [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Подписывает документ с помощью [`SignOptions`](../../groupdocs.signature.options/signoptions) и сохраняет результат по указанному пути к файлу с предопределёнными [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Обновляет переданную подпись [`BaseSignature`](../../groupdocs.signature.domain/basesignature) в документе. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Обновляет переданные подписи [`BaseSignature`](../../groupdocs.signature.domain/basesignature) в документе. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Проверяет подписи документа с помощью списка данных VerifyOptions. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Проверяет подписи документа с заданными данными VerifyOptions. |
| [Verify](../../groupdocs.signature/signature/verify#verify_3)(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Проверяет подписи документа, используя все доступные параметры проверки, и фильтрует результаты на основе указанного предиката. Этот метод сначала ищет подписи, соответствующие параметрам проверки, фильтрует их с помощью предиката, а затем проверяет только отфильтрованные подписи. |
| [Verify](../../groupdocs.signature/signature/verify#verify_2)(VerifyOptions, Func&lt;BaseSignature, bool&gt;) | Проверяет подписи документа, используя предоставленные параметры проверки, и фильтрует результаты на основе указанного предиката. Этот метод сначала ищет подписи, соответствующие параметрам проверки, фильтрует их с помощью предиката, а затем проверяет только отфильтрованные подписи. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Создаёт предварительный просмотр подписи на основе заданных SignOptions. [`SignOptions`](../../groupdocs.signature.options/signoptions) |

## События

| Имя | Описание |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Происходит, когда процесс поиска подписи завершён. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Происходит, когда прогресс процесса поиска подписи изменился. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Происходит, когда процесс поиска подписи начался. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Происходит, когда процесс подписания документа завершён. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Возникает, когда изменился прогресс процесса подписания документа. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Возникает, когда процесс подписания документа начался. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Возникает, когда процесс проверки подписи завершён. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Возникает, когда изменился прогресс процесса проверки подписи. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Возникает, когда процесс проверки подписи начался. |

### Примечания

**Learn more**

Больше о функциях GroupDocs.Signature: [GroupDocs.Signature Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### См. также

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
