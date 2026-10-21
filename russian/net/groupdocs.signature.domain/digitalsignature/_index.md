---
title: "DigitalSignature"
second_title: "GroupDocs.Signature for .NET API Reference"
description: "Содержит свойства цифровой подписи."
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

## Свойства

| Имя | Описание |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Получает или задает сертификат X509. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Указывает пользовательское имя хранилища сертификата. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Указывает расположение хранилища сертификата |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Указывает имя хранилища сертификата. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Получает или задает комментарий цели подписи. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Получить или установить дату создания подписи. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Получить флаг, указывающий, была ли эта подпись удалена из документа. Это свойство используется только для записей журнала истории документа, чтобы сохранять список удаленных подписей. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Указывает высоту подписи. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Получить или установить флаг, указывающий, является ли этот компонент подписью или содержимым документа. Это свойство используется с методом Update для установки элемента как подписи (true) или как элемента документа (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Сохраняет значение true, если эта цифровая подпись действительна и документ не был изменён. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Указывает левое положение подписи. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Получить или установить дату изменения подписи. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Указывает страницу, на которой была найдена подпись. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Уникальный идентификатор подписи для изменения подписи в документе с помощью методов Update или Delete. Это свойство будет установлено автоматически после вызова метода Sign или Search. Если это свойство было сохранено ранее, его можно установить вручную для манипуляции подписью. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Указывает тип подписи. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Получает или задает время подписи документа. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Получает отпечаток сертификата. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Указывает верхнее положение подписи. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Указывает ширину подписи. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | Тип XAdES [`XAdESType`](./xadestype). Значение по умолчанию — None (XAdES отключён). В данный момент тип подписи XAdES поддерживается только для документов Spreadsheet. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Клонировать экземпляр Barcode Signature. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Переопределяет метод Equals для сравнения свойств подписи |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Переопределяет метод GetHashCode |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Загрузить цифровые подписи из всех системных хранилищ сертификатов X509. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Загрузить цифровые подписи из хранилища сертификатов. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_3)(string) | Загрузить цифровые подписи из хранилища сертификатов. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Загрузить цифровые подписи из цифрового хранилища сертификатов, расположенного в определённом месте. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_4)(string, StoreLocation) | Загрузить цифровые подписи из цифрового хранилища сертификатов, расположенного в определённом месте. |

### См. также

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
