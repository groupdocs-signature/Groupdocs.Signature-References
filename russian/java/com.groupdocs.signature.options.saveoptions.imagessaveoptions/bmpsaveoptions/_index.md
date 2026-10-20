---
title: "BmpSaveOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Параметры сохранения BMP для документов‑изображений."
type: docs
weight: 11
url: /ru/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bmpsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class BmpSaveOptions extends ImageSaveOptions
```

Параметры сохранения BMP для документов‑изображений.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [BmpSaveOptions()](#BmpSaveOptions--) | Создаёт BmpSaveOptions со значениями по умолчанию. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getBitsPerPixel()](#getBitsPerPixel--) | Получает или задает количество бит на пиксель изображения. |
|
|  | [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Получает или задает количество бит на пиксель изображения. |
|
|  | [getCompression()](#getCompression--) | Получает или задает сжатие. |
|
|  | [setCompression(int value)](#setCompression-int-) | Получает или задает сжатие. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Получает или задает горизонтальное разрешение. |
|
|  | [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Получает или задает горизонтальное разрешение. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Получает или задает вертикальное разрешение. |
|
|  | [setVerticalResolution(double value)](#setVerticalResolution-double-) | Получает или задает вертикальное разрешение. |
|
### BmpSaveOptions() {#BmpSaveOptions--}
```
public BmpSaveOptions()
```


Создаёт BmpSaveOptions со значениями по умолчанию.


### getBitsPerPixel() {#getBitsPerPixel--}
```
public final int getBitsPerPixel()
```


Получает или задает количество бит на пиксель изображения.


**Returns:**
int
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public final void setBitsPerPixel(int value)
```


Получает или задает количество бит на пиксель изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getCompression() {#getCompression--}
```
public final int getCompression()
```


Получает или задает сжатие. См. [BitmapCompression](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression).


**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public final void setCompression(int value)
```


Получает или задает сжатие. См. [BitmapCompression](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final double getHorizontalResolution()
```


Получает или задает горизонтальное разрешение. Обратите внимание, что из‑за округления полученное
разрешение может слегка отличаться от переданного.


**Returns:**
double
### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public final void setHorizontalResolution(double value)
```


Получает или задает горизонтальное разрешение. Обратите внимание, что из‑за округления полученное
разрешение может слегка отличаться от переданного.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final double getVerticalResolution()
```


Получает или задает вертикальное разрешение. Обратите внимание, что из‑за округления полученное
разрешение может слегка отличаться от переданного.


**Returns:**
double
### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public final void setVerticalResolution(double value)
```


Получает или задает вертикальное разрешение. Обратите внимание, что из‑за округления полученное
разрешение может слегка отличаться от переданного.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

