---
title: "PdfTextStickerAppearance"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Описывает внешний вид объекта стикера текстовой аннотации PDF и всплывающего окна стикера."
type: docs
weight: 14
url: /ru/java/com.groupdocs.signature.options.appearances/pdftextstickerappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfTextStickerAppearance extends SignatureAppearance
```

Описывает внешний вид объекта стикера текстовой аннотации PDF и всплывающего окна стикера.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PdfTextStickerAppearance()](#PdfTextStickerAppearance--) | Создаёт объект внешнего вида текстовой аннотации подписи PDF. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getTitle()](#getTitle--) | Получает или задает заголовок всплывающего окна. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Получает или задает заголовок всплывающего окна. |
|
|  | [getSubject()](#getSubject--) | Получает или задает тему. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Получает или задает тему. |
|
|  | [getContents()](#getContents--) | Получает или задает содержимое всплывающего окна. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | Получает или задает содержимое всплывающего окна. |
|
|  | [getOpened()](#getOpened--) | Настройте, будет ли всплывающее окно стикера открываться по умолчанию. |
|
|  | [setOpened(boolean value)](#setOpened-boolean-) | Настройте, будет ли всплывающее окно стикера открываться по умолчанию. |
|
|  | [getIcon()](#getIcon--) | Получает или задает значок стикера. |
|
|  | [setIcon(int value)](#setIcon-int-) | Получает или задает значок стикера. |
|
|  | [getDefaultAppearance()](#getDefaultAppearance--) | Получает внешний вид по умолчанию для стикера. |
|
|  | [resetDefaultAppearance()](#resetDefaultAppearance--) | Очищает значения внешнего вида по умолчанию для стикера. |
|
|  | [toString()](#toString--) | Переопределить преобразование строки. |
|
### PdfTextStickerAppearance() {#PdfTextStickerAppearance--}
```
public PdfTextStickerAppearance()
```


Создаёт объект внешнего вида текстовой аннотации подписи PDF.


### getTitle() {#getTitle--}
```
public final String getTitle()
```


Получает или задает заголовок всплывающего окна.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Получает или задает заголовок всплывающего окна.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Получает или задает тему.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Получает или задает тему.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getContents() {#getContents--}
```
public final String getContents()
```


Получает или задает содержимое всплывающего окна.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Получает или задает содержимое всплывающего окна.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getOpened() {#getOpened--}
```
public final boolean getOpened()
```


Настройте, будет ли всплывающее окно стикера открываться по умолчанию.


**Returns:**
boolean
### setOpened(boolean value) {#setOpened-boolean-}
```
public final void setOpened(boolean value)
```


Настройте, будет ли всплывающее окно стикера открываться по умолчанию.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getIcon() {#getIcon--}
```
public final int getIcon()
```


Получает или задает значок стикера.


**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public final void setIcon(int value)
```


Получает или задает значок стикера.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public static PdfTextStickerAppearance getDefaultAppearance()
```


Получает внешний вид по умолчанию для стикера. Эти свойства применяются по умолчанию, если
Свойство Options.SignatureAppearance не указано.
Эти свойства могут быть изменены пользователем в любой момент.


**Returns:**
[PdfTextStickerAppearance](../../com.groupdocs.signature.options.appearances/pdftextstickerappearance)
### resetDefaultAppearance() {#resetDefaultAppearance--}
```
public static void resetDefaultAppearance()
```


Очищает значения внешнего вида по умолчанию для стикера.


### toString() {#toString--}
```
public String toString()
```


Переопределить преобразование строки.


**Returns:**
java.lang.String -
