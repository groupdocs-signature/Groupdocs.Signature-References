---
title: DigitalSignature
second_title: Справочник по API GroupDocs.Signature для .NET
description: Содержит свойства цифровой подписи.
type: docs
weight: 150
url: /ru/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

Содержит свойства цифровой подписи.

```csharp
public class DigitalSignature : BaseSignature
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Инициализировать цифровую подпись с параметрами по умолчанию. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Инициализировать цифровую подпись с известным SignatureId. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Создать цифровую подпись с указанным сертификатом. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Создать цифровую подпись на основе указанного хранилища X509. Будет использован первый сертификат из указанного хранилища. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Создать цифровую подпись на основе указанного хранилища X509 и индекса сертификата. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Получает или задает сертификат X509. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Указывает расположение хранилища сертификата |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Указывает имя хранилища сертификата. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Получает или задает комментарий к цели подписания. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Получить или установить дату создания подписи. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Получить флаг, указывающий, была ли эта подпись удалена из документа. Это свойство используется только для записей журнала истории документа, чтобы сохранить список удаленных подписей. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Определяет высоту подписи. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Получить или установить флаг, чтобы указать, является ли этот компонент подписью или содержимым документа. Это свойство используется с методом Update для установки элемента в качестве подписи (истина) или элемента документа (ложь). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Остается истинным, если эта цифровая подпись действительна и документ не был подделан. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Указывает левую позицию подписи. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Получить или установить дату модификации подписи. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Указывает, что подпись страницы была найдена на. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Уникальный идентификатор подписи для изменения подписи в документе с помощью методов Update или Delete. Это свойство будет установлено автоматически после вызова метода Sign или Search. Если это свойство было сохранено до того, как его можно будет установить вручную для управления подписью. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Указывает тип подписи. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Получает или задает время подписания документа. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Получает отпечаток сертификата. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Указывает верхнее положение подписи. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Определяет ширину подписи. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | Тип XAdES[`XAdESType`](./xadestype) . Значение по умолчанию — None (XAdES выключен). На данный момент тип подписи XAdES поддерживается только для электронных таблиц. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Клонировать экземпляр подписи штрих-кода. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Перезаписывает метод Equals для сравнения свойств подписи |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Переопределяет метод GetHashCode |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Загрузить цифровую подпись из всех системных хранилищ сертификатов X509. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Загрузить цифровую подпись из переданного хранилища сертификатов X509. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Загрузить цифровую подпись из переданного хранилища сертификатов X509. |

### Смотрите также

* class [BaseSignature](../basesignature)
* пространство имен [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* сборка [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
