---
title: "SwissAddress"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет адрес кредитора или должника."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.domain.extensions.swissqr/swissaddress/
---
**Inheritance:**
java.lang.Object
```
public class SwissAddress
```

Представляет адрес кредитора или должника.
Вы можете задать улицу, номер дома, почтовый индекс и город (структурированный тип адреса)
или строка адреса 1 и 2 (тип комбинированных элементов адреса).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SwissAddress()](#SwissAddress--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getName()](#getName--) | Получает или задает имя, либо имя и фамилию физического лица, либо |
название компании юридического лица.
|
|  | [setName(String value)](#setName-java.lang.String-) | Получает или задает имя, либо имя и фамилию физического лица, либо |
название компании юридического лица.
|
|  | [getAddressLine1()](#getAddressLine1--) | Получает или задает строку адреса 1. |
|
|  | [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Получает или задает строку адреса 1. |
|
|  | [getAddressLine2()](#getAddressLine2--) | Получает или задает строку адреса 2. |
|
|  | [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Получает или задает строку адреса 2. |
|
|  | [getStreet()](#getStreet--) | Получает или задает улицу. |
|
|  | [setStreet(String value)](#setStreet-java.lang.String-) | Получает или задает улицу. |
|
|  | [getHouseNo()](#getHouseNo--) | Получает или задает номер дома. |
|
|  | [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Получает или задает номер дома. |
|
|  | [getPostalCode()](#getPostalCode--) | Получает или задает почтовый индекс. |
|
|  | [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Получает или задает почтовый индекс. |
|
|  | [getTown()](#getTown--) | Получает или задает город или населённый пункт. |
|
|  | [setTown(String value)](#setTown-java.lang.String-) | Получает или задает город или населённый пункт. |
|
|  | [getCountryCode()](#getCountryCode--) | Получает или задает двухбуквенный код страны ISO. |
|
|  | [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Получает или задает двухбуквенный код страны ISO. |
|
### SwissAddress() {#SwissAddress--}
```
public SwissAddress()
```


### getName() {#getName--}
```
public final String getName()
```


Получает или задает имя, либо имя и фамилию физического лица, либо
название компании юридического лица.
Значение: имя.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Получает или задает имя, либо имя и фамилию физического лица, либо
название компании юридического лица.
Значение: имя.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getAddressLine1() {#getAddressLine1--}
```
public final String getAddressLine1()
```


Получает или задает строку адреса 1.
Строка адреса 1 содержит название улицы, номер дома или абонентский ящик.
Это поле используется только для адресов с комбинированными элементами и является необязательным.
Значение: строка адреса 1.


**Returns:**
java.lang.String
### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public final void setAddressLine1(String value)
```


Получает или задает строку адреса 1.
Строка адреса 1 содержит название улицы, номер дома или абонентский ящик.
Это поле используется только для адресов с комбинированными элементами и является необязательным.
Значение: строка адреса 1.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getAddressLine2() {#getAddressLine2--}
```
public final String getAddressLine2()
```


Получает или задает строку адреса 2.
Строка адреса 2 содержит почтовый индекс и город.
Это поле используется только для адресов с комбинированными элементами. Для этого типа оно обязательно.
Значение: строка адреса 2.


**Returns:**
java.lang.String
### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public final void setAddressLine2(String value)
```


Получает или задает строку адреса 2.
Строка адреса 2 содержит почтовый индекс и город.
Это поле используется только для адресов с комбинированными элементами. Для этого типа оно обязательно.
Значение: строка адреса 2.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getStreet() {#getStreet--}
```
public final String getStreet()
```


Получает или задает улицу.
Улица должна указываться без номера дома.
Это поле используется только для структурированных адресов и является необязательным.
Значение: улица.


**Returns:**
java.lang.String
### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


Получает или задает улицу.
Улица должна указываться без номера дома.
Это поле используется только для структурированных адресов и является необязательным.
Значение: улица.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getHouseNo() {#getHouseNo--}
```
public final String getHouseNo()
```


Получает или задает номер дома.
Это поле используется только для структурированных адресов и является необязательным.
Значение: номер дома.


**Returns:**
java.lang.String
### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public final void setHouseNo(String value)
```


Получает или задает номер дома.
Это поле используется только для структурированных адресов и является необязательным.
Значение: номер дома.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


Получает или задает почтовый индекс.
Это поле используется только для структурированных адресов. Для этого типа оно обязательно.
Значение: почтовый индекс.


**Returns:**
java.lang.String
### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Получает или задает почтовый индекс.
Это поле используется только для структурированных адресов. Для этого типа оно обязательно.
Значение: почтовый индекс.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getTown() {#getTown--}
```
public final String getTown()
```


Получает или задает город или населённый пункт.
Это поле используется только для структурированных адресов. Для этого типа оно обязательно.
Значение: город или населённый пункт.


**Returns:**
java.lang.String
### setTown(String value) {#setTown-java.lang.String-}
```
public final void setTown(String value)
```


Получает или задает город или населённый пункт.
Это поле используется только для структурированных адресов. Для этого типа оно обязательно.
Значение: город или населённый пункт.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


Получает или задает двухбуквенный код страны ISO.
Код страны обязателен, если только весь адрес не содержит null или пустых значений.
Значение: ISO-код страны.


**Returns:**
java.lang.String
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


Получает или задает двухбуквенный код страны ISO.
Код страны обязателен, если только весь адрес не содержит null или пустых значений.
Значение: ISO-код страны.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

