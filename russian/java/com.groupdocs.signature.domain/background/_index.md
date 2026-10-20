---
title: "Background"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет внешний вид фона."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.domain/background/
---
**Inheritance:**
java.lang.Object
```
public class Background
```

Представляет внешний вид фона.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Background()](#Background--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getColor()](#getColor--) | Получает или задает цвет фона подписи. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Получает или задает цвет фона подписи. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Получает или задает цвет фона подписи. |
|
|  | [getTransparency()](#getTransparency--) | Получает или задает прозрачность фона (значение от 0.0 (непрозрачный) до 1.0 (прозрачный)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Получает или задает прозрачность фона (значение от 0.0 (непрозрачный) до 1.0 (прозрачный)). |
|
|  | [getBrush()](#getBrush--) | Получает или задает кисть фона. |
|
|  | [setBrush(Brush value)](#setBrush-com.groupdocs.signature.domain.extensions.Brush-) | Получает или задает кисть фона. |
|
### Background() {#Background--}
```
public Background()
```


### getColor() {#getColor--}
```
public final Color getColor()
```


Получает или задает цвет фона подписи.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Получает или задает цвет фона подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Получает или задает цвет фона подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Получает или задает прозрачность фона (значение от 0.0 (непрозрачный) до 1.0 (прозрачный)).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Получает или задает прозрачность фона (значение от 0.0 (непрозрачный) до 1.0 (прозрачный)).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Получает или задает кисть фона. Значение по умолчанию — null.
Это свойство ожидает экземпляр реализации объектов Brush.
См. различные классы Brush.


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBrush(Brush value) {#setBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBrush(Brush value)
```


Получает или задает кисть фона. Значение по умолчанию — null.
Это свойство ожидает экземпляр реализации объектов Brush.
См. различные классы Brush.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

