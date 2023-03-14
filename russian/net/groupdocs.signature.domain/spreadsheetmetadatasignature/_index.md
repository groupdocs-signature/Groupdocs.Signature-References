---
title: SpreadsheetMetadataSignature
second_title: Справочник по API GroupDocs.Signature для .NET
description: Содержит свойства подписи метаданных электронной таблицы.
type: docs
weight: 870
url: /ru/net/groupdocs.signature.domain/spreadsheetmetadatasignature/
---
## SpreadsheetMetadataSignature class

Содержит свойства подписи метаданных электронной таблицы.

```csharp
public sealed class SpreadsheetMetadataSignature : MetadataSignature
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SpreadsheetMetadataSignature](spreadsheetmetadatasignature#constructor)(string) | Создает подпись метаданных электронной таблицы с предопределенным именем и пустым значением. |
| [SpreadsheetMetadataSignature](spreadsheetmetadatasignature#constructor_1)(string, object) | Создает подпись метаданных электронной таблицы с предопределенными значениями. |

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
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Указывает тип значения метаданных. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Указывает объект метаданных. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Определяет ширину подписи. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/spreadsheetmetadatasignature/clone#clone_1)() | Экземпляр подписи метаданных клонирования. |
| override [Clone](../../groupdocs.signature.domain/spreadsheetmetadatasignature/clone#clone)(object) | Клонировать экземпляр подписи метаданных электронной таблицы с заданным значением. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Перезаписывает метод Equals для сравнения свойств подписи |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Получить объект из значения подписи метаданных через десериализацию. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Получить объект из текста подписи метаданных через десериализацию. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Переопределяет метод GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Преобразует в логическое значение. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Преобразует в DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Преобразует в DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Преобразует в десятичное число. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Преобразует в десятичное число. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Преобразуется в Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Преобразуется в Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Преобразует в целое число. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Преобразует в число с плавающей запятой. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Преобразует в число с плавающей запятой. |
| override [ToString](../../groupdocs.signature.domain/spreadsheetmetadatasignature/tostring#tostring)() | Преобразует в строку с переопределением метода ToString() |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Преобразует в строку с указанным форматом |
| override [ToString](../../groupdocs.signature.domain/spreadsheetmetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Преобразует в строку с указанным форматом |

### Смотрите также

* class [MetadataSignature](../metadatasignature)
* пространство имен [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* сборка [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
