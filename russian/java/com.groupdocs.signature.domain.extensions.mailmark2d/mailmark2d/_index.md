---
title: "Mailmark2D"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Класс для кодирования и декодирования текста, встроенного в Royal Mail 2D Mailmark"
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

Класс для кодирования и декодирования текста, встроенного в Royal Mail 2D Mailmark

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Mailmark2D()](#Mailmark2D--) | Создаёт комбинированные данные Royal Mail Mailmark с значениями первичных и вторичных данных по умолчанию. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getUPUCountryID()](#getUPUCountryID--) | Определяет идентификатор страны UPU. Максимальная длина: 4 символа. |
|
|  | [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Определяет идентификатор страны UPU. Максимальная длина: 4 символа. |
|
|  | [getInformationTypeID()](#getInformationTypeID--) | Определяет полезную нагрузку штрих‑кода Royal Mail Mailmark для каждого типа продукта. |
|
|  | [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Определяет полезную нагрузку штрих‑кода Royal Mail Mailmark для каждого типа продукта. |
|
|  | [getVersionID()](#getVersionID--) | Определяет версию штрих‑кода в соответствии с каждым идентификатором типа информации. |
|
|  | [getClass_()](#getClass---) | Определяет класс элемента. |
|
|  | [setClass(String value)](#setClass-java.lang.String-) | Определяет класс элемента. |
|
|  | [getSupplyChainID()](#getSupplyChainID--) | Определяет уникальную группу клиентов, участвующих в рассылке. |
|
|  | [setSupplyChainID(int value)](#setSupplyChainID-int-) | Определяет уникальную группу клиентов, участвующих в рассылке. |
|
|  | [getItemID()](#getItemID--) | Определяет уникальный элемент в рамках идентификатора цепочки поставок. |
|
|  | [setItemID(int value)](#setItemID-int-) | Определяет уникальный элемент в рамках идентификатора цепочки поставок. |
|
|  | [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Содержит почтовый индекс адреса доставки с DPS |
Если внутри страны, почтовый индекс/DP содержит следующее количество символов.
|
|  | [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Содержит почтовый индекс адреса доставки с DPS |
Если внутри страны, почтовый индекс/DP содержит следующее количество символов.
|
|  | [getRTSFlag()](#getRTSFlag--) | Флаг, указывающий, какой уровень услуги возврата отправителю запрашивается. |
|
|  | [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Флаг, указывающий, какой уровень услуги возврата отправителю запрашивается. |
|
|  | [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Содержит почтовый индекс возврата отправителю, но без DPS. |
|
|  | [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Содержит почтовый индекс возврата отправителю, но без DPS. |
|
|  | [getCustomerContent()](#getCustomerContent--) | Опциональное пространство для использования клиентом. |
|
|  | [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Опциональное пространство для использования клиентом. |
|
|  | [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Режим кодирования штрих‑кода DataMatrix. |
|
|  | [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | Режим кодирования штрих‑кода DataMatrix. |
|
|  | [getDataMatrixType()](#getDataMatrixType--) | Тип 2D Mailmark определяет размер штрих‑кода Data Matrix. |
|
|  | [setDataMatrixType(int value)](#setDataMatrixType-int-) | Тип 2D Mailmark определяет размер штрих‑кода Data Matrix. |
|
|  | [deepClone()](#deepClone--) | Получает копию этого объекта. |
|
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


Создаёт комбинированные данные Royal Mail Mailmark с значениями первичных и вторичных данных по умолчанию.


### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


Определяет идентификатор страны UPU. Максимальная длина: 4 символа.


**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


Определяет идентификатор страны UPU. Максимальная длина: 4 символа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


Определяет полезную нагрузку штрих‑кода Royal Mail Mailmark для каждого типа продукта.

<br />

*** ** * ** ***

Допустимые значения: "0" - Внутренняя сортировка и несортировка "A" - Онлайн‑почтовый сервис "B" - Франкирование "C" - Консолидация

<br />



**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


Определяет полезную нагрузку штрих‑кода Royal Mail Mailmark для каждого типа продукта.

<br />

*** ** * ** ***

Допустимые значения: "0" - Внутренняя сортировка и несортировка "A" - Онлайн‑почтовый сервис "B" - Франкирование "C" - Консолидация

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


Определяет версию штрих‑кода в соответствии с каждым идентификатором типа информации.

<br />

*** ** * ** ***

Допустимые значения: "1" - в настоящее время используется только это значение (по умолчанию) "0" и от "2" до "9" и от "A" до "Z" зарезервированы для потенциального будущего использования.

<br />



**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


Определяет класс элемента.

<br />

*** ** * ** ***

Допустимые значения: "1" - 1C (розничный) "2" - 2C (розничный) "3" - Economy (розничный) "5" - Deferred (розничный) "8" - Premium (сетевой доступ) "9" - Standard (сетевой доступ)

<br />



**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


Определяет класс элемента.

<br />

*** ** * ** ***

Допустимые значения: "1" - 1C (розничный) "2" - 2C (розничный) "3" - Economy (розничный) "5" - Deferred (розничный) "8" - Premium (сетевой доступ) "9" - Standard (сетевой доступ)

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


Определяет уникальную группу клиентов, участвующих в рассылке.
Максимальное значение: 9999999.


**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


Определяет уникальную группу клиентов, участвующих в рассылке.
Максимальное значение: 9999999.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


Определяет уникальный элемент в рамках идентификатора цепочки поставок.
Каждый штрих-код Mailmark должен содержать идентификатор, чтобы его можно было уникально идентифицировать как минимум 90 дней.
Максимальное значение: 99999999.


**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


Определяет уникальный элемент в рамках идентификатора цепочки поставок.
Каждый штрих-код Mailmark должен содержать идентификатор, чтобы его можно было уникально идентифицировать как минимум 90 дней.
Максимальное значение: 99999999.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


Содержит почтовый индекс адреса доставки с DPS
Если внутри страны, почтовый индекс/DP содержит следующее количество символов.
Область (1 или 2 символа)
Район(1 или 2 символа)
Сектор(1 символ)
Блок(2 символа)
DPS (2 символа).
Почтовый индекс и DPS должны соответствовать действительному формату PAF®. Максимальная длина — 9.


**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


Содержит почтовый индекс адреса доставки с DPS
Если внутри страны, почтовый индекс/DP содержит следующее количество символов.
Область (1 или 2 символа)
Район(1 или 2 символа)
Сектор(1 символ)
Блок(2 символа)
DPS (2 символа).
Почтовый индекс и DPS должны соответствовать действительному формату PAF®. Максимальная длина — 9.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


Флаг, указывающий, какой уровень услуги «Возврат отправителю» запрашивается. Максимальная длина — 1


**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


Флаг, указывающий, какой уровень услуги «Возврат отправителю» запрашивается. Максимальная длина — 1


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


Содержит почтовый индекс возврата отправителю, но без DPS.
PC (без DPS) должен соответствовать формату PAF®.


**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


Содержит почтовый индекс возврата отправителю, но без DPS.
PC (без DPS) должен соответствовать формату PAF®.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


Опциональное пространство для использования клиентом.

<br />

*** ** * ** ***

Максимальная длина по типу [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Тип 7: 6 символов Тип 9: 45 символов Тип 29: 25 символов

<br />



**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


Опциональное пространство для использования клиентом.

<br />

*** ** * ** ***

Максимальная длина по типу [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Тип 7: 6 символов Тип 9: 45 символов Тип 29: 25 символов

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public final int getCustomerContentEncodeMode()
```


Режим кодирования штрих‑кода DataMatrix. Значение по умолчанию: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Returns:**
int
### setCustomerContentEncodeMode(int value) {#setCustomerContentEncodeMode-int-}
```
public final void setCustomerContentEncodeMode(int value)
```


Режим кодирования штрих‑кода DataMatrix. Значение по умолчанию: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getDataMatrixType() {#getDataMatrixType--}
```
public final int getDataMatrixType()
```


Тип 2D Mailmark определяет размер штрих‑кода Data Matrix.


**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


Тип 2D Mailmark определяет размер штрих‑кода Data Matrix.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Получает копию этого объекта.


**Returns:**
java.lang.Object
