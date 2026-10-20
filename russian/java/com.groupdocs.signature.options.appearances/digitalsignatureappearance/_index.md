---
title: "DigitalSignatureAppearance"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Описывает внешний вид строки подписи для цифровой подписи."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

Описывает внешний вид строки подписи для цифровой подписи.
Одна строка подписи может быть применена только к одной цифровой подписи.
Строка подписи всегда находится на первой странице.
Эта функция может быть полезна для форматов файлов .docx, .doc, .odt и .xlsx.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | Создаёт объект внешнего вида строки подписи. |
|
|  | [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | Создаёт внешний вид строки подписи с указанными значениями (подписант, заголовок, электронная почта). |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getSigner()](#getSigner--) | Получает или задает имя подписанта для строки подписи. |
|
|  | [setSigner(String value)](#setSigner-java.lang.String-) | Получает или задает имя подписанта для строки подписи. |
|
|  | [getTitle()](#getTitle--) | Получает или задает заголовок для строки подписи. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Получает или задает заголовок для строки подписи. |
|
|  | [getEmail()](#getEmail--) | Получает или задает электронную почту, которая будет отображаться в строке подписи. |
|
|  | [setEmail(String value)](#setEmail-java.lang.String-) | Получает или задает электронную почту, которая будет отображаться в строке подписи. |
|
|  | [toString()](#toString--) | Переопределить преобразование строки. |
|
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


Создаёт объект внешнего вида строки подписи.


### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


Создаёт внешний вид строки подписи с указанными значениями (подписант, заголовок, электронная почта).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | подписант | java.lang.String | Имя подписанта. |
|
|  | title | java.lang.String | Заголовок подписи. |
|
|  | электронная почта | java.lang.String | Электронная почта автора. |
|

### getSigner() {#getSigner--}
```
public final String getSigner()
```


Получает или задает имя подписанта для строки подписи.


**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


Получает или задает имя подписанта для строки подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Получает или задает заголовок для строки подписи.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Получает или задает заголовок для строки подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


Получает или задает электронную почту, которая будет отображаться в строке подписи.


**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


Получает или задает электронную почту, которая будет отображаться в строке подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Переопределить преобразование строки.


**Returns:**
java.lang.String -
