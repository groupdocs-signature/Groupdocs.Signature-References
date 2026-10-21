---
title: "CertificateMetadataSignature"
second_title: "GroupDocs.Signature for .NET API Reference"
description: "Содержит свойства подписи метаданных сертификата."
type: docs
weight: 70
url: /ru/net/groupdocs.signature.domain/certificatemetadatasignature/
---
## CertificateMetadataSignature class

Содержит свойства подписи метаданных сертификата.

```csharp
public sealed class CertificateMetadataSignature : MetadataSignature
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CertificateMetadataSignature](certificatemetadatasignature#constructor)(string) | Создаёт подпись метаданных сертификата с предопределённым именем и пустым значением. |
| [CertificateMetadataSignature](certificatemetadatasignature#constructor_1)(string, object) | Создаёт подпись метаданных сертификата с предопределёнными значениями. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Получить или установить дату создания подписи. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Получает или задает реализацию интерфейса [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) для кодирования и декодирования свойств Value подписи. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Получить флаг, указывающий, была ли эта подпись удалена из документа. Это свойство используется только для записей журнала истории документа, чтобы сохранять список удаленных подписей. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Указывает высоту подписи. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Получить или установить флаг, указывающий, является ли этот компонент подписью или содержимым документа. Это свойство используется с методом Update для установки элемента как подписи (true) или как элемента документа (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Указывает левое положение подписи. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Получить или установить дату изменения подписи. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Указывает уникальное имя метаданных. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Указывает страницу, на которой была найдена подпись. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Уникальный идентификатор подписи для изменения подписи в документе с помощью методов Update или Delete. Это свойство будет установлено автоматически после вызова метода Sign или Search. Если это свойство было сохранено ранее, его можно установить вручную для манипуляции подписью. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Указывает тип подписи. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Указывает верхнее положение подписи. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Указывает тип значения метаданных. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Указывает объект метаданных. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Указывает ширину подписи. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/certificatemetadatasignature/clone#clone_1)() | Клонировать экземпляр Metadata Signature. |
| override [Clone](../../groupdocs.signature.domain/certificatemetadatasignature/clone#clone)(object) | Клонировать экземпляр подписи метаданных сертификата с заданным значением. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Переопределяет метод Equals для сравнения свойств подписи |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Получить объект из Metadata Signature Value при десериализации. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Получить объект из Metadata Signature Text при десериализации. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Переопределяет метод GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Преобразует в логическое значение. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Преобразует в DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Преобразует в DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Преобразует в Decimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Преобразует в Decimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Преобразует в Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Преобразует в Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Преобразует в integer. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Преобразует в float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Преобразует в float. |
| override [ToString](../../groupdocs.signature.domain/certificatemetadatasignature/tostring#tostring)() | Преобразует в String с переопределённым методом ToString() |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Преобразует в String с указанным форматом |
| override [ToString](../../groupdocs.signature.domain/certificatemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Преобразует в String с указанным форматом |

### См. также

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
