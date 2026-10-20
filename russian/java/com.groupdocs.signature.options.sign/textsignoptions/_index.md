---
title: "TextSignOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет параметры подписи текста."
type: docs
weight: 18
url: /ru/java/com.groupdocs.signature.options.sign/textsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class TextSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency
```

Представляет параметры подписи текста.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [TextSignOptions()](#TextSignOptions--) | Инициализирует новый экземпляр класса SignTextOptions со значениями по умолчанию. |
|
|  | [TextSignOptions(String text)](#TextSignOptions-java.lang.String-) | Инициализирует новый экземпляр класса SignTextOptions с текстом. |
|
## Поля

| Поле | Описание |
| --- | --- |
| [DEFAULT_TRANSPARENCY](#DEFAULT-TRANSPARENCY) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getLeft()](#getLeft--) | Левая позиция X подписи на странице документа в измерительных значениях |
(пиксели, проценты или миллиметры см. свойство [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setLeft(int value)](#setLeft-int-) | Левая позиция X подписи на странице документа в измерительных значениях |
(пиксели, проценты или миллиметры см. свойство [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getTop()](#getTop--) | Верхняя позиция Y подписи на странице документа в измерительных значениях |
(пиксели, проценты или миллиметры см. свойство [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setTop(int value)](#setTop-int-) | Верхняя позиция Y подписи на странице документа в измерительных значениях |
(пиксели, проценты или миллиметры см. свойство [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getWidth()](#getWidth--) | Ширина подписи на странице документа в измерительных значениях |
(пиксели, проценты или миллиметры см. свойство [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setWidth(int value)](#setWidth-int-) | Ширина подписи на странице документа в измерительных значениях |
(пиксели, проценты или миллиметры см. свойство [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getHeight()](#getHeight--) | Высота подписи на странице документа в измерительных значениях |
(пиксели, проценты или миллиметры см. свойство [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setHeight(int value)](#setHeight-int-) | Высота подписи на странице документа в измерительных значениях |
(пиксели, проценты или миллиметры см. свойство [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
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
|  | [getText()](#getText--) | Получает или задаёт текст подписи. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Получает или задаёт текст подписи. |
|
|  | [getFont()](#getFont--) | Получает или задаёт шрифт подписи. |
|
|  | [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | Получает или задаёт шрифт подписи. |
|
|  | [getFontOrDefault()](#getFontOrDefault--) | Внутреннее: шрифт, который имел этот экземпляр при создании, или шрифт по умолчанию. |
|
|  | [getForeColor()](#getForeColor--) | Получает или задаёт передний цвет подписи. |
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Получает или задаёт передний цвет подписи. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Получает или задаёт тип реализации текстовой подписи. |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Получает или задаёт тип реализации текстовой подписи. |
|
|  | [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Горизонтальное выравнивание текста внутри подписи. |
|
|  | [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Горизонтальное выравнивание текста внутри подписи. |
|
|  | [getTextVerticalAlignment()](#getTextVerticalAlignment--) | Вертикальное выравнивание текста внутри подписи. |
|
|  | [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | Вертикальное выравнивание текста внутри подписи. |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Получает или задаёт заголовок текстового поля формы, в которое помещается текстовая подпись. |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Получает или задаёт заголовок текстового поля формы, в которое помещается текстовая подпись. |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | Получает или задает тип поля формы, в которое помещается текстовая подпись. |
|
|  | [setFormTextFieldType(int value)](#setFormTextFieldType-int-) | Получает или задает тип поля формы, в которое помещается текстовая подпись. |
|
|  | [getShapeType()](#getShapeType--) | Получает или задает тип фигуры для размещения текста. |
|
|  | [setShapeType(int value)](#setShapeType-int-) | Получает или задает тип фигуры для размещения текста. |
|
|  | [getSignatureID()](#getSignatureID--) | Получает или задает уникальный идентификатор подписи. |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | Получает или задает уникальный идентификатор подписи. |
|
|  | [getBorder()](#getBorder--) | Укажите настройки границы |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Укажите настройки границы |
|
|  | [getBackground()](#getBackground--) | Получает или задает настройки фона подписи. |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Получает или задает настройки фона подписи. |
|
|  | [getNative()](#getNative--) | Получает или задает нативный атрибут. |
|
|  | [setNative(boolean value)](#setNative-boolean-) | Получает или задает нативный атрибут. |
|
|  | [getShapePosition()](#getShapePosition--) | Определяет, где форма должна отображаться в макете документа. |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | Определяет, где форма должна отображаться в макете документа. |
|
|  | [validate()](#validate--) | Внутренний метод для проверки параметров опций. |
|
|  | [toString()](#toString--) | Переопределить преобразование строки. |
|
### TextSignOptions() {#TextSignOptions--}
```
public TextSignOptions()
```


Инициализирует новый экземпляр класса SignTextOptions со значениями по умолчанию.


### TextSignOptions(String text) {#TextSignOptions-java.lang.String-}
```
public TextSignOptions(String text)
```


Инициализирует новый экземпляр класса SignTextOptions с текстом.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | текст | java.lang.String | Текст подписи. |
|

### DEFAULT_TRANSPARENCY {#DEFAULT-TRANSPARENCY}
```
public static final double DEFAULT_TRANSPARENCY
```


### getLeft() {#getLeft--}
```
public final int getLeft()
```


Левая позиция X подписи на странице документа в измерительных значениях
(пиксели, проценты или миллиметры см. свойство [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(работает, если горизонтальное выравнивание не указано).


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Левая позиция X подписи на странице документа в измерительных значениях
(пиксели, проценты или миллиметры см. свойство [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(работает, если горизонтальное выравнивание не указано).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Верхняя позиция Y подписи на странице документа в измерительных значениях
(пиксели, проценты или миллиметры см. свойство [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(работает, если вертикальное выравнивание не указано).


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Верхняя позиция Y подписи на странице документа в измерительных значениях
(пиксели, проценты или миллиметры см. свойство [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
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
(пиксели, проценты или миллиметры см. свойство [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ширина подписи на странице документа в измерительных значениях
(пиксели, проценты или миллиметры см. свойство [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Высота подписи на странице документа в измерительных значениях
(пиксели, проценты или миллиметры см. свойство [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Высота подписи на странице документа в измерительных значениях
(пиксели, проценты или миллиметры см. свойство [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


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

### getText() {#getText--}
```
public final String getText()
```


Получает или задаёт текст подписи.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Получает или задаёт текст подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


Получает или задаёт шрифт подписи.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


Получает или задаёт шрифт подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getFontOrDefault() {#getFontOrDefault--}
```
public final SignatureFont getFontOrDefault()
```


Внутреннее: шрифт, который имел этот экземпляр при создании, или шрифт по умолчанию.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Получает или задаёт передний цвет подписи.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Получает или задаёт передний цвет подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Color |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Получает или задаёт тип реализации текстовой подписи.


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Получает или задаёт тип реализации текстовой подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public final int getTextHorizontalAlignment()
```


