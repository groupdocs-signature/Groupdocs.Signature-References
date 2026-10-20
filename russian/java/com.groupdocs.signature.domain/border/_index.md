---
title: "Border"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Экземпляр для хранения свойств линии границы."
type: docs
weight: 11
url: /ru/java/com.groupdocs.signature.domain/border/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class Border implements ITransparency
```

Экземпляр для хранения свойств линии границы.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Border()](#Border--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getDashStyle()](#getDashStyle--) | Получает или задает стиль границы подписи. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | Получает или задает стиль границы подписи. |
|
|  | [getTransparency()](#getTransparency--) | Получает или задает прозрачность границы подписи (значение от 0.0 (непрозрачный) до 1.0 (прозрачный)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Получает или задает прозрачность границы подписи (значение от 0.0 (непрозрачный) до 1.0 (прозрачный)). |
|
|  | [getWeight()](#getWeight--) | Получает или задает толщину границы подписи. |
|
|  | [setWeight(double value)](#setWeight-double-) | Получает или задает толщину границы подписи. |
|
|  | [getColor()](#getColor--) | Получает или задает цвет границы подписи. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Получает или задает цвет границы подписи. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Получает или задает цвет границы подписи. |
|
|  | [getVisible()](#getVisible--) | Получает или задает видимость границы. |
|
| [setVisible(boolean value)](#setVisible-boolean-) |  |
|  | [deepClone()](#deepClone--) | Реализовать интерфейс IClonable. |
|
### Border() {#Border--}
```
public Border()
```


### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Получает или задает стиль границы подписи.


**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Получает или задает стиль границы подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Получает или задает прозрачность границы подписи (значение от 0.0 (непрозрачный) до 1.0 (прозрачный)).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Получает или задает прозрачность границы подписи (значение от 0.0 (непрозрачный) до 1.0 (прозрачный)).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### getWeight() {#getWeight--}
```
public final double getWeight()
```


Получает или задает толщину границы подписи.


**Returns:**
double
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Получает или задает толщину границы подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Получает или задает цвет границы подписи.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Получает или задает цвет границы подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Получает или задает цвет границы подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Получает или задает видимость границы.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Реализовать интерфейс IClonable.


**Returns:**
java.lang.Object — только что созданный экземпляр Border с теми же свойствами.

