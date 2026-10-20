---
title: "Отступ"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет информацию о заполнении или отступе, связанную с элементом."
type: docs
weight: 13
url: /ru/java/com.groupdocs.signature.domain/padding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Padding implements Cloneable
```

Представляет информацию о заполнении или отступе, связанную с элементом.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Padding()](#Padding--) | Инициализирует новый экземпляр класса Padding, используя нулевые значения. |
|
|  | [Padding(int all)](#Padding-int-) | Инициализирует новый экземпляр класса Padding, используя заданный размер отступа для всех сторон. |
|
|  | [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | Инициализирует новый экземпляр класса Padding, используя заданные размеры отступов. |
|
## Поля

| Поле | Описание |
| --- | --- |
|  | [Empty](#Empty) | Предоставляет объект Padding без отступов. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getAll()](#getAll--) | Получает или задает значение отступа для всех сторон. |
|
|  | [setAll(int value)](#setAll-int-) | Получает или задает значение отступа для всех сторон. |
|
|  | [getLeft()](#getLeft--) | Получает или задает значение отступа для левой стороны. |
|
|  | [setLeft(int value)](#setLeft-int-) | Получает или задает значение отступа для левой стороны. |
|
|  | [getRight()](#getRight--) | Получает или задает значение отступа для правой стороны. |
|
|  | [setRight(int value)](#setRight-int-) | Получает или задает значение отступа для правой стороны. |
|
|  | [getTop()](#getTop--) | Получает или задает значение отступа для верхней стороны. |
|
|  | [setTop(int value)](#setTop-int-) | Получает или задает значение отступа для верхней стороны. |
|
|  | [getBottom()](#getBottom--) | Получает или задает значение отступа для нижней стороны. |
|
|  | [setBottom(int value)](#setBottom-int-) | Получает или задает значение отступа для нижней стороны. |
|
|  | [getHorizontal()](#getHorizontal--) | Получает комбинированный отступ для правой и левой сторон. |
|
|  | [getVertical()](#getVertical--) | Получает комбинированный отступ для верхней и нижней сторон. |
|
|  | [deepClone()](#deepClone--) | Получает копию этого объекта. |
|
|  | [toString()](#toString--) | Переопределяет преобразование в строку |
|
### Padding() {#Padding--}
```
public Padding()
```


Инициализирует новый экземпляр класса Padding, используя нулевые значения.


### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


Инициализирует новый экземпляр класса Padding, используя заданный размер отступа для всех сторон.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | все | int | Количество единиц измерения, используемых для отступов всех сторон. |
|

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


Инициализирует новый экземпляр класса Padding, используя заданные размеры отступов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | слева | int | Размер левого отступа. |
|
|  | право | int | Размер правого отступа. |
|
|  | верх | int | Размер верхнего отступа. |
|
|  | нижний | int | Размер нижнего отступа. |
|

### Empty {#Empty}
```
public static final Padding Empty
```


Предоставляет объект Padding без отступов.


### getAll() {#getAll--}
```
public final int getAll()
```


Получает или задает значение отступа для всех сторон.
Изменение любой частичной грани, такой как слева или сверху, делает это свойство равным 0;


**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


Получает или задает значение отступа для всех сторон.
Изменение любой частичной грани, такой как слева или сверху, делает это свойство равным 0;


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Получает или задает значение отступа для левой стороны.


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Получает или задает значение отступа для левой стороны.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


Получает или задает значение отступа для правой стороны.


**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Получает или задает значение отступа для правой стороны.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Получает или задает значение отступа для верхней стороны.


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Получает или задает значение отступа для верхней стороны.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


Получает или задает значение отступа для нижней стороны.


**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Получает или задает значение отступа для нижней стороны.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


Получает комбинированный отступ для правой и левой сторон.


**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


Получает комбинированный отступ для верхней и нижней сторон.


**Returns:**
int
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Получает копию этого объекта.


**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```


Переопределяет преобразование в строку


**Returns:**
java.lang.String -
