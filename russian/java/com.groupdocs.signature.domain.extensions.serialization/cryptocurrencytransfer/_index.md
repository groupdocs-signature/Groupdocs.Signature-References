---
title: "CryptoCurrencyTransfer"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет получателя или перевод криптовалюты для QR-кода."
type: docs
weight: 11
url: /ru/java/com.groupdocs.signature.domain.extensions.serialization/cryptocurrencytransfer/
---
**Inheritance:**
java.lang.Object
```
public class CryptoCurrencyTransfer
```

Представляет перевод криптовалюты (получатель или перевод) для QR‑кода.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CryptoCurrencyTransfer()](#CryptoCurrencyTransfer--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getType()](#getType--) | Получает или задает один из поддерживаемых типов криптовалюты. |
|
|  | [setType(int value)](#setType-int-) | Получает или задает один из поддерживаемых типов криптовалюты. |
|
|  | [getAmount()](#getAmount--) | Получает или задает сумму перевода. |
|
|  | [setAmount(BigDecimal value)](#setAmount-java.math.BigDecimal-) | Получает или задает сумму перевода. |
|
|  | [getAddress()](#getAddress--) | Получает или задает публичный адрес криптовалюты. |
|
|  | [setAddress(String value)](#setAddress-java.lang.String-) | Получает или задает публичный адрес криптовалюты. |
|
|  | [getMessage()](#getMessage--) | Получает или задает необязательное сообщение перевода. |
|
|  | [setMessage(String value)](#setMessage-java.lang.String-) | Получает или задает необязательное сообщение перевода. |
|
|  | [getCustomType()](#getCustomType--) | Получает или задает необязательное сообщение перевода. |
|
|  | [setCustomType(String value)](#setCustomType-java.lang.String-) | Получает или задает необязательное сообщение перевода. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Переопределяет метод Equals для сравнения свойств перевода криптовалюты. |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
### CryptoCurrencyTransfer() {#CryptoCurrencyTransfer--}
```
public CryptoCurrencyTransfer()
```


### getType() {#getType--}
```
public final int getType()
```


Получает или задает один из поддерживаемых типов криптовалюты.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Получает или задает один из поддерживаемых типов криптовалюты.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getAmount() {#getAmount--}
```
public final BigDecimal getAmount()
```


Получает или задает сумму перевода.


**Returns:**
java.math.BigDecimal
### setAmount(BigDecimal value) {#setAmount-java.math.BigDecimal-}
```
public final void setAmount(BigDecimal value)
```


Получает или задает сумму перевода.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.math.BigDecimal |  |

### getAddress() {#getAddress--}
```
public final String getAddress()
```


Получает или задает публичный адрес криптовалюты.


**Returns:**
java.lang.String
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


Получает или задает публичный адрес криптовалюты.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


Получает или задает необязательное сообщение перевода.


**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


Получает или задает необязательное сообщение перевода.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getCustomType() {#getCustomType--}
```
public final String getCustomType()
```


Получает или задает необязательное сообщение перевода.


**Returns:**
java.lang.String
### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public final void setCustomType(String value)
```


Получает или задает необязательное сообщение перевода.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Переопределяет метод Equals для сравнения свойств перевода криптовалюты.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | obj | java.lang.Object | Объект передачи криптовалюты для сравнения. |
|

**Returns:**
boolean - Возвращает true, если переданный объект передачи криптовалюты имеет тот же тип и все его свойства равны свойствам этого экземпляра.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Переопределяет метод GetHashCode


**Returns:**
int - Хеш-код передачи криптовалюты