Горизонтальное выравнивание текста внутри подписи.
Эта функция поддерживается только для реализаций подписи Image и Annotation.
(см. [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) свойство SignatureImplementation).


**Returns:**
int
### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public final void setTextHorizontalAlignment(int value)
```


Горизонтальное выравнивание текста внутри подписи.
Эта функция поддерживается только для реализаций подписи Image и Annotation.
(см. [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) свойство SignatureImplementation).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


Вертикальное выравнивание текста внутри подписи.
Эта функция поддерживается только для реализации подписи Image.
(см. [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) свойство SignatureImplementation).


**Returns:**
int
### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


Вертикальное выравнивание текста внутри подписи.
Эта функция поддерживается только для реализации подписи Image.
(см. [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) свойство SignatureImplementation).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Получает или задаёт заголовок текстового поля формы, в которое помещается текстовая подпись.
Это свойство может использоваться только с SignatureImplementation = TextToFormField.


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Получает или задаёт заголовок текстового поля формы, в которое помещается текстовая подпись.
Это свойство может использоваться только с SignatureImplementation = TextToFormField.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final int getFormTextFieldType()
```


Получает или задает тип поля формы, в которое помещается текстовая подпись.
Это свойство может использоваться только с SignatureImplementation = TextToFormField.
Значение по умолчанию — AllTextTypes.


**Returns:**
int
### setFormTextFieldType(int value) {#setFormTextFieldType-int-}
```
public final void setFormTextFieldType(int value)
```


Получает или задает тип поля формы, в которое помещается текстовая подпись.
Это свойство может использоваться только с SignatureImplementation = TextToFormField.
Значение по умолчанию — AllTextTypes.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Получает или задает тип фигуры для размещения текста.
Это свойство может использоваться только с SignatureImplementation = TextStamp.
Значение по умолчанию — Rectangle.


**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public final void setShapeType(int value)
```


Получает или задает тип фигуры для размещения текста.
Это свойство может использоваться только с SignatureImplementation = TextStamp.
Значение по умолчанию — Rectangle.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Получает или задает уникальный идентификатор подписи. Он может использоваться в параметрах проверки подписи. Свойство поддерживается только для PDF‑документов.


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Получает или задает уникальный идентификатор подписи. Он может использоваться в параметрах проверки подписи. Свойство поддерживается только для PDF‑документов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

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

### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Получает или задает настройки фона подписи.


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Получает или задает настройки фона подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getNative() {#getNative--}
```
public final boolean getNative()
```


Получает или задает нативный атрибут. Если он установлен, могут использоваться подписи, специфичные для документа.
Нативный текстовый водяной знак для документов WordProcessing отличается от обычного, например.


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Получает или задает нативный атрибут. Если он установлен, могут использоваться подписи, специфичные для документа.
Нативный текстовый водяной знак для документов WordProcessing отличается от обычного, например.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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

### validate() {#validate--}
```
public void validate()
```


Внутренний метод для проверки параметров опций.


### toString() {#toString--}
```
public String toString()
```


Переопределить преобразование строки.


**Returns:**
java.lang.String -
