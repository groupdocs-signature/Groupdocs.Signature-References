---
title: "MetadataSignature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Содержит свойства подписи метаданных."
type: docs
weight: 12
url: /ru/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

Содержит свойства подписи метаданных.

## Методы

| Метод | Описание |
| --- | --- |
|  | [getName()](#getName--) | Указывает уникальное имя метаданных. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Указывает уникальное имя метаданных. |
|
|  | [getValue()](#getValue--) | Указывает объект метаданных. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Указывает объект метаданных. |
|
|  | [getType()](#getType--) | Указывает тип значения метаданных. |
|
|  | [setType(int value)](#setType-int-) | Указывает тип значения метаданных. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств подписи Value. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств подписи Value. |
|
|  | [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | Получить объект из Metadata Signature Value при десериализации. |
|
|  | [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Получить объект из Metadata Signature Text при десериализации. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Переопределяет метод Equals для сравнения свойств подписи |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
|  | [toBoolean()](#toBoolean--) | Преобразует в логический тип. |
|
|  | [toInteger()](#toInteger--) | Преобразует в целое число. |
|
|  | [toDouble()](#toDouble--) | Преобразует в тип Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Преобразует в тип Double. |
|
|  | [toSingle()](#toSingle--) | Преобразует в тип float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Преобразует в тип float. |
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
|  | [deepClone()](#deepClone--) | Клонировать экземпляр Metadata Signature. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Клонировать экземпляр Metadata Signature с заданным значением. |
|
### getName() {#getName--}
```
public final String getName()
```


Указывает уникальное имя метаданных.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Указывает уникальное имя метаданных.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Указывает объект метаданных.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Указывает объект метаданных.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

### getType() {#getType--}
```
public final int getType()
```


Указывает тип значения метаданных.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Указывает тип значения метаданных.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств подписи Value.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств подписи Value.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


Получить объект из Metadata Signature Value при десериализации.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - экземпляр объекта T


T
: Тип объекта для десериализации из значения Metadata

### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


Получить объект из Metadata Signature Text при десериализации.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Установить пользовательскую реализацию шифрования данных |


T
: Тип объекта для десериализации из значения метаданных
|

**Returns:**
T -
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


### toDouble() {#toDouble--}
```
public double toDouble()
```


Преобразует в тип Double.


**Returns:**
double - Возвращает значение подписи метаданных как Double.

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

### toSingle() {#toSingle--}
```
public float toSingle()
```


Преобразует в тип float.


**Returns:**
float - Возвращает значение подписи метаданных как float.

<br />

*** ** * ** ***

Выбрасывает исключение, если значение метаданных не может быть преобразовано. Если исходное значение основано на строке, будет использована информация о культуре по умолчанию из свойств SignatureSettings, SignatureSettings.DefaultCulture().

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
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

<br />

*** ** * ** ***

Преобразует логическое свойство в "True" или "False". Для другого типа данных будет использован провайдер формата данных по умолчанию.

<br />


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


Клонировать экземпляр Metadata Signature с заданным значением.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.Object | Значение для нового клонированного объекта. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.

