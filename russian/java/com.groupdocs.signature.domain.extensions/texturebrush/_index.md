---
title: "TextureBrush"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет кисть текстуры."
type: docs
weight: 14
url: /ru/java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

Представляет кисть текстуры.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [TextureBrush()](#TextureBrush--) | Инициализирует новый экземпляр класса TextureBrush со значениями по умолчанию. |
|
|  | [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | Инициализирует новый экземпляр класса TextureBrush с файлом изображения. |
|
|  | [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | Инициализирует новый экземпляр класса TextureBrush с опцией потока изображения. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | Получает или задает путь к файлу текстурного изображения. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Получает или задает путь к файлу текстурного изображения. |
|
|  | [getImageStream()](#getImageStream--) | Получает или задает поток изображения текстуры. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Получает или задает поток изображения текстуры. |
|
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


Инициализирует новый экземпляр класса TextureBrush со значениями по умолчанию.


### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


Инициализирует новый экземпляр класса TextureBrush с файлом изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | Путь к файлу изображения. |
|

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


Инициализирует новый экземпляр класса TextureBrush с опцией потока изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | Поток изображения. |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Получает или задает путь к файлу текстурного изображения.
Это свойство используется только если ImageStream не указан.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Получает или задает путь к файлу текстурного изображения.
Это свойство используется только если ImageStream не указан.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Получает или задает поток изображения текстуры.
Если это свойство указано, оно всегда используется вместо ImageFilePath.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Получает или задает поток изображения текстуры.
Если это свойство указано, оно всегда используется вместо ImageFilePath.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.io.InputStream |  |

