---
title: "SwissQR"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Класс для кодирования и декодирования текста, встроенного в код SwissQR."
type: docs
weight: 11
url: /ru/java/com.groupdocs.signature.domain.extensions.swissqr/swissqr/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class SwissQR implements IComplexData
```

Класс для кодирования и декодирования текста, встроенного в код SwissQR.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [SwissQR()](#SwissQR--) | Создаёт экземпляр SwissQR. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getAmount()](#getAmount--) | Получает или задаёт сумму платежа. |
|
|  | [setAmount(double value)](#setAmount-double-) | Получает или задаёт сумму платежа. |
|
|  | [getCurrency()](#getCurrency--) | Получает или задаёт валюту платежа. |
|
|  | [setCurrency(String value)](#setCurrency-java.lang.String-) | Получает или задаёт валюту платежа. |
|
|  | [getAccount()](#getAccount--) | Получает или задаёт номер счёта кредитора. |
|
|  | [setAccount(String value)](#setAccount-java.lang.String-) | Получает или задаёт номер счёта кредитора. |
|
|  | [getCreditor()](#getCreditor--) | Получает или задаёт адрес кредитора. |
|
|  | [setCreditor(SwissAddress value)](#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Получает или задаёт адрес кредитора. |
|
|  | [getReference()](#getReference--) | Получает или задает ссылку платежа кредитора. |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | Получает или задает ссылку платежа кредитора. |
|
|  | [getDebtor()](#getDebtor--) | Получает или задает адрес должника. |
|
|  | [setDebtor(SwissAddress value)](#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Получает или задает адрес должника. |
|
|  | [getUnstructuredMessage()](#getUnstructuredMessage--) | Получает или задает дополнительное неструктурированное сообщение. |
|
|  | [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Получает или задает дополнительное неструктурированное сообщение. |
|
|  | [getBillInformation()](#getBillInformation--) | Получает или задает дополнительную структурированную информацию о счете. |
|
|  | [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Получает или задает дополнительную структурированную информацию о счете. |
|
### SwissQR() {#SwissQR--}
```
public SwissQR()
```


Создаёт экземпляр SwissQR.


### getAmount() {#getAmount--}
```
public final double getAmount()
```


Получает или задаёт сумму платежа.
Допустимые значения находятся в диапазоне от 0.01 до 999,999,999.99.
Значение: Сумма платежа.


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Получает или задаёт сумму платежа.
Допустимые значения находятся в диапазоне от 0.01 до 999,999,999.99.
Значение: Сумма платежа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### getCurrency() {#getCurrency--}
```
public final String getCurrency()
```


Получает или задаёт валюту платежа.
Допустимые значения: "CHF" и "EUR".
Значение: Валюта платежа.


**Returns:**
java.lang.String
### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public final void setCurrency(String value)
```


Получает или задаёт валюту платежа.
Допустимые значения: "CHF" и "EUR".
Значение: Валюта платежа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getAccount() {#getAccount--}
```
public final String getAccount()
```


Получает или задаёт номер счёта кредитора.
Номера счетов должны быть действительными IBAN банков Швейцарии или Лихтенштейна.
Пробелы допускаются в номере счета.
Значение: Номер счета кредитора.


**Returns:**
java.lang.String
### setAccount(String value) {#setAccount-java.lang.String-}
```
public final void setAccount(String value)
```


Получает или задаёт номер счёта кредитора.
Номера счетов должны быть действительными IBAN банков Швейцарии или Лихтенштейна.
Пробелы допускаются в номере счета.
Значение: Номер счета кредитора.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getCreditor() {#getCreditor--}
```
public final SwissAddress getCreditor()
```


Получает или задаёт адрес кредитора.
Значение: Адрес кредитора.


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setCreditor(SwissAddress value) {#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setCreditor(SwissAddress value)
```


Получает или задаёт адрес кредитора.
Значение: Адрес кредитора.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Получает или задает ссылку платежа кредитора.
Ссылка обязательна для SwissQR IBAN, т.е. IBAN в диапазоне CHxx30000xxxxxx
до CHxx31999xxxxx.
Если указана, ссылка должна быть либо действительной SwissQR ссылкой (соответствующей
форме ISR) либо действительной ссылкой кредитора согласно ISO 11649 ("RFxxxx").
Обе могут содержать пробелы для форматирования.
Значение: Ссылка платежа кредитора.


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Получает или задает ссылку платежа кредитора.
Ссылка обязательна для SwissQR IBAN, т.е. IBAN в диапазоне CHxx30000xxxxxx
до CHxx31999xxxxx.
Если указана, ссылка должна быть либо действительной SwissQR ссылкой (соответствующей
форме ISR) либо действительной ссылкой кредитора согласно ISO 11649 ("RFxxxx").
Обе могут содержать пробелы для форматирования.
Значение: Ссылка платежа кредитора.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getDebtor() {#getDebtor--}
```
public final SwissAddress getDebtor()
```


Получает или задает адрес должника.
Должник является необязательным. Если он опущен, как установка этого поля в null, так и
установка адреса со всеми null или пустыми значениями допустима.
Значение: Адрес должника.


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setDebtor(SwissAddress value) {#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setDebtor(SwissAddress value)
```


Получает или задает адрес должника.
Должник является необязательным. Если он опущен, как установка этого поля в null, так и
установка адреса со всеми null или пустыми значениями допустима.
Значение: Адрес должника.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public final String getUnstructuredMessage()
```


Получает или задает дополнительное неструктурированное сообщение.
Значение: Неструктурированное сообщение.


**Returns:**
java.lang.String
### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public final void setUnstructuredMessage(String value)
```


Получает или задает дополнительное неструктурированное сообщение.
Значение: Неструктурированное сообщение.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getBillInformation() {#getBillInformation--}
```
public final String getBillInformation()
```


Получает или задает дополнительную структурированную информацию о счете.
Значение: Структурированная информация о счете.


**Returns:**
java.lang.String
### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public final void setBillInformation(String value)
```


Получает или задает дополнительную структурированную информацию о счете.
Значение: Структурированная информация о счете.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

