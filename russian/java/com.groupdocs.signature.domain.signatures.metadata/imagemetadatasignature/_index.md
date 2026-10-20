---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Содержит свойства подписи метаданных изображения."
type: docs
weight: 11
url: /ru/java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

Содержит свойства подписи метаданных изображения.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | Создает Image Metadata Signature с Id и значением |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getId()](#getId--) | Идентификатор Image Metadata signature. |
|
|  | [setId(int value)](#setId-int-) | Идентификатор Image Metadata signature. |
|
|  | [getSize()](#getSize--) | Только для чтения значение для получения размера значения Metadata |
|
|  | [setSize(int value)](#setSize-int-) | Только для чтения значение для получения размера значения Metadata |
|
|  | [getDescription()](#getDescription--) | Только для чтения значение для получения описания стандартной Image Metadata signature |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Переопределяет метод Equals для сравнения свойств подписи |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
|  | [deepClone()](#deepClone--) | Клонировать экземпляр Metadata Signature. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Клонировать экземпляр Image Metadata Signature с заданным значением. |
|
|  | [toBoolean()](#toBoolean--) | Преобразует в логический тип. |
|
|  | [toInteger()](#toInteger--) | Преобразует в целое число. |
|
|  | [toLong()](#toLong--) | Преобразует в long. |
|
|  | [toSingle()](#toSingle--) | Преобразует в тип float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Преобразует в тип float. |
|
|  | [toDouble()](#toDouble--) | Преобразует в тип Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Преобразует в тип Double. |
|
|  | [toDecimal()](#toDecimal--) | Преобразует в Decimal. |
|
|  | [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | Преобразует в Decimal. |
|
|  | [toDateTime()](#toDateTime--) | Преобразует в тип DateTime. |
|
|  | [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | Преобразует в тип DateTime. |
|
|  | [toString()](#toString--) | Преобразует в String с переопределённым методом ToString() |
|
|  | [toString(String format)](#toString-java.lang.String-) | Преобразует в String с указанным форматом |
|
|  | [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Преобразует в String с указанным форматом |
|
| [setAsBool(Object value)](#setAsBool-java.lang.Object-) |  |
| [setAsByte(Object value)](#setAsByte-java.lang.Object-) |  |
| [setAsShrt(Object value)](#setAsShrt-java.lang.Object-) |  |
| [setAsWord(Object value)](#setAsWord-java.lang.Object-) |  |
| [setAsSInt(Object value)](#setAsSInt-java.lang.Object-) |  |
| [setAsUInt(Object value)](#setAsUInt-java.lang.Object-) |  |
| [setAsSLng(Object value)](#setAsSLng-java.lang.Object-) |  |
| [setAsULng(Object value)](#setAsULng-java.lang.Object-) |  |
| [setAsSngl(Object value)](#setAsSngl-java.lang.Object-) |  |
| [setAsDbls(Object value)](#setAsDbls-java.lang.Object-) |  |
| [setAsDcml(Object value)](#setAsDcml-java.lang.Object-) |  |
| [setAsDate(Object value)](#setAsDate-java.lang.Object-) |  |
| [setAsStrn(Object value)](#setAsStrn-java.lang.Object-) |  |
| [setAsObjc(Object value)](#setAsObjc-java.lang.Object-) |  |
| [setString(Object value)](#setString-java.lang.Object-) |  |
### ImageMetadataSignature(int id, Object value) {#ImageMetadataSignature-int-java.lang.Object-}
```
public ImageMetadataSignature(int id, Object value)
```


Создает Image Metadata Signature с Id и значением


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | id | int | Уникальный идентификатор имени подписи Image Metadata. См. ссылки для спецификаций тегов Exif, чтобы узнать возможные значения id. |
|
|  | значение | java.lang.Object | Значение метаданных |
|

### getId() {#getId--}
```
public final int getId()
```


Идентификатор Image Metadata signature.
Смотрите класс [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) , который содержит стандартную Signature с предопределенным значением Id.


**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Идентификатор Image Metadata signature.
Смотрите класс [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) , который содержит стандартную Signature с предопределенным значением Id.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


Только для чтения значение для получения размера значения Metadata


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Только для чтения значение для получения размера значения Metadata


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Только для чтения значение для получения описания стандартной Image Metadata signature


**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Переопределяет метод Equals для сравнения свойств подписи


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | подпись | java.lang.Object | Объект подписи для сравнения. |
|

**Returns:**
boolean — Возвращает true, если переданный объект подписи имеет тот же тип и все его свойства равны свойствам этого экземпляра.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Переопределяет метод GetHashCode


**Returns:**
int — Хеш‑код подписи

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Клонировать экземпляр Metadata Signature.


**Returns:**
java.lang.Object — Возвращает клонированный экземпляр Metadata Signature

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Клонировать экземпляр Image Metadata Signature с заданным значением.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.Object | Значение для нового клонированного объекта. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


Преобразует в логический тип.


**Returns:**
boolean - Возвращает значение подписи метаданных как логическое.

<br />

*** ** * ** ***

Выбрасывает исключение, если значение метаданных не может быть преобразовано.

<br />


### toInteger() {#toInteger--}
```
public int toInteger()
```


Преобразует в целое число.


**Returns:**
int - Возвращает значение подписи метаданных как целое число.

<br />

*** ** * ** ***

Выбрасывает исключение, если значение метаданных не может быть преобразовано.

<br />


### toLong() {#toLong--}
```
public final long toLong()
```


Преобразует в long.


**Returns:**
long — Возвращает значение Metadata Signature как long.

<br />

*** ** * ** ***

Выбрасывает исключение, если значение метаданных не может быть преобразовано.

<br />


### toSingle() {#toSingle--}
```
public final float toSingle()
```


Преобразует в тип float.


**Returns:**
float — Возвращает значение Image Metadata Signature как float.

<br />

*** ** * ** ***

Выбрасывает исключение, если значение метаданных не может быть преобразовано. Если исходное значение основано на строке, будет использована информация о культуре по умолчанию из свойств SignatureSettings, SignatureSettings.DefaultCulture.

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
```


Преобразует в тип float.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | провайдер | java.util.Locale | Провайдер формата данных, используемый в операциях преобразования данных. |

<br />

*** ** * ** ***

Выбрасывает исключение, если значение метаданных не может быть преобразовано.

<br />

|

**Returns:**
float - Возвращает значение подписи метаданных как float.

### toDouble() {#toDouble--}
```
public double toDouble()
```


Преобразует в тип Double.


**Returns:**
double — Возвращает значение Image Metadata Signature как Double.

<br />

*** ** * ** ***

Выбрасывает исключение, если значение метаданных не может быть преобразовано. Если исходное значение основано на строке, будет использована информация о культуре по умолчанию из свойств SignatureSettings, SignatureSettings.DefaultCulture.

<br />


### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Преобразует в тип Double.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | провайдер | java.util.Locale | Провайдер формата данных, используемый в операциях преобразования данных. |

<br />

*** ** * ** ***

Выбрасывает исключение, если значение метаданных не может быть преобразовано.

<br />

|

**Returns:**
double - Возвращает значение подписи метаданных как Double.

### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


Преобразует в Decimal.


**Returns:**
java.math.BigDecimal — Возвращает значение Image Metadata Signature как Decimal.

<br />

*** ** * ** ***

Выбрасывает исключение, если значение метаданных не может быть преобразовано. Если исходное значение основано на строке, будет использована информация о культуре по умолчанию из свойств SignatureSettings, SignatureSettings.DefaultCulture.

<br />


### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


Преобразует в Decimal.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | провайдер | java.util.Locale | Провайдер формата данных, используемый в операциях преобразования данных. |

<br />

*** ** * ** ***

Выбрасывает исключение, если значение метаданных не может быть преобразовано.

<br />

|

**Returns:**
java.math.BigDecimal — Возвращает значение Metadata Signature как Decimal.

### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Преобразует в тип DateTime.


**Returns:**
java.util.Date - Возвращает значение подписи метаданных как DateTime.

<br />

*** ** * ** ***

Выбрасывает исключение, если значение метаданных не может быть преобразовано. Если исходное значение основано на строке, будет использована информация о культуре по умолчанию из свойств SignatureSettings, SignatureSettings.DefaultCulture.

<br />


### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


Преобразует в тип DateTime.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | провайдер | java.util.Locale | Провайдер формата данных, используемый в операциях преобразования данных. |

<br />

*** ** * ** ***

Выбрасывает исключение, если значение метаданных не может быть преобразовано.

<br />

|

**Returns:**
java.util.Date - Возвращает значение подписи метаданных как DateTime.

### toString() {#toString--}
```
public String toString()
```


Преобразует в String с переопределённым методом ToString()


**Returns:**
java.lang.String - Возвращает значение подписи метаданных как String.

### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Преобразует в String с указанным форматом


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | формат | java.lang.String | Строка формата данных. |

<br />

*** ** * ** ***

Преобразует логическое свойство в "True" или "False". Информация о культуре по умолчанию будет использована из свойств SignatureSettings, SignatureSettings.DefaultCulture.

<br />

|

**Returns:**
java.lang.String - Возвращает значение подписи метаданных как String.

### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Преобразует в String с указанным форматом


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | формат | java.lang.String | Строка формата данных. |
|
|  | провайдер | java.util.Locale | Провайдер формата данных, используемый в операциях преобразования данных. |

<br />

*** ** * ** ***

Преобразует логическое свойство в "True" или "False".

<br />

|

**Returns:**
java.lang.String - Возвращает значение подписи метаданных как String.

### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

**Returns:**
boolean
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

**Returns:**
boolean
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

**Returns:**
boolean
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

**Returns:**
boolean
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

**Returns:**
boolean
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

**Returns:**
boolean
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

**Returns:**
boolean
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

**Returns:**
boolean
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

**Returns:**
boolean
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

**Returns:**
boolean
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

**Returns:**
boolean
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

**Returns:**
boolean
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

**Returns:**
boolean
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

**Returns:**
boolean
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

