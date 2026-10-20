---
title: "TextVerifyOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Сохраняет параметры для проверки текстовой подписи документа."
type: docs
weight: 14
url: /ru/java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

Сохраняет параметры для проверки текстовой подписи документа.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/)
* Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-text-signatures/)

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [TextVerifyOptions()](#TextVerifyOptions--) | Инициализирует новый экземпляр TextVerifyOptions со значениями по умолчанию. |
|
|  | [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | Инициализирует новый экземпляр TextVerifyOptions с текстом проверки. |
|
|  | [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | Инициализирует новый экземпляр TextVerifyOptions со свойством Text для проверки и реализацией подписи. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getText()](#getText--) | Укажите текст подписи, если его следует проверить. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Укажите текст подписи, если его следует проверить. |
|
|  | [getMatchType()](#getMatchType--) | Получает или задает проверку типа совпадения текста. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Получает или задает проверку типа совпадения текста. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Тип подписи для проверки. |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Тип подписи для проверки. |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Получает или задает заголовок поля формы для его проверки. |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Получает или задает заголовок поля формы для его проверки. |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | Получает или задает тип поля формы для его проверки. |
|
|  | [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | Получает или задает тип поля формы для его проверки. |
|
|  | [getSignatureID()](#getSignatureID--) | Укажите идентификатор текстовой подписи больше нуля, если её следует проверить. |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | Укажите идентификатор текстовой подписи больше нуля, если её следует проверить. |
|
|  | [toString()](#toString--) | Переопределяет преобразование в строку. |
|
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


Инициализирует новый экземпляр TextVerifyOptions со значениями по умолчанию.


### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


Инициализирует новый экземпляр TextVerifyOptions с текстом проверки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | текст | java.lang.String | Текст для проверки |
|

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


Инициализирует новый экземпляр TextVerifyOptions со свойством Text для проверки и реализацией подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | текст | java.lang.String | Текст для проверки. |
|
|  | реализация | int | Тип реализации подписи. |
|

### getText() {#getText--}
```
public final String getText()
```


Укажите текст подписи, если его следует проверить.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Укажите текст подписи, если его следует проверить.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Получает или задает проверку типа совпадения текста.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Получает или задает проверку типа совпадения текста.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Тип подписи для проверки.


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Тип подписи для проверки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Получает или задает заголовок поля формы для его проверки.
Если установить это свойство, текст будет найден только в текстовых полях формы.


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Получает или задает заголовок поля формы для его проверки.
Если установить это свойство, текст будет найден только в текстовых полях формы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


Получает или задает тип поля формы для его проверки.
Если установить это свойство, текст будет найден только в текстовых полях формы.


**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


Получает или задает тип поля формы для его проверки.
Если установить это свойство, текст будет найден только в текстовых полях формы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Укажите идентификатор текстовой подписи больше нуля, если её следует проверить. Это свойство поддерживается только для PDF‑документов.


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Укажите идентификатор текстовой подписи больше нуля, если её следует проверить. Это свойство поддерживается только для PDF‑документов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### toString() {#toString--}
```
public String toString()
```


Переопределяет преобразование в строку.


**Returns:**
java.lang.String -
