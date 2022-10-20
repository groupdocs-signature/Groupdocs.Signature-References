---
title: ImageMetadataSignature
second_title: Справочник по API GroupDocs.Signature для .NET
description: Содержит свойства подписи метаданных изображения.
type: docs
weight: 550
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
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Создает подпись метаданных изображения с идентификатором и значением |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Получить или установить дату создания подписи. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Получает или задает реализацию[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) интерфейс для кодирования и декодирования свойств подписи Value. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Получить флаг, указывающий, была ли эта подпись удалена из документа. Это свойство используется только для записей журнала истории документа, чтобы сохранить список удаленных подписей. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Значение только для чтения для получения описания стандартной подписи метаданных изображения |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Определяет высоту подписи. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | Идентификатор подписи метаданных изображения. См.ImageMetadataSignatures класс, содержащий стандартную подпись с предопределенным значением идентификатора. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Получить или установить флаг, чтобы указать, является ли этот компонент подписью или содержимым документа. Это свойство используется с методом Update для установки элемента в качестве подписи (истина) или элемента документа (ложь). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Указывает левую позицию подписи. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Получить или установить дату модификации подписи. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Указывает уникальное имя метаданных. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Указывает, что подпись страницы была найдена на. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Уникальный идентификатор подписи для изменения подписи в документе с помощью методов Update или Delete. Это свойство будет установлено автоматически после вызова метода Sign или Search. Если это свойство было сохранено до того, как его можно будет установить вручную для управления подписью. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Указывает тип подписи. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Значение только для чтения для получения размера метаданных value |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Указывает верхнее положение подписи. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Указывает объект метаданных. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Определяет ширину подписи. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Экземпляр подписи метаданных клонирования. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Клонировать экземпляр подписи метаданных изображения с заданным значением. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Перезаписывает метод Equals для сравнения свойств подписи |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Получить объект из значения подписи метаданных через десериализацию. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Получить объект из текста подписи метаданных через десериализацию. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | Переопределяет метод GetHashCode |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Преобразует в логическое значение. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Преобразует в DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Преобразует в DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Преобразует в десятичное число. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Преобразует в десятичное число. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Преобразуется в Double. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Преобразуется в Double. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Преобразует в целое число. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Преобразует в длинное. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Преобразует в число с плавающей запятой. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Преобразует в число с плавающей запятой. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Преобразует в строку с переопределением метода ToString() |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Преобразует в строку с указанным форматом |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Преобразует в строку с указанным форматом |

### Смотрите также

* class [MetadataSignature](../metadatasignature)
* пространство имен [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* сборка [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
