---
title: "DigitalVBA"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет цифровую подпись для проектов VBA в электронных таблицах."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

Представляет цифровую подпись для проектов VBA в электронных таблицах.
Это предоставляет возможность подписывать проект VBA в конкретных форматах документов электронных таблиц, таких как Xlsm или Xltm.
Если несколько расширений DigitalVBA добавлены в DigitalSignOptions.Extensions, только первое участвует в подписании документа.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса DigitalVBA с файлом сертификата. |
|
|  | [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | Инициализирует новый экземпляр класса DigitalVBA с потоком сертификата. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getComments()](#getComments--) | Получает или задает комментарии подписи. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Получает или задает комментарии подписи. |
|
|  | [getPassword()](#getPassword--) | Получает или задает пароль цифрового сертификата. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Получает или задает пароль цифрового сертификата. |
|
|  | [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | Получает или задает настройку только подписи проекта VBA. |
|
|  | [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | Получает или задает настройку только подписи проекта VBA. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Получает путь к файлу цифрового сертификата. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Получает поток цифрового сертификата. |
|
|  | [release()](#release--) | Переопределяет метод для очистки ресурсов после подписания. |
|
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


Инициализирует новый экземпляр класса DigitalVBA с файлом сертификата.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Путь к файлу цифрового сертификата |
|
|  | пароль | java.lang.String | Пароль цифрового сертификата |
|

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


Инициализирует новый экземпляр класса DigitalVBA с потоком сертификата.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Поток цифрового сертификата |
|
|  | пароль | java.lang.String | Пароль цифрового сертификата |
|

### getComments() {#getComments--}
```
public final String getComments()
```


Получает или задает комментарии подписи.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Получает или задает комментарии подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Получает или задает пароль цифрового сертификата.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Получает или задает пароль цифрового сертификата.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


Получает или задает настройку только подписи проекта VBA.
Если установить значение true, документ SpreadSheet не будет подписан, но проект VBA будет подписан.


**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


Получает или задает настройку только подписи проекта VBA.
Если установить значение true, документ SpreadSheet не будет подписан, но проект VBA будет подписан.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Получает путь к файлу цифрового сертификата.
Это свойство используется только если CertificateStream не указан.


**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Получает поток цифрового сертификата.
Если это свойство указано, оно всегда используется вместо CertificateFilePath.


**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


Переопределяет метод для очистки ресурсов после подписания.


