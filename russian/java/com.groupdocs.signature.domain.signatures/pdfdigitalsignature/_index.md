---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Содержит свойства цифровой подписи PDF."
type: docs
weight: 15
url: /ru/java/com.groupdocs.signature.domain.signatures/pdfdigitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
```
public class PdfDigitalSignature extends DigitalSignature
```

Содержит свойства цифровой подписи PDF.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PdfDigitalSignature()](#PdfDigitalSignature--) | Инициализировать Pdf Digital Signature без сертификата. |
|
|  | [PdfDigitalSignature(KeyStore certificate)](#PdfDigitalSignature-java.security.KeyStore-) | Создать Pdf Digital signature с указанным сертификатом. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getContactInfo()](#getContactInfo--) | Информация, предоставленная подписантом, позволяющая получателю связаться с подписантом |
для проверки подписи, например.
|
|  | [setContactInfo(String value)](#setContactInfo-java.lang.String-) | Информация, предоставленная подписантом, позволяющая получателю связаться с подписантом |
для проверки подписи, например.
|
|  | [getLocation()](#getLocation--) | Имя хоста CPU или физическое местоположение подписи. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Имя хоста CPU или физическое местоположение подписи. |
|
|  | [getReason()](#getReason--) | Причина подписи, например (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Причина подписи, например (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
|
|  | [getType()](#getType--) | Тип цифровой подписи PDF. |
|
|  | [setType(int value)](#setType-int-) | Тип цифровой подписи PDF. |
|
|  | [getTimeStamp()](#getTimeStamp--) | Отметка времени для цифровой подписи PDF. |
|
|  | [setTimeStamp(TimeStamp value)](#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) | Отметка времени для цифровой подписи PDF. |
|
|  | [getShowProperties()](#getShowProperties--) | Принудительно показывать/скрывать свойства подписи. |
|
|  | [setShowProperties(boolean value)](#setShowProperties-boolean-) | Принудительно показывать/скрывать свойства подписи. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Переопределяет метод Equals для сравнения свойств подписи |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
|  | [deepClone()](#deepClone--) | Создать копию экземпляра подписи штрих‑кода. |
|
### PdfDigitalSignature() {#PdfDigitalSignature--}
```
public PdfDigitalSignature()
```


Инициализировать Pdf Digital Signature без сертификата.


### PdfDigitalSignature(KeyStore certificate) {#PdfDigitalSignature-java.security.KeyStore-}
```
public PdfDigitalSignature(KeyStore certificate)
```


Создать Pdf Digital signature с указанным сертификатом.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | сертификат | java.security.KeyStore | Сертификат X509. |
|

### getContactInfo() {#getContactInfo--}
```
public final String getContactInfo()
```


Информация, предоставленная подписантом, позволяющая получателю связаться с подписантом
для проверки подписи, например, номер телефона.


**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public final void setContactInfo(String value)
```


Информация, предоставленная подписантом, позволяющая получателю связаться с подписантом
для проверки подписи, например, номер телефона.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Имя хоста CPU или физическое местоположение подписи.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Имя хоста CPU или физическое местоположение подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Причина подписи, например (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Причина подписи, например (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Тип цифровой подписи PDF.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Тип цифровой подписи PDF.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getTimeStamp() {#getTimeStamp--}
```
public final TimeStamp getTimeStamp()
```


Отметка времени для цифровой подписи PDF.
Значение по умолчанию — null.


**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### setTimeStamp(TimeStamp value) {#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public final void setTimeStamp(TimeStamp value)
```


Отметка времени для цифровой подписи PDF.
Значение по умолчанию — null.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### getShowProperties() {#getShowProperties--}
```
public final boolean getShowProperties()
```


Принудительно показывать/скрывать свойства подписи. Если ShowProperties истинно, подпись
поле имеет предопределённый формат отображения
Электронно подписано {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} Date: {Date} Reason: {
Причина
(#getReason.getReason/#setReason(String).setReason(String))}
Местоположение: {
Местоположение
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties по умолчанию истинно.


**Returns:**
boolean
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public final void setShowProperties(boolean value)
```


Принудительно показывать/скрывать свойства подписи. Если ShowProperties истинно, подпись
поле имеет предопределённый формат отображения
Электронно подписано {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} Date: {Date} Reason: {
Причина
(#getReason.getReason/#setReason(String).setReason(String))}
Местоположение: {
Местоположение
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties по умолчанию истинно.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Переопределяет метод Equals для сравнения свойств подписи


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | подпись | java.lang.Object | Объект подписи для сравнения. |
|

**Returns:**
boolean — Возвращает true, если переданный объект подписи имеет тот же тип и все его свойства равны свойствам этого экземпляра.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Переопределяет метод GetHashCode


**Returns:**
int — Хеш‑код подписи

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создать копию экземпляра подписи штрих‑кода.


**Returns:**
java.lang.Object - Возвращает клонированный экземпляр подписи штрих‑кода.

