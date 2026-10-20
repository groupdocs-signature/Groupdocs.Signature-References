---
title: "DigitalVerifyOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Сохраняет параметры для проверки цифровой подписи документа."
type: docs
weight: 12
url: /ru/java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

Сохраняет параметры для проверки цифровой подписи документа.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](../https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/)
* Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Digital signatures in a document and additional settings](../)

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [DigitalVerifyOptions()](#DigitalVerifyOptions--) | Создаёт Digital Verification Option со значениями по умолчанию. |
|
|  | [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | Создаёт Digital Verification Option с указанным GUID цифрового сертификата. |
|
|  | [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | Создаёт Digital Verification Option с указанным потоком сертификата. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Получить сертификат X509Certificate2 из GUID сертификата или потока. |
|
|  | [getPassword()](#getPassword--) | Пароль цифрового сертификата, если требуется. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Пароль цифрового сертификата, если требуется. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | GUID файла цифрового сертификата. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | GUID файла цифрового сертификата. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Поток цифрового сертификата. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Поток цифрового сертификата. |
|
|  | [getComments()](#getComments--) | Комментарии цифровой подписи для проверки. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Комментарии цифровой подписи для проверки. |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Диапазон даты и времени цифровой подписи для проверки. |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Диапазон даты и времени цифровой подписи для проверки. |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | Диапазон даты и времени цифровой подписи для проверки. |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Диапазон даты и времени цифровой подписи для проверки. |
|
|  | [getReason()](#getReason--) | Причина цифровой подписи для проверки. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Причина цифровой подписи для проверки. |
|
|  | [getContact()](#getContact--) | Контакт подписи для проверки. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | Контакт подписи для проверки. |
|
|  | [getLocation()](#getLocation--) | Местоположение подписи для проверки. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Местоположение подписи для проверки. |
|
|  | [getSubjectName()](#getSubjectName--) | Отличительное имя субъекта сертификата для проверки. |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Отличительное имя субъекта сертификата для проверки. |
|
|  | [getIssuerName()](#getIssuerName--) | Имя издателя сертификата для проверки. |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Имя издателя сертификата для проверки. |
|
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


Создаёт Digital Verification Option со значениями по умолчанию.


### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


Создаёт Digital Verification Option с указанным GUID цифрового сертификата.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | certificateGuid | java.lang.String | Путь к файлу цифрового сертификата. |
|

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


Создаёт Digital Verification Option с указанным потоком сертификата.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Поток сертификата. |
|

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


Получить сертификат X509Certificate2 из GUID сертификата или потока.


**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Пароль цифрового сертификата, если требуется.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Пароль цифрового сертификата, если требуется.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


GUID файла цифрового сертификата.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


GUID файла цифрового сертификата.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Поток цифрового сертификата.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Поток цифрового сертификата.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Комментарии цифровой подписи для проверки.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Комментарии цифровой подписи для проверки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


Диапазон даты и времени цифровой подписи для проверки. Значение null будет игнорироваться.


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


Диапазон даты и времени цифровой подписи для проверки. Значение null будет игнорироваться.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


Диапазон даты и времени цифровой подписи для проверки. Значение null будет игнорироваться.


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


Диапазон даты и времени цифровой подписи для проверки. Значение null будет игнорироваться.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Причина цифровой подписи для проверки.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Причина цифровой подписи для проверки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Контакт подписи для проверки.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Контакт подписи для проверки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Местоположение подписи для проверки.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Местоположение подписи для проверки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Уникальное имя субъекта сертификата для проверки. Значение чувствительно к регистру.
Если это свойство установлено, проверка будет проверять, содержит ли имя субъекта подписи или равно переданному значению


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Уникальное имя субъекта сертификата для проверки. Значение чувствительно к регистру.
Если это свойство установлено, проверка будет проверять, содержит ли имя субъекта подписи или равно переданному значению


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Имя издателя сертификата для проверки. Значение чувствительно к регистру.
Если это свойство установлено, проверка будет проверять, содержит ли имя издателя подписи или равно переданному значению


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Имя издателя сертификата для проверки. Значение чувствительно к регистру.
Если это свойство установлено, проверка будет проверять, содержит ли имя издателя подписи или равно переданному значению


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

