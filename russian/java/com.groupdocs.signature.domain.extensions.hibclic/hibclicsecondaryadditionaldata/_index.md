---
title: "HIBCLICSecondaryAdditionalData"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Класс для хранения вторичных и дополнительных данных HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 13
url: /ru/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

Класс для хранения вторичных и дополнительных данных HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | Конструктор по умолчанию ctor() |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getExpiryDateFormat()](#getExpiryDateFormat--) | Определяет формат даты истечения срока. |
|
|  | [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | Определяет формат даты истечения срока. |
|
|  | [getExpiryDate()](#getExpiryDate--) | Определяет дату истечения срока. |
|
|  | [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | Определяет дату истечения срока. |
|
|  | [getLotNumber()](#getLotNumber--) | Определяет номер партии или лота. |
|
|  | [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Определяет номер партии или лота. |
|
|  | [getSerialNumber()](#getSerialNumber--) | Определяет серийный номер. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Определяет серийный номер. |
|
|  | [getDateOfManufacture()](#getDateOfManufacture--) | Определяет дату производства. |
|
|  | [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | Определяет дату производства. |
|
|  | [getQuantity()](#getQuantity--) | Определяет количество, должно быть целым значением от 0 до 500. |
|
|  | [setQuantity(int value)](#setQuantity-int-) | Определяет количество, должно быть целым значением от 0 до 500. |
|
|  | [getLinkCharacter()](#getLinkCharacter--) | Определяет символ ссылки в выходной строке. |
|
|  | [setLinkCharacter(char value)](#setLinkCharacter-char-) | Определяет символ ссылки в выходной строке. |
|
|  | [deepClone()](#deepClone--) | Получает копию этого объекта. |
|
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


Конструктор по умолчанию ctor()


### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


Определяет формат даты истечения срока.


**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


Определяет формат даты истечения срока.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


Определяет дату истечения срока. Будет использовано, если ExpiryDateFormat не установлен в None.


**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


Определяет дату истечения срока. Будет использовано, если ExpiryDateFormat не установлен в None.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


Определяет номер партии или лота.
Номер партии/лота должен быть буквенно-цифровой строкой длиной до 18 символов.


**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


Определяет номер партии или лота.
Номер партии/лота должен быть буквенно-цифровой строкой длиной до 18 символов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Определяет серийный номер.
Серийный номер должен быть буквенно-цифровой строкой длиной до 18 символов.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Определяет серийный номер.
Серийный номер должен быть буквенно-цифровой строкой длиной до 18 символов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


Определяет дату производства.
Дата производства может быть установлена в DateTime.MinValue, чтобы не использовать это поле.
Значение по умолчанию: DateTime.MinValue


**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


Определяет дату производства.
Дата производства может быть установлена в DateTime.MinValue, чтобы не использовать это поле.
Значение по умолчанию: DateTime.MinValue


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


Определяет количество, должно быть целым значением от 0 до 500.
Количество может быть установлено в -1, чтобы не использовать это поле. Значение по умолчанию: -1


**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


Определяет количество, должно быть целым значением от 0 до 500.
Количество может быть установлено в -1, чтобы не использовать это поле. Значение по умолчанию: -1


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getLinkCharacter() {#getLinkCharacter--}
```
public final char getLinkCharacter()
```


Определяет символ ссылки в выходной строке.


**Returns:**
char
### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public final void setLinkCharacter(char value)
```


Определяет символ ссылки в выходной строке.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | char |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Получает копию этого объекта.


**Returns:**
java.lang.Object
