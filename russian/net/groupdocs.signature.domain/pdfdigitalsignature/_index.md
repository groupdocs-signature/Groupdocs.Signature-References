---
title: PdfDigitalSignature
second_title: Справочник по API GroupDocs.Signature для .NET
description: Содержит свойства цифровой подписи Pdf.
type: docs
weight: 630
url: /ru/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Содержит свойства цифровой подписи Pdf.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Инициализировать цифровую подпись Pdf без сертификата. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Создать цифровую подпись Pdf с указанным сертификатом. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Инициализировать цифровую подпись Pdf на основе указанного хранилища X509. Будет использован первый сертификат из указанного хранилища. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Создать цифровую подпись Pdf на основе указанного хранилища X509 и индекса сертификата. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Получает или задает сертификат X509. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Указывает расположение хранилища сертификата |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Указывает имя хранилища сертификата. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Получает или задает комментарий к цели подписания. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Информация, предоставленная подписывающей стороной, чтобы получатель мог связаться с подписывающей стороной для проверки подписи, например номер телефона. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Получить или установить дату создания подписи. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Получить флаг, указывающий, была ли эта подпись удалена из документа. Это свойство используется только для записей журнала истории документа, чтобы сохранить список удаленных подписей. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Определяет высоту подписи. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Получить или установить флаг, чтобы указать, является ли этот компонент подписью или содержимым документа. Это свойство используется с методом Update для установки элемента в качестве подписи (истина) или элемента документа (ложь). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Остается истинным, если эта цифровая подпись действительна и документ не был подделан. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Указывает левую позицию подписи. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | Имя хоста ЦП или физическое расположение подписи. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Получить или установить дату модификации подписи. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Указывает, что подпись страницы была найдена на. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | Причина подписания, типа (согласен). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Принудительно показать/скрыть свойства подписи. Если ShowProperties имеет значение true, поле подпись имеет предопределенный формат отображения Цифровая подпись {[`ContactInfo`](./contactinfo)} Дата: {Дата} Причина: {[`Reason`](./reason)} Местоположение: {[`Location`](./location) } ShowProperties по умолчанию имеет значение true. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Уникальный идентификатор подписи для изменения подписи в документе с помощью методов Update или Delete. Это свойство будет установлено автоматически после вызова метода Sign или Search. Если это свойство было сохранено до того, как его можно будет установить вручную для управления подписью. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Указывает тип подписи. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Получает или задает время подписания документа. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Получает отпечаток сертификата. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Отметка времени для цифровой подписи Pdf. Значение по умолчанию — null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Указывает верхнее положение подписи. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Тип цифровой подписи Pdf. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Определяет ширину подписи. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | Тип XAdES[`XAdESType`](../digitalsignature/xadestype) . Значение по умолчанию — None (XAdES выключен). На данный момент тип подписи XAdES поддерживается только для электронных таблиц. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Клонировать экземпляр подписи штрих-кода. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Перезаписывает метод Equals для сравнения свойств подписи |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Переопределяет метод GetHashCode |

### Смотрите также

* class [DigitalSignature](../digitalsignature)
* пространство имен [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* сборка [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
