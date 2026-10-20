---
title: "JpegSaveOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Параметры сохранения JPEG для документов‑изображений."
type: docs
weight: 19
url: /ru/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

Параметры сохранения JPEG для документов‑изображений.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [JpegSaveOptions()](#JpegSaveOptions--) | Создает JpegSaveOptions со значениями по умолчанию. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getBitsPerChannel()](#getBitsPerChannel--) | Получает или задает количество бит на канал для без потерь JPEG‑изображения. |
|
|  | [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Получает или задает количество бит на канал для без потерь JPEG‑изображения. |
|
|  | [getColorType()](#getColorType--) | Получает или задает тип цвета для JPEG‑изображения. |
|
|  | [setColorType(int value)](#setColorType-int-) | Получает или задает тип цвета для JPEG‑изображения. |
|
|  | [getComment()](#getComment--) | Получает или задает комментарий к JPEG‑файлу. |
|
|  | [setComment(String value)](#setComment-java.lang.String-) | Получает или задает комментарий к JPEG‑файлу. |
|
|  | [getCompressionType()](#getCompressionType--) | Получает или задает тип сжатия. |
|
|  | [setCompressionType(int value)](#setCompressionType-int-) | Получает или задает тип сжатия. |
|
|  | [getQuality()](#getQuality--) | Получает или задает качество изображения. |
|
|  | [setQuality(int value)](#setQuality-int-) | Получает или задает качество изображения. |
|
|  | [getSampleRoundingMode()](#getSampleRoundingMode--) | Получает или задает режим округления образца для приведения 8‑битного значения к n‑битному. |
JpegOptions.BitsPerChannel.
|
|  | [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Получает или задает режим округления образца для приведения 8‑битного значения к n‑битному. |
JpegOptions.BitsPerChannel.
|
|  | [getFileFormat()](#getFileFormat--) | Получает или задает формат файла подписанного документа. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Получает или задает формат файла подписанного документа. |
|
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


Создает JpegSaveOptions со значениями по умолчанию.


### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Получает или задает количество бит на канал для без потерь JPEG‑изображения.
Теперь поддерживается от 2 до 8 бит на канал.


**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Получает или задает количество бит на канал для без потерь JPEG‑изображения.
Теперь поддерживается от 2 до 8 бит на канал.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Получает или задает тип цвета для JPEG‑изображения.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Получает или задает тип цвета для JPEG‑изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


Получает или задает комментарий к JPEG‑файлу.


**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Получает или задает комментарий к JPEG‑файлу.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Получает или задает тип сжатия.


**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Получает или задает тип сжатия.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getQuality() {#getQuality--}
```
public int getQuality()
```


Получает или задает качество изображения.


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Получает или задает качество изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Получает или задает режим округления образца для приведения 8‑битного значения к n‑битному.
JpegOptions.BitsPerChannel.


**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Получает или задает режим округления образца для приведения 8‑битного значения к n‑битному.
JpegOptions.BitsPerChannel.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Получает или задает формат файла подписанного документа. Скрыто, потому что не используется в этом классе параметров.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Получает или задает формат файла подписанного документа. Скрыто, потому что не используется в этом классе параметров.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

