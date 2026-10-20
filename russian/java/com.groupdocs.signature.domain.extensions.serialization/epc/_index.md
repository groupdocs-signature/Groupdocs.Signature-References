---
title: "EPC"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет QR‑код Европейского совета платежей."
type: docs
weight: 14
url: /ru/java/com.groupdocs.signature.domain.extensions.serialization/epc/
---
**Inheritance:**
java.lang.Object
```
public final class EPC
```

Представляет QR‑код Европейского совета платежей.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [EPC()](#EPC--) | Создаёт новый объект EPC. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getName()](#getName--) | Получает или задает имя получателя. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Получает или задает имя получателя. |
|
|  | [getBIC()](#getBIC--) | Получает или задает BIC получателя длиной до 11 символов. |
|
|  | [setBIC(String value)](#setBIC-java.lang.String-) | Получает или задает BIC получателя длиной до 11 символов. |
|
|  | [getIBAN()](#getIBAN--) | Получает или задает счёт получателя (IBAN). |
|
|  | [setIBAN(String value)](#setIBAN-java.lang.String-) | Получает или задает счёт получателя (IBAN). |
|
|  | [getAmount()](#getAmount--) | Получает или задает сумму. |
|
|  | [setAmount(double value)](#setAmount-double-) | Получает или задает сумму. |
|
|  | [getCode()](#getCode--) | Получает или задает бизнес‑код длиной до 4 символов. |
|
|  | [setCode(String value)](#setCode-java.lang.String-) | Получает или задает бизнес‑код длиной до 4 символов. |
|
|  | [getReference()](#getReference--) | Получает или задает платёжное назначение (максимум 35 символов). |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | Получает или задает платёжное назначение (максимум 35 символов). |
|
|  | [getRemittance()](#getRemittance--) | Получает или задает информацию о платеже (максимум 140 символов). |
|
|  | [setRemittance(String value)](#setRemittance-java.lang.String-) | Получает или задает информацию о платеже (максимум 140 символов). |
|
|  | [getInformation()](#getInformation--) | Получает или задает подсказку. |
|
|  | [setInformation(String value)](#setInformation-java.lang.String-) | Получает или задает подсказку. |
|
|  | [getVersion()](#getVersion--) | Реализация версии EPC / SEPA QR-Code. |
|
|  | [setVersion(String value)](#setVersion-java.lang.String-) | Реализация версии EPC / SEPA QR-Code. |
|
|  | [getCharset()](#getCharset--) | Реализация набора символов EPC / SEPA QR-Code. |
|
|  | [setCharset(String value)](#setCharset-java.lang.String-) | Реализация набора символов EPC / SEPA QR-Code. |
|
|  | [getIdentification()](#getIdentification--) | Идентификация EPC / SEPA QR-Code. |
|
|  | [setIdentification(String value)](#setIdentification-java.lang.String-) | Идентификация EPC / SEPA QR-Code. |
|
|  | [equals(Object source)](#equals-java.lang.Object-) | Перезаписывает метод Equals для сравнения свойств EPC. |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
### EPC() {#EPC--}
```
public EPC()
```


Создаёт новый объект EPC.


### getName() {#getName--}
```
public final String getName()
```


Получает или задает имя получателя. Максимальная длина — 70 символов.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Получает или задает имя получателя. Максимальная длина — 70 символов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getBIC() {#getBIC--}
```
public final String getBIC()
```


Получает или задает BIC получателя длиной до 11 символов.


**Returns:**
java.lang.String
### setBIC(String value) {#setBIC-java.lang.String-}
```
public final void setBIC(String value)
```


Получает или задает BIC получателя длиной до 11 символов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getIBAN() {#getIBAN--}
```
public final String getIBAN()
```


Получает или задает счет получателя (IBAN). IBAN состоит из до 34 буквенно-цифровых символов.


**Returns:**
java.lang.String
### setIBAN(String value) {#setIBAN-java.lang.String-}
```
public final void setIBAN(String value)
```


Получает или задает счет получателя (IBAN). IBAN состоит из до 34 буквенно-цифровых символов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getAmount() {#getAmount--}
```
public final double getAmount()
```


Получает или задает сумму.


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Получает или задает сумму.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### getCode() {#getCode--}
```
public final String getCode()
```


Получает или задает бизнес‑код длиной до 4 символов.


**Returns:**
java.lang.String
### setCode(String value) {#setCode-java.lang.String-}
```
public final void setCode(String value)
```


Получает или задает бизнес‑код длиной до 4 символов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Получает или задает ссылку платежа (максимум 35 символов). Это поле и поле информации о переводе взаимно исключают друг друга.


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Получает или задает ссылку платежа (максимум 35 символов). Это поле и поле информации о переводе взаимно исключают друг друга.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getRemittance() {#getRemittance--}
```
public final String getRemittance()
```


Получает или задает информацию о переводе (максимум 140 символов). Это поле и поле ссылки платежа взаимно исключают друг друга.


**Returns:**
java.lang.String
### setRemittance(String value) {#setRemittance-java.lang.String-}
```
public final void setRemittance(String value)
```


Получает или задает информацию о переводе (максимум 140 символов). Это поле и поле ссылки платежа взаимно исключают друг друга.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getInformation() {#getInformation--}
```
public final String getInformation()
```


Получает или задает подсказку. Максимум 70 символов.


**Returns:**
java.lang.String
### setInformation(String value) {#setInformation-java.lang.String-}
```
public final void setInformation(String value)
```


Получает или задает подсказку. Максимум 70 символов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


Реализация версии EPC / SEPA QR-Code. По умолчанию это значение установлено в 002.


**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


Реализация версии EPC / SEPA QR-Code. По умолчанию это значение установлено в 002.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final String getCharset()
```


Реализация набора символов EPC / SEPA QR-Code. По умолчанию это значение установлено в 1.


**Returns:**
java.lang.String
### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


Реализация набора символов EPC / SEPA QR-Code. По умолчанию это значение установлено в 1.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getIdentification() {#getIdentification--}
```
public final String getIdentification()
```


Идентификация EPC / SEPA QR-Code. По умолчанию это значение установлено в SCT.


**Returns:**
java.lang.String
### setIdentification(String value) {#setIdentification-java.lang.String-}
```
public final void setIdentification(String value)
```


Идентификация EPC / SEPA QR-Code. По умолчанию это значение установлено в SCT.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


Перезаписывает метод Equals для сравнения свойств EPC.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | источник | java.lang.Object | Объект EPC для сравнения. |
|

**Returns:**
boolean - Возвращает true, если переданный объект адреса имеет тот же тип и все его свойства равны свойствам данного экземпляра.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Переопределяет метод GetHashCode


**Returns:**
int - Хеш-код Email

