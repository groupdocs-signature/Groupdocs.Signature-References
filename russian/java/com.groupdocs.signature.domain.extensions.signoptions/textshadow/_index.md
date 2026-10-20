---
title: "TextShadow"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет свойства теней текста для текстовых подписей."
type: docs
weight: 13
url: /ru/java/com.groupdocs.signature.domain.extensions.signoptions/textshadow/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class TextShadow extends SignatureExtension
```

Представляет свойства теней текста для текстовых подписей.
Результат может различаться в зависимости от типа подписи и формата документа.
TextShadow рекомендуется использовать с подписью TextAsImage для всех поддерживаемых типов документов,
а также с простой TextSignature и TextSignature в качестве водяного знака для Cells (.xslx) и Slides (.pptx).
Simple TextSignature для Words (.docx) также рекомендуется, но имеет ограниченную функциональность.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [TextShadow()](#TextShadow--) | Создаёт TextShadow с параметрами по умолчанию. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getDistance()](#getDistance--) | Получает или задает расстояние от текста до тени. |
|
|  | [setDistance(double value)](#setDistance-double-) | Получает или задает расстояние от текста до тени. |
|
|  | [getAngle()](#getAngle--) | Получает или задает угол размещения тени относительно текста. |
|
|  | [setAngle(double value)](#setAngle-double-) | Получает или задает угол размещения тени относительно текста. |
|
|  | [getColor()](#getColor--) | Получает или задает цвет тени. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Получает или задает цвет тени. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Получает или задает цвет тени. |
|
|  | [getTransparency()](#getTransparency--) | Получает или задает прозрачность тени. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Получает или задает прозрачность тени. |
|
|  | [getBlur()](#getBlur--) | Получает или задает размытие тени. |
|
|  | [setBlur(double value)](#setBlur-double-) | Получает или задает размытие тени. |
|
### TextShadow() {#TextShadow--}
```
public TextShadow()
```


Создаёт TextShadow с параметрами по умолчанию.


### getDistance() {#getDistance--}
```
public final double getDistance()
```


Получает или задает расстояние от текста до тени.
Значение по умолчанию равно 1.


**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Получает или задает расстояние от текста до тени.
Значение по умолчанию равно 1.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


Получает или задает угол размещения тени относительно текста.
Значение по умолчанию равно 0.


**Returns:**
double
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Получает или задает угол размещения тени относительно текста.
Значение по умолчанию равно 0.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Получает или задает цвет тени.
Значение по умолчанию — чёрный.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Получает или задает цвет тени.
Значение по умолчанию — чёрный.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Получает или задает цвет тени.
Значение по умолчанию — чёрный.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Получает или задает прозрачность тени.
Значение по умолчанию равно 0.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Получает или задает прозрачность тени.
Значение по умолчанию равно 0.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### getBlur() {#getBlur--}
```
public final double getBlur()
```


Получает или задает размытие тени.
Значение по умолчанию равно 4.


**Returns:**
double
### setBlur(double value) {#setBlur-double-}
```
public final void setBlur(double value)
```


Получает или задает размытие тени.
Значение по умолчанию равно 4.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

