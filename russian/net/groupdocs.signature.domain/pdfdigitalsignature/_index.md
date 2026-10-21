---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature for .NET API Reference"
description: "Содержит свойства цифровой подписи PDF."
type: docs
weight: 840
url: /ru/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Содержит свойства цифровой подписи PDF.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Инициализировать Pdf Digital Signature без сертификата. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Создать Pdf Digital signature с указанным сертификатом. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Инициализировать Pdf Digital Signature на основе указанного хранилища X509. Будет использован первый сертификат из указанного хранилища. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Создать Pdf Digital signature на основе указанного хранилища X509 и индекса сертификата. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Получает или задает сертификат X509. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Указывает пользовательское имя хранилища сертификата. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Указывает расположение хранилища сертификата |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Указывает имя хранилища сертификата. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Получает или задает комментарий цели подписи. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Информация, предоставленная подписантом, позволяющая получателю связаться с подписантом для проверки подписи, например номер телефона. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Получить или установить дату создания подписи. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Получить флаг, указывающий, была ли эта подпись удалена из документа. Это свойство используется только для записей журнала истории документа, чтобы сохранять список удаленных подписей. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Указывает высоту подписи. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Получить или установить флаг, указывающий, является ли этот компонент подписью или содержимым документа. Это свойство используется с методом Update для установки элемента как подписи (true) или как элемента документа (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Сохраняет значение true, если эта цифровая подпись действительна и документ не был изменён. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Указывает левое положение подписи. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | Имя хоста CPU или физическое местоположение подписи. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Получить или установить дату изменения подписи. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Указывает страницу, на которой была найдена подпись. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | Причина подписи, например (I agreeРІР‚В¦). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Принудительно показывать/скрывать свойства подписи. Если ShowProperties равно true, поле подписи имеет предопределённый формат отображения Digitally signed by {[`ContactInfo`](./contactinfo)} Date: {Date} Reason: {[`Reason`](./reason)} Location: {[`Location`](./location)} ShowProperties по умолчанию равно true. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Уникальный идентификатор подписи для изменения подписи в документе с помощью методов Update или Delete. Это свойство будет установлено автоматически после вызова метода Sign или Search. Если это свойство было сохранено ранее, его можно установить вручную для манипуляции подписью. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Указывает тип подписи. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Получает или задает время подписи документа. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Получает отпечаток сертификата. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Отметка времени для Pdf digital signature. Значение по умолчанию — null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Указывает верхнее положение подписи. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Тип Pdf digital signature. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Указывает ширину подписи. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | Тип XAdES [`XAdESType`](../digitalsignature/xadestype). Значение по умолчанию — None (XAdES отключён). В данный момент тип подписи XAdES поддерживается только для документов Spreadsheet. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Клонировать экземпляр Barcode Signature. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Переопределяет метод Equals для сравнения свойств подписи |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Переопределяет метод GetHashCode |

### См. также

* class [DigitalSignature](../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
