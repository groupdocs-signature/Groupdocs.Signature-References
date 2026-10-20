---
title: "PdfTextAnnotationAppearance"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Описывает внешний вид объекта текстовой аннотации PDF: Title, Subject, Content."
type: docs
weight: 13
url: /ru/java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

Описывает внешний вид объекта текстовой аннотации PDF (Заголовок, Тема, Содержание).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | Создает объект внешнего вида текстовой аннотации подписи PDF. |
|
|  | [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | Создает текстовую аннотацию подписи PDF с указанными значениями (title, subject, contents). |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getContents()](#getContents--) | Получает или задает содержимое объекта аннотации. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | Получает или задает содержимое объекта аннотации. |
|
|  | [getSubject()](#getSubject--) | Получает или задает Subject, представляющий описание объекта. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Получает или задает Subject, представляющий описание объекта. |
|
|  | [getTitle()](#getTitle--) | Получает или задает Title, который будет отображаться в заголовке окна объекта аннотации. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Получает или задает Title, который будет отображаться в заголовке окна объекта аннотации. |
|
|  | [getBorder()](#getBorder--) | Получает или задает различные настройки границы |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Получает или задает различные настройки границы |
|
|  | [getBorderEffect()](#getBorderEffect--) | Получает или задает эффект границы. |
|
|  | [setBorderEffect(int value)](#setBorderEffect-int-) | Получает или задает эффект границы. |
|
|  | [getBorderEffectIntensity()](#getBorderEffectIntensity--) | Получает или задает интенсивность эффекта границы. |
|
|  | [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | Получает или задает интенсивность эффекта границы. |
|
|  | [getHCornerRadius()](#getHCornerRadius--) | Получает или задает горизонтальный радиус скругления. |
|
|  | [setHCornerRadius(int value)](#setHCornerRadius-int-) | Получает или задает горизонтальный радиус скругления. |
|
|  | [getVCornerRadius()](#getVCornerRadius--) | Получает или задает вертикальный радиус скругления. |
|
|  | [setVCornerRadius(int value)](#setVCornerRadius-int-) | Получает или задает вертикальный радиус скругления. |
|
|  | [toString()](#toString--) | Переопределить преобразование строки. |
|
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


Создает объект внешнего вида текстовой аннотации подписи PDF.


### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


Создает текстовую аннотацию подписи PDF с указанными значениями (title, subject, contents).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | title | java.lang.String | Title. |
|
|  | subject | java.lang.String | Subject. |
|
|  | contents | java.lang.String | Содержание. |
|

### getContents() {#getContents--}
```
public final String getContents()
```


Получает или задает содержимое объекта аннотации.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Получает или задает содержимое объекта аннотации.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Получает или задает Subject, представляющий описание объекта.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Получает или задает Subject, представляющий описание объекта.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Получает или задает Title, который будет отображаться в заголовке окна объекта аннотации.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Получает или задает Title, который будет отображаться в заголовке окна объекта аннотации.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Получает или задает различные настройки границы


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Получает или задает различные настройки границы


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


Получает или задает эффект границы.


**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


Получает или задает эффект границы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


Получает или задает интенсивность эффекта границы. Допустимый диапазон значения — [0..2].


**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


Получает или задает интенсивность эффекта границы. Допустимый диапазон значения — [0..2].


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


Получает или задает горизонтальный радиус скругления.


**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


Получает или задает горизонтальный радиус скругления.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


Получает или задает вертикальный радиус скругления.


**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


Получает или задает вертикальный радиус скругления.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### toString() {#toString--}
```
public String toString()
```


Переопределить преобразование строки.


**Returns:**
java.lang.String -
