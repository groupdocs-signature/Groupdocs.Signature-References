---
title: "Углы"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет углы квадратного графического объекта."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

Представляет углы квадратного графического объекта.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Corners()](#Corners--) | Инициализирует новый экземпляр класса Corners, используя нулевые значения. |
|
|  | [Corners(double all)](#Corners-double-) | Инициализирует новый экземпляр класса Corners, используя предоставленное значение для всех углов. |
|
|  | [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | Инициализирует новый экземпляр класса Corners, используя предоставленные значения. |
|
## Поля

| Поле | Описание |
| --- | --- |
|  | [Empty](#Empty) | Предоставляет объект Corners без данных. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getAll()](#getAll--) | Получает или задает значение для всех углов. |
|
|  | [setAll(double value)](#setAll-double-) | Получает или задает значение для всех углов. |
|
|  | [getTopLeft()](#getTopLeft--) | Получает или задает значение верхнего левого угла. |
|
|  | [setTopLeft(double value)](#setTopLeft-double-) | Получает или задает значение верхнего левого угла. |
|
|  | [getTopRight()](#getTopRight--) | Получает или задает значение верхнего правого угла. |
|
|  | [setTopRight(double value)](#setTopRight-double-) | Получает или задает значение верхнего правого угла. |
|
|  | [getBottomLeft()](#getBottomLeft--) | Получает или задает значение нижнего левого угла. |
|
|  | [setBottomLeft(double value)](#setBottomLeft-double-) | Получает или задает значение нижнего левого угла. |
|
|  | [getBottomRight()](#getBottomRight--) | Получает или задает значение нижнего правого угла. |
|
|  | [setBottomRight(double value)](#setBottomRight-double-) | Получает или задает значение нижнего правого угла. |
|
|  | [deepClone()](#deepClone--) | Получает копию этого объекта. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Переопределить метод equals |
|
|  | [hashCode()](#hashCode--) | Переопределяет получение уникального значения хэш-кода |
|
|  | [toString()](#toString--) | Переопределяет преобразование в строку. |
|
### Corners() {#Corners--}
```
public Corners()
```


Инициализирует новый экземпляр класса Corners, используя нулевые значения.


### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


Инициализирует новый экземпляр класса Corners, используя предоставленное значение для всех углов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | все | double | Значение, которое будет использоваться для отступа всех углов. |
|

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


Инициализирует новый экземпляр класса Corners, используя предоставленные значения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | topLeft | double | Значение верхнего левого угла. |
|
|  | topRight | double | Значение верхнего правого угла. |
|
|  | bottomLeft | double | Значение нижнего левого угла. |
|
|  | bottomRight | double | Значение нижнего правого угла. |
|

### Empty {#Empty}
```
public static final Corners Empty
```


Предоставляет объект Corners без данных.


### getAll() {#getAll--}
```
public final double getAll()
```


Получает или задает значение для всех углов.
Изменение любой частичной грани, например верхнего правого, делает это свойство равным 0;


**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


Получает или задает значение для всех углов.
Изменение любой частичной грани, например верхнего правого, делает это свойство равным 0;


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


Получает или задает значение верхнего левого угла.


**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


Получает или задает значение верхнего левого угла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


Получает или задает значение верхнего правого угла.


**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


Получает или задает значение верхнего правого угла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


Получает или задает значение нижнего левого угла.


**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


Получает или задает значение нижнего левого угла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


Получает или задает значение нижнего правого угла.


**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


Получает или задает значение нижнего правого угла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Получает копию этого объекта.


**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Переопределить метод equals


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | obj | java.lang.Object | Экземпляр для сравнения. |
|

**Returns:**
boolean - Возвращает true, если свойства объектов равны.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Переопределяет получение уникального значения хэш-кода


**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


Переопределяет преобразование в строку.


**Returns:**
java.lang.String -
