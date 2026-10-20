---
title: "MetadataSearchOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет абстрактные параметры поиска для подписей метаданных."
type: docs
weight: 15
url: /ru/java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

Представляет абстрактные параметры поиска для подписей метаданных.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [MetadataSearchOptions()](#MetadataSearchOptions--) | Инициализирует новый экземпляр класса SearchMetadataOptions со значениями по умолчанию. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getName()](#getName--) | Указывает имя подписи метаданных, если его следует искать и сопоставлять. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Указывает имя подписи метаданных, если его следует искать и сопоставлять. |
|
|  | [getNameMatchType()](#getNameMatchType--) | Получает или задает тип сопоставления имени метаданных при поиске. |
|
|  | [setNameMatchType(int value)](#setNameMatchType-int-) | Получает или задает тип сопоставления имени метаданных при поиске. |
|
|  | [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | Указывает, следует ли включать встроенные свойства документа, такие как статистика документа, информация и т.д., в результат поиска. |
|
|  | [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | Указывает, следует ли включать встроенные свойства документа, такие как статистика документа, информация и т.д., в результат поиска. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств текста или данных подписи QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств текста или данных подписи QR-Code. |
|
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


Инициализирует новый экземпляр класса SearchMetadataOptions со значениями по умолчанию.


### getName() {#getName--}
```
public final String getName()
```


Указывает имя подписи метаданных, если его следует искать и сопоставлять.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Указывает имя подписи метаданных, если его следует искать и сопоставлять.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


Получает или задает поиск по типу совпадения имени метаданных. Используется только когда свойство Name установлено.


**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


Получает или задает поиск по типу совпадения имени метаданных. Используется только когда свойство Name установлено.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


Указывает, следует ли включать встроенные свойства документа, такие как статистика документа, информация и т.д., в результат поиска.
Этот флаг имеет смысл для типов файлов Presentation, Spreadhsheet и Word Processing.


**Returns:**
boolean
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


Указывает, следует ли включать встроенные свойства документа, такие как статистика документа, информация и т.д., в результат поиска.
Этот флаг имеет смысл для типов файлов Presentation, Spreadhsheet и Word Processing.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств текста или данных подписи QR-Code.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств текста или данных подписи QR-Code.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

