---
title: "MetadataSignature"
second_title: "GroupDocs.Signature for .NET API Reference"
description: "Содержит свойства подписи метаданных."
type: docs
weight: 780
url: /ru/net/groupdocs.signature.domain/metadatasignature/
---
## MetadataSignature class

Содержит свойства подписи метаданных.

```csharp
public abstract class MetadataSignature : BaseSignature
```

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
| override [Clone](../../groupdocs.signature.domain/metadatasignature/clone#clone_1)() | Клонировать экземпляр Metadata Signature. |
| virtual [Clone](../../groupdocs.signature.domain/metadatasignature/clone#clone)(object) | Клонировать экземпляр Metadata Signature с заданным значением. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Переопределяет метод Equals для сравнения свойств подписи |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata#getdata)() | Получить объект из Metadata Signature Value при десериализации. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata#getdata_1)(IDataEncryption) | Получить объект из Metadata Signature Text при десериализации. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Переопределяет метод GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Преобразует в логическое значение. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime#todatetime)() | Преобразует в DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime#todatetime_1)(IFormatProvider) | Преобразует в DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal#todecimal)() | Преобразует в Decimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal#todecimal_1)(IFormatProvider) | Преобразует в Decimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble#todouble)() | Преобразует в Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble#todouble_1)(IFormatProvider) | Преобразует в Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Преобразует в integer. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle#tosingle)() | Преобразует в float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle#tosingle_1)(IFormatProvider) | Преобразует в float. |
| override [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring)() | Преобразует в String с переопределённым методом ToString() |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring_1)(string) | Преобразует в String с указанным форматом |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring_2)(string, IFormatProvider) | Преобразует в String с указанным форматом |

### См. также

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
