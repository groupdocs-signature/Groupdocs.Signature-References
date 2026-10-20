---
title: "ImageSignOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет параметры подписи изображения."
type: docs
weight: 13
url: /ru/java/com.groupdocs.signature.options.sign/imagesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency), com.aspose.ms.System.IDisposable
```
public class ImageSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency, System.IDisposable
```

Представляет параметры подписи изображения.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [ImageSignOptions()](#ImageSignOptions--) | Инициализирует новый экземпляр класса ImageSignOptions со значениями по умолчанию. |
|
|  | [ImageSignOptions(String imageFilePath)](#ImageSignOptions-java.lang.String-) | Инициализирует новый экземпляр класса ImageSignOptions с файлом изображения. |
|
|  | [ImageSignOptions(InputStream imageStream)](#ImageSignOptions-java.io.InputStream-) | Инициализирует новый экземпляр класса ImageSignOptions с потоком изображения. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | Получает или задает путь к файлу изображения подписи. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Получает или задает путь к файлу изображения подписи. |
|
|  | [getImageStream()](#getImageStream--) | Получает или задает поток изображения подписи. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Получает или задает поток изображения подписи. |
|
|  | [getLeft()](#getLeft--) | Левая позиция X подписи на странице документа в измерительных значениях |
(пиксели, проценты или миллиметры см. [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setLeft(int value)](#setLeft-int-) | Левая позиция X подписи на странице документа в измерительных значениях |
(пиксели, проценты или миллиметры см. [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getTop()](#getTop--) | Верхняя позиция Y подписи на странице документа в измерительных значениях |
(пиксели, проценты или миллиметры см. [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setTop(int value)](#setTop-int-) | Верхняя позиция Y подписи на странице документа в измерительных значениях |
(пиксели, проценты или миллиметры см. [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getWidth()](#getWidth--) | Ширина подписи на странице документа в измерительных значениях |
(пиксели, проценты или миллиметры [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setWidth(int value)](#setWidth-int-) | Ширина подписи на странице документа в измерительных значениях |
(пиксели, проценты или миллиметры [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getHeight()](#getHeight--) | Высота подписи на странице документа в измерительных значениях |
(пиксели, проценты или миллиметры см. [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setHeight(int value)](#setHeight-int-) | Высота подписи на странице документа в измерительных значениях |
(пиксели, проценты или миллиметры см. [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getLocationMeasureType()](#getLocationMeasureType--) | Тип измерения (пиксели, проценты или миллиметры) для свойств Left и Top. |
|
|  | [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | Тип измерения (пиксели, проценты или миллиметры) для свойств Left и Top. |
|
|  | [getSizeMeasureType()](#getSizeMeasureType--) | Тип измерения (пиксели, проценты или миллиметры) для свойств Width и Height. |
|
|  | [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | Тип измерения (пиксели, проценты или миллиметры) для свойств Width и Height. |
|
|  | [getStretch()](#getStretch--) | Режим растяжения на странице документа. |
|
|  | [setStretch(int value)](#setStretch-int-) | Режим растяжения на странице документа. |
|
|  | [getRotationAngle()](#getRotationAngle--) | Угол поворота подписи на странице документа (по часовой стрелке). |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | Угол поворота подписи на странице документа (по часовой стрелке). |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Горизонтальное выравнивание подписи на странице документа. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Горизонтальное выравнивание подписи на странице документа. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Вертикальное выравнивание подписи на странице документа. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Вертикальное выравнивание подписи на странице документа. |
|
|  | [getMargin()](#getMargin--) | Получает или задает пространство между краями Sign и Document. |
|
|  | [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | Получает или задает пространство между краями Sign и Document. |
|
|  | [getMarginMeasureType()](#getMarginMeasureType--) | Получает или задает тип измерения (пиксели, проценты или миллиметры) для Margin. |
|
|  | [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Получает или задает тип измерения (пиксели, проценты или миллиметры) для Margin. |
|
|  | [getTransparency()](#getTransparency--) | Получает или задает прозрачность подписи (значение от 0.0 (непрозрачный) до 1.0 (прозрачный)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Получает или задает прозрачность подписи (значение от 0.0 (непрозрачный) до 1.0 (прозрачный)). |
|
|  | [getShapePosition()](#getShapePosition--) | Определяет, где форма должна отображаться в макете документа. |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | Определяет, где форма должна отображаться в макете документа. |
|
|  | [getRectangle()](#getRectangle--) | Прямоугольник области для размещения изображения в документе. |
|
|  | [getBorder()](#getBorder--) | Укажите настройки границы |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Укажите настройки границы |
|
|  | [toString()](#toString--) | Переопределить преобразование строки. |
|
|  | [fromBase64(String base64Content)](#fromBase64-java.lang.String-) | Создает новый экземпляр класса ImageSignOptions с предопределенным изображением из Base64. |
|
|  | [dispose()](#dispose--) | Очищает внутренние ресурсы |
|
### ImageSignOptions() {#ImageSignOptions--}
```
public ImageSignOptions()
```


Инициализирует новый экземпляр класса ImageSignOptions со значениями по умолчанию.


### ImageSignOptions(String imageFilePath) {#ImageSignOptions-java.lang.String-}
```
public ImageSignOptions(String imageFilePath)
```


Инициализирует новый экземпляр класса ImageSignOptions с файлом изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | Путь к файлу изображения |
|

### ImageSignOptions(InputStream imageStream) {#ImageSignOptions-java.io.InputStream-}
```
public ImageSignOptions(InputStream imageStream)
```


Инициализирует новый экземпляр класса ImageSignOptions с потоком изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | Поток изображения |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Получает или задает путь к файлу изображения подписи.
Это свойство используется только если ImageStream не указан.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Получает или задает путь к файлу изображения подписи.
Это свойство используется только если ImageStream не указан.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Получает или задает поток изображения подписи.
Если это свойство указано, оно всегда используется вместо ImageGuid.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Получает или задает поток изображения подписи.
Если это свойство указано, оно всегда используется вместо ImageGuid.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.io.InputStream |  |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Левая позиция X подписи на странице документа в измерительных значениях
(пиксели, проценты или миллиметры см. [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(работает, если горизонтальное выравнивание не указано).


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Левая позиция X подписи на странице документа в измерительных значениях
(пиксели, проценты или миллиметры см. [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(работает, если горизонтальное выравнивание не указано).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Верхняя позиция Y подписи на странице документа в измерительных значениях
(пиксели, проценты или миллиметры см. [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(работает, если вертикальное выравнивание не указано).


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Верхняя позиция Y подписи на странице документа в измерительных значениях
(пиксели, проценты или миллиметры см. [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(работает, если вертикальное выравнивание не указано).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ширина подписи на странице документа в измерительных значениях
(пиксели, проценты или миллиметры [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ширина подписи на странице документа в измерительных значениях
(пиксели, проценты или миллиметры [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Высота подписи на странице документа в измерительных значениях
(пиксели, проценты или миллиметры см. [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Высота подписи на странице документа в измерительных значениях
(пиксели, проценты или миллиметры см. [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


Тип измерения (пиксели, проценты или миллиметры) для свойств Left и Top.


**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


Тип измерения (пиксели, проценты или миллиметры) для свойств Left и Top.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


Тип измерения (пиксели, проценты или миллиметры) для свойств Width и Height.


**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


Тип измерения (пиксели, проценты или миллиметры) для свойств Width и Height.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


Режим растяжения на странице документа.


**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


Режим растяжения на странице документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Угол поворота подписи на странице документа (по часовой стрелке).


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Угол поворота подписи на странице документа (по часовой стрелке).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Горизонтальное выравнивание подписи на странице документа.


**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Горизонтальное выравнивание подписи на странице документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Вертикальное выравнивание подписи на странице документа.


**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Вертикальное выравнивание подписи на странице документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


Получает или задает пространство между краями Sign и Document.
(работает ТОЛЬКО если указано горизонтальное или вертикальное выравнивание).


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


Получает или задает пространство между краями Sign и Document.
(работает ТОЛЬКО если указано горизонтальное или вертикальное выравнивание).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


Получает или задает тип измерения (пиксели, проценты или миллиметры) для Margin.


**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


Получает или задает тип измерения (пиксели, проценты или миллиметры) для Margin.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Получает или задает прозрачность подписи (значение от 0.0 (непрозрачный) до 1.0 (прозрачный)). Значение по умолчанию — 0 (непрозрачный).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Получает или задает прозрачность подписи (значение от 0.0 (непрозрачный) до 1.0 (прозрачный)). Значение по умолчанию — 0 (непрозрачный).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


Определяет, где форма должна отображаться в макете документа.


**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


Определяет, где форма должна отображаться в макете документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


Прямоугольник области для размещения изображения в документе.


**Returns:**
java.awt.Rectangle
### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Укажите настройки границы


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Укажите настройки границы


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### toString() {#toString--}
```
public String toString()
```


Переопределить преобразование строки.


**Returns:**
java.lang.String -
### fromBase64(String base64Content) {#fromBase64-java.lang.String-}
```
public static ImageSignOptions fromBase64(String base64Content)
```


Создает новый экземпляр класса ImageSignOptions с предопределенным изображением из Base64.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | base64Content | java.lang.String | Содержимое изображения в формате строки Base64 |
|

**Returns:**
[ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions) - 
### dispose() {#dispose--}
```
public final void dispose()
```


Очищает внутренние ресурсы


