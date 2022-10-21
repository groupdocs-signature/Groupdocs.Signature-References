---
title: MetadataSignature
second_title: Справочник по API GroupDocs.Signature для .NET
description: Содержит свойства подписи метаданных.
type: docs
weight: 590
url: /ru/net/groupdocs.signature.domain/metadatasignature/
---
## MetadataSignature class

Содержит свойства подписи метаданных.

```csharp
public abstract class MetadataSignature : BaseSignature
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Получить или установить дату создания подписи. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Получает или задает реализацию[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) интерфейс для кодирования и декодирования свойств подписи Value. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Получить флаг, указывающий, была ли эта подпись удалена из документа. Это свойство используется только для записей журнала истории документа, чтобы сохранить список удаленных подписей. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Определяет высоту подписи. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Получить или установить флаг, чтобы указать, является ли этот компонент подписью или содержимым документа. Это свойство используется с методом Update для установки элемента в качестве подписи (истина) или элемента документа (ложь). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Указывает левую позицию подписи. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Получить или установить дату модификации подписи. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Указывает уникальное имя метаданных. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Указывает, что подпись страницы была найдена на. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Уникальный идентификатор подписи для изменения подписи в документе с помощью методов Update или Delete. Это свойство будет установлено автоматически после вызова метода Sign или Search. Если это свойство было сохранено до того, как его можно будет установить вручную для управления подписью. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Указывает тип подписи. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Указывает верхнее положение подписи. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Указывает объект метаданных. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Определяет ширину подписи. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/metadatasignature/clone#clone_1)() | Экземпляр подписи метаданных клонирования. |
| virtual [Clone](../../groupdocs.signature.domain/metadatasignature/clone#clone)(object) | Копировать экземпляр подписи метаданных с заданным значением. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Перезаписывает метод Equals для сравнения свойств подписи |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata#getdata)() | Получить объект из значения подписи метаданных через десериализацию. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata#getdata_1)(IDataEncryption) | Получить объект из текста подписи метаданных через десериализацию. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Переопределяет метод GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Преобразует в логическое значение. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime#todatetime)() | Преобразует в DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime#todatetime_1)(IFormatProvider) | Преобразует в DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal#todecimal)() | Преобразует в десятичное число. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal#todecimal_1)(IFormatProvider) | Преобразует в десятичное число. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble#todouble)() | Преобразуется в Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble#todouble_1)(IFormatProvider) | Преобразуется в Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Преобразует в целое число. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle#tosingle)() | Преобразует в число с плавающей запятой. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle#tosingle_1)(IFormatProvider) | Преобразует в число с плавающей запятой. |
| override [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring)() | Преобразует в строку с переопределением метода ToString() |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring_1)(string) | Преобразует в строку с указанным форматом |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring_2)(string, IFormatProvider) | Преобразует в строку с указанным форматом |

### Смотрите также

* class [BaseSignature](../basesignature)
* пространство имен [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* сборка [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
