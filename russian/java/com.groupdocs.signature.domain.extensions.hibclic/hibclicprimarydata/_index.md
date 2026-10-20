---
title: "HIBCLICPrimaryData"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Класс для хранения основных данных HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 12
url: /ru/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

Класс для хранения первичных данных HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | Конструктор по умолчанию ctor() |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Определяет дату кода идентификации маркировщика. |
|
|  | [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Определяет дату кода идентификации маркировщика. |
|
|  | [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Определяет номер продукта или каталога. |
|
|  | [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Определяет номер продукта или каталога. |
|
|  | [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Определяет идентификатор единицы измерения. |
|
|  | [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Определяет идентификатор единицы измерения. |
|
|  | [deepClone()](#deepClone--) | Получает копию этого объекта. |
|
| [getCodetext()](#getCodetext--) |  |
### HIBCLICPrimaryData() {#HIBCLICPrimaryData--}
```
public HIBCLICPrimaryData()
```


Конструктор по умолчанию ctor()


### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public final String getLabelerIdentificationCode()
```


Определяет дату кода идентификации маркировщика. Код идентификации маркировщика должен
быть 4‑символьной буквенно-цифровой строкой, где первый символ всегда буквенный.


**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


Определяет дату кода идентификации маркировщика. Код идентификации маркировщика должен
быть 4‑символьной буквенно-цифровой строкой, где первый символ всегда буквенный.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


Определяет номер продукта или каталога. Номер продукта или каталога должен быть буквенно-цифровым
строкой длиной до 18 символов.


**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


Определяет номер продукта или каталога. Номер продукта или каталога должен быть буквенно-цифровым
строкой длиной до 18 символов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


Определяет идентификатор единицы измерения. Идентификатор единицы измерения должен быть целым числом от 0 до 9.


**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


Определяет идентификатор единицы измерения. Идентификатор единицы измерения должен быть целым числом от 0 до 9.


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
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
