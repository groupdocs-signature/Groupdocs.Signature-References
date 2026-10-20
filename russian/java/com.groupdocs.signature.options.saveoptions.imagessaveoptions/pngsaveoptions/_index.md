---
title: "PngSaveOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Параметры сохранения PNG для документов‑изображений."
type: docs
weight: 22
url: /ru/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class PngSaveOptions extends ImageSaveOptions
```

Параметры сохранения PNG для документов‑изображений.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PngSaveOptions()](#PngSaveOptions--) | Создаёт PngSaveOptions со значениями по умолчанию. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getBitDepth()](#getBitDepth--) | Битовая глубина. |
|
|  | [setBitDepth(byte value)](#setBitDepth-byte-) | Битовая глубина. |
|
|  | [getColorType()](#getColorType--) | Получает или задает тип |
PngColorType
.
|
|  | [setColorType(int value)](#setColorType-int-) | Получает или задает тип |
PngColorType
.
|
|  | [getCompressionLevel()](#getCompressionLevel--) | Уровень сжатия PNG‑изображения в диапазоне от 0 до 9, где 9 — максимальное сжатие |
а 0 — режим хранения.
|
|  | [setCompressionLevel(int value)](#setCompressionLevel-int-) | Уровень сжатия PNG‑изображения в диапазоне от 0 до 9, где 9 — максимальное сжатие |
а 0 — режим хранения.
|
|  | [getFilterType()](#getFilterType--) | Получает или задает тип фильтра |
PngFilterType
используется при процессе сохранения PNG‑файла.
|
|  | [setFilterType(int value)](#setFilterType-int-) | Получает или задает тип фильтра |
PngFilterType
используется при процессе сохранения PNG‑файла.
|
|  | [getProgressive()](#getProgressive--) | Получает или задает значение, указывающее, является ли этот PngSaveOptions прогрессивным. |
|
|  | [setProgressive(boolean value)](#setProgressive-boolean-) | Получает или задает значение, указывающее, является ли этот PngSaveOptions прогрессивным. |
|
### PngSaveOptions() {#PngSaveOptions--}
```
public PngSaveOptions()
```


Создаёт PngSaveOptions со значениями по умолчанию.


### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


Битовая глубина.


**Returns:**
byte
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


Битовая глубина.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Получает или задает тип
PngColorType
.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Получает или задает тип
PngColorType
.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


Уровень сжатия PNG‑изображения в диапазоне от 0 до 9, где 9 — максимальное сжатие
а 0 — режим хранения.


**Returns:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


Уровень сжатия PNG‑изображения в диапазоне от 0 до 9, где 9 — максимальное сжатие
а 0 — режим хранения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Получает или задает тип фильтра
PngFilterType
используется при процессе сохранения PNG‑файла.


**Returns:**
int
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Получает или задает тип фильтра
PngFilterType
используется при процессе сохранения PNG‑файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


Получает или задает значение, указывающее, является ли этот PngSaveOptions прогрессивным.


**Returns:**
boolean
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


Получает или задает значение, указывающее, является ли этот PngSaveOptions прогрессивным.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

