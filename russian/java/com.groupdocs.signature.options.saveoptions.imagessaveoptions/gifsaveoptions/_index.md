---
title: "GifSaveOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Параметры сохранения в формате GIF для документов‑изображений."
type: docs
weight: 15
url: /ru/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

Параметры сохранения в формате GIF для документов‑изображений.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [GifSaveOptions()](#GifSaveOptions--) | Создает GifSaveOptions со значениями по умолчанию. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Получает или задает индекс фонового цвета GIF. |
|
|  | [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Получает или задает индекс фонового цвета GIF. |
|
|  | [getColorResolution()](#getColorResolution--) | Получает или задает разрешение цвета GIF. |
|
|  | [setColorResolution(byte value)](#setColorResolution-byte-) | Получает или задает разрешение цвета GIF. |
|
|  | [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Получает или задает значение, указывающее, применяется ли коррекция палитры. |
|
|  | [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Получает или задает значение, указывающее, применяется ли коррекция палитры. |
|
|  | [hasTrailer()](#hasTrailer--) | Получает или задает значение, указывающее, имеет ли GIF трейлер. |
|
|  | [setTrailer(boolean value)](#setTrailer-boolean-) | Получает или задает значение, указывающее, имеет ли GIF трейлер. |
|
|  | [getInterlaced()](#getInterlaced--) | Истина, если изображение должно быть чередованным. |
|
|  | [setInterlaced(boolean value)](#setInterlaced-boolean-) | Истина, если изображение должно быть чередованным. |
|
|  | [isPaletteSorted()](#isPaletteSorted--) | Получает или задает значение, указывающее, отсортированы ли элементы палитры. |
|
|  | [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Получает или задает значение, указывающее, отсортированы ли элементы палитры. |
|
|  | [getPixelAspectRatio()](#getPixelAspectRatio--) | Получает или задает соотношение сторон пикселя GIF. |
|
|  | [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Получает или задает соотношение сторон пикселя GIF. |
|
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


Создает GifSaveOptions со значениями по умолчанию.


### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Получает или задает индекс фонового цвета GIF.


**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Получает или задает индекс фонового цвета GIF.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Получает или задает разрешение цвета GIF.

<br />

*** ** * ** ***

Разрешение цвета - количество бит на основной цвет, доступных оригинальному изображению, минус 1. Это значение представляет размер всей палитры, из которой были выбраны цвета графики, а не количество фактически использованных в графике цветов. Например, если значение в этом поле равно 3, то палитра оригинального изображения имела 4 бита на основной цвет, доступных для создания изображения. Это значение следует установить, чтобы указать насыщенность оригинальной палитры, даже если не каждый цвет из полной палитры доступен на исходном устройстве.

<br />



**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Получает или задает разрешение цвета GIF.

<br />

*** ** * ** ***

Разрешение цвета - количество бит на основной цвет, доступных оригинальному изображению, минус 1. Это значение представляет размер всей палитры, из которой были выбраны цвета графики, а не количество фактически использованных в графике цветов. Например, если значение в этом поле равно 3, то палитра оригинального изображения имела 4 бита на основной цвет, доступных для создания изображения. Это значение следует установить, чтобы указать насыщенность оригинальной палитры, даже если не каждый цвет из полной палитры доступен на исходном устройстве.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Получает или задает значение, указывающее, применяется ли коррекция палитры.

<br />

*** ** * ** ***

Коррекция палитры означает, что при экспорте изображения в GIF цвета исходного изображения будут проанализированы для построения наиболее подходящей палитры (в случае, если палитра изображения не существует или не указана в параметрах). Процесс анализа занимает некоторое время, однако результирующее изображение будет иметь наиболее подходящую цветовую палитру, и результат будет визуально лучше.

<br />



**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Получает или задает значение, указывающее, применяется ли коррекция палитры.

<br />

*** ** * ** ***

Коррекция палитры означает, что при экспорте изображения в GIF цвета исходного изображения будут проанализированы для построения наиболее подходящей палитры (в случае, если палитра изображения не существует или не указана в параметрах). Процесс анализа занимает некоторое время, однако результирующее изображение будет иметь наиболее подходящую цветовую палитру, и результат будет визуально лучше.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Получает или задает значение, указывающее, имеет ли GIF трейлер.


**Returns:**
boolean
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Получает или задает значение, указывающее, имеет ли GIF трейлер.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Истина, если изображение должно быть чередованным.


**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Истина, если изображение должно быть чередованным.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Получает или задает значение, указывающее, отсортированы ли элементы палитры.


**Returns:**
boolean
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Получает или задает значение, указывающее, отсортированы ли элементы палитры.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Получает или задает соотношение сторон пикселя GIF.

<br />

*** ** * ** ***

Соотношение сторон пикселя - фактор, используемый для вычисления приближённого соотношения сторон пикселя в оригинальном изображении. Если значение поля не равно 0, это приближение соотношения сторон вычисляется по формуле: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Соотношение сторон пикселя определяется как отношение ширины пикселя к его высоте. Диапазон значений в этом поле позволяет задавать от самого широкого пикселя 4:1 до самого высокого пикселя 1:4 с шагом 1/64. Значения: 0 — информация о соотношении сторон не указана. 1..255 — значение, используемое в вычислениях.

<br />



**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Получает или задает соотношение сторон пикселя GIF.

<br />

*** ** * ** ***

Соотношение сторон пикселя - фактор, используемый для вычисления приближённого соотношения сторон пикселя в оригинальном изображении. Если значение поля не равно 0, это приближение соотношения сторон вычисляется по формуле: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Соотношение сторон пикселя определяется как отношение ширины пикселя к его высоте. Диапазон значений в этом поле позволяет задавать от самого широкого пикселя 4:1 до самого высокого пикселя 1:4 с шагом 1/64. Значения: 0 — информация о соотношении сторон не указана. 1..255 — значение, используемое в вычислениях.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte |  |

