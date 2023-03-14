---
title: Signature
second_title: Справочник по API GroupDocs.Signature для .NET
description: Представляет основной класс управляющий процессом подписания документа.
type: docs
weight: 1880
url: /ru/net/groupdocs.signature/signature/
---
## Signature class

Представляет основной класс, управляющий процессом подписания документа.

```csharp
public class Signature : IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Инициализирует новый экземпляр[`Signature`](../signature) класс с документом, предоставленным stream. |
| [Signature](signature#constructor_4)(string) | Инициализирует новый экземпляр[`Signature`](../signature) экземпляр класса с документом, предоставленным по пути к файлу. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Инициализирует новый экземпляр[`Signature`](../signature) класс с документом, предоставленным параметрами потока и загрузкиLoadOptions . |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Инициализирует новый экземпляр[`Signature`](../signature)экземпляр класса с документом, предоставленным потоком и[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_5)(string, LoadOptions) | Инициализирует новый экземпляр[`Signature`](../signature) экземпляр класса с документом, предоставленным путем к файлу иLoadOptions . |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Инициализирует новый экземпляр[`Signature`](../signature) экземпляр класса с документом, предоставленным путем к файлу и[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Инициализирует новый экземпляр[`Signature`](../signature) экземпляр класса с документом, предоставленным потоком, параметры загрузкиLoadOptions и настройки[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Инициализирует новый экземпляр[`Signature`](../signature) экземпляр класса с документом, предоставленным путем к файлу,LoadOptions и[`SignatureSettings`](../signaturesettings) . |

## Методы

| Имя | Описание |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Удаляет переданную подпись[`BaseSignature`](../../groupdocs.signature.domain/basesignature) из документа. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Удаляет переданный список подписей[`BaseSignature`](../../groupdocs.signature.domain/basesignature) из документа. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Удаляет подписи определенного списка типов[`SignatureType`](../../groupdocs.signature.domain/signaturetype) из документа. Только подписи, добавленные методом Sign и помеченные как Signatures[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) будет удален. Поддерживаются следующие типы подписи: Текст, Изображение, Цифровая, Штрих-код, QR-код |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Удаляет переданный список подписей[`BaseSignature`](../../groupdocs.signature.domain/basesignature) из документа. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Удаляет подписи определенного типа[`SignatureType`](../../groupdocs.signature.domain/signaturetype) из документа. Только подписи, добавленные методом Sign и помеченные как Signatures[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) будет удален. Поддерживаются следующие типы подписи: Текст, Изображение, Цифровая, Штрих-код, QR-код |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Удаляет подпись по ее конкретному идентификатору подписи из документа. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Реализовать интерфейс IDisposable для очистки внутренних ресурсов |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Генерирует предварительный просмотр страниц документа. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Получает информацию о страницах документа: их размеры, максимальная высота страницы, ширина страницы при максимальной высоте. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Ищет подписи в документе по[`SearchOptions`](../../groupdocs.signature.options/searchoptions) список. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Ищет указанные типы подписей в документе по[`SignatureType`](../../groupdocs.signature.domain/signaturetype) значение. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_3)(SearchOptions) | Ищет подписи в документе по[`SearchOptions`](../../groupdocs.signature.options/searchoptions) варианты. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_2)(SignatureType) | Ищет точный тип подписи в документе по[`SignatureType`](../../groupdocs.signature.domain/signaturetype) значение. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Подписывает документ с коллекцией[`SignOptions`](../../groupdocs.signature.options/signoptions) и сохраняет результат в поток. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Подписывает документ с помощью[`SignOptions`](../../groupdocs.signature.options/signoptions) и сохраняет результат в поток. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Подписывает документ с коллекцией[`SignOptions`](../../groupdocs.signature.options/signoptions) и сохраняет результат в указанный путь к файлу. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Подписывает документ с помощью[`SignOptions`](../../groupdocs.signature.options/signoptions) и сохраняет результат в указанный путь к файлу. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Подписывает документ с коллекцией[`SignOptions`](../../groupdocs.signature.options/signoptions)и сохраняет результат в поток с предопределенными[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Подписывает документ с помощью[`SignOptions`](../../groupdocs.signature.options/signoptions)и сохраняет результат в поток с предопределенными[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Подписывает документ с коллекцией[`SignOptions`](../../groupdocs.signature.options/signoptions) и сохраняет результат в указанный путь к файлу с предопределенным[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Подписывает документ с помощью[`SignOptions`](../../groupdocs.signature.options/signoptions) и сохраняет результат в указанный путь к файлу с предопределенным[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Обновляет переданную подпись[`BaseSignature`](../../groupdocs.signature.domain/basesignature) в документе. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Обновляет переданные подписи[`BaseSignature`](../../groupdocs.signature.domain/basesignature) в документе. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Проверяет подписи документа со списком данных VerifyOptions. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Проверяет подписи документов с заданными данными VerifyOptions. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Генерирует предварительный просмотр подписи на основе заданных SignOptions.[`SignOptions`](../../groupdocs.signature.options/signoptions) |

## События

| Имя | Описание |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Происходит после завершения процесса поиска сигнатуры. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Происходит при изменении хода процесса поиска сигнатур. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Происходит при запуске процесса поиска подписи. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Происходит после завершения процесса подписания документа. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Происходит при изменении хода процесса подписания документа. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Происходит при запуске процесса подписания документа. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Происходит после завершения процесса проверки подписи. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Происходит при изменении хода процесса проверки подписи. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Происходит при запуске процесса проверки подписи. |

### Примечания

**Узнать больше**

* Подробнее о возможностях GroupDocs.Signature: [Руководство разработчика GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Смотрите также

* пространство имен [GroupDocs.Signature](../../groupdocs.signature)
* сборка [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
