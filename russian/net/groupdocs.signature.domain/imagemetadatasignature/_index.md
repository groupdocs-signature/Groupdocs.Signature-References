---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature for .NET API Reference"
description: "Содержит свойства подписи метаданных изображения."
type: docs
weight: 740
url: /ru/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Содержит свойства подписи метаданных изображения.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Создаёт Image Metadata Signature с Id и значением |

## Свойства

| Имя | Описание |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Получить или установить дату создания подписи. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Получает или задает реализацию интерфейса [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) для кодирования и декодирования свойств Value подписи. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Получить флаг, указывающий, была ли эта подпись удалена из документа. Это свойство используется только для записей журнала истории документа, чтобы сохранять список удаленных подписей. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Только для чтения значение для получения описания стандартной Image Metadata signature |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Указывает высоту подписи. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | Идентификатор подписи Image Metadata. См. класс ImageMetadataSignatures, который содержит стандартную Signature с предопределённым значением Id. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Получить или установить флаг, указывающий, является ли этот компонент подписью или содержимым документа. Это свойство используется с методом Update для установки элемента как подписи (true) или как элемента документа (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Указывает левое положение подписи. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Получить или установить дату изменения подписи. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Указывает уникальное имя метаданных. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Указывает страницу, на которой была найдена подпись. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Уникальный идентификатор подписи для изменения подписи в документе с помощью методов Update или Delete. Это свойство будет установлено автоматически после вызова метода Sign или Search. Если это свойство было сохранено ранее, его можно установить вручную для манипуляции подписью. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Указывает тип подписи. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Только для чтения значение для получения размера значения Metadata |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Указывает верхнее положение подписи. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Указывает тип значения метаданных. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Указывает объект метаданных. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Указывает ширину подписи. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Клонировать экземпляр Metadata Signature. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Создать клон экземпляра Image Metadata Signature с заданным значением. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Переопределяет метод Equals для сравнения свойств подписи |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Получить объект из Metadata Signature Value при десериализации. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Получить объект из Metadata Signature Text при десериализации. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | Переопределяет метод GetHashCode |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Преобразует в логическое значение. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Преобразует в DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Преобразует в DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Преобразует в Decimal. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Преобразует в Decimal. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Преобразует в Double. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Преобразует в Double. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Преобразует в integer. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Преобразует в long. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Преобразует в float. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Преобразует в float. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Преобразует в String с переопределённым методом ToString() |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Преобразует в String с указанным форматом |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Преобразует в String с указанным форматом |

### См. также

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
