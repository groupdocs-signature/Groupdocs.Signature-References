---
title: "StampSignOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет параметры подписи штампа."
type: docs
weight: 17
url: /ru/java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

Представляет параметры подписи штампа.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [StampSignOptions()](#StampSignOptions--) | Инициализирует новый экземпляр класса StampSignOptions со значениями по умолчанию. |
|
|  | [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | Инициализирует новый экземпляр класса StampSignOptions с параметрами выравнивания. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getStampType()](#getStampType--) | Получает или задает тип штампа. |
|
|  | [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | Получает или задает тип штампа. |
|
|  | [getOuterLines()](#getOuterLines--) | Список внешних линий, отображаемых в виде концентрических кругов. |
|
|  | [getInnerLines()](#getInnerLines--) | Список внутренних линий, отображаемых как набор прямоугольников. |
|
|  | [getBackground()](#getBackground--) | Получает или задает фон штампа. |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Получает или задает фон штампа. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Получает или задает цвет фона подписи. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | Получает или задает цвет фона подписи. |
|
|  | [getBackgroundBrush()](#getBackgroundBrush--) | Получает или задает кисть фона подписи. |
|
|  | [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | Получает или задает кисть фона подписи. |
|
|  | [getBackgroundColorCropType()](#getBackgroundColorCropType--) | Получает или задает тип обрезки фонового цвета подписи. |
|
|  | [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | Получает или задает тип обрезки фонового цвета подписи. |
|
|  | [getBackgroundImageCropType()](#getBackgroundImageCropType--) | Получает или задает тип обрезки фонового изображения подписи. |
|
|  | [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | Получает или задает тип обрезки фонового изображения подписи. |
|
|  | [toString()](#toString--) | Переопределить преобразование строки |
|
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


Инициализирует новый экземпляр класса StampSignOptions со значениями по умолчанию.


### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


Инициализирует новый экземпляр класса StampSignOptions с параметрами выравнивания.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | слева | int | Координата X левого верхнего края подписи штампа |
|
|  | верх | int | Координата Y левого верхнего края подписи штампа |
|
|  | ширина | int | Ширина подписи штампа |
|
|  | высота | int | Высота подписи штампа |
|

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


Получает или задает тип штампа.
Значение по умолчанию — Round.


**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


Получает или задает тип штампа.
Значение по умолчанию — Round.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


Список внешних линий, отображаемых в виде концентрических кругов.


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


Список внутренних линий, отображаемых как набор прямоугольников.


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Получает или задает фон штампа.


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Получает или задает фон штампа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Получает или задает цвет фона подписи.


**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


Получает или задает цвет фона подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


Получает или задает кисть фона подписи. Значение по умолчанию — null.


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


Получает или задает кисть фона подписи. Значение по умолчанию — null.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


Получает или задает тип обрезки фонового цвета подписи.


**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


Получает или задает тип обрезки фонового цвета подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


Получает или задает тип обрезки фонового изображения подписи.


**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


Получает или задает тип обрезки фонового изображения подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### toString() {#toString--}
```
public String toString()
```


Переопределить преобразование строки


**Returns:**
java.lang.String -
