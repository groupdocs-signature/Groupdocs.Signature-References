---
title: "DigitalSignature"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Содержит свойства цифровой подписи."
type: docs
weight: 12
url: /ru/java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

Содержит свойства цифровой подписи.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [DigitalSignature()](#DigitalSignature--) | Инициализировать цифровую подпись с параметрами по умолчанию. |
|
|  | [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | Инициализировать цифровую подпись с известным SignatureId. |
|
|  | [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | Создать цифровую подпись с указанным сертификатом. |
|
|  | [DigitalSignature(X509Certificate cert, PrivateKey key)](#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Создать цифровую подпись на основе сертификата X509Certificate и PrivateKey. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Получает или задает сертификат KeyStore. |
|
|  | [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | Получает или задает сертификат KeyStore. |
|
|  | [getX509Certificate()](#getX509Certificate--) | Получает или задает сертификат X509. |
|
|  | [setX509Certificate(X509Certificate value)](#setX509Certificate-java.security.cert.X509Certificate-) | Получает или задает сертификат X509. |
|
|  | [getPrivateKey()](#getPrivateKey--) | Получает или задает PrivateKey сертификата. |
|
|  | [setPrivateKey(PrivateKey value)](#setPrivateKey-java.security.PrivateKey-) | Получает или задает PrivateKey сертификата. |
|
|  | [getCertificateName()](#getCertificateName--) | Получает или задает имя сертификата X509. |
|
|  | [setCertificateName(String value)](#setCertificateName-java.lang.String-) | Получает или задает имя сертификата X509. |
|
|  | [getComments()](#getComments--) | Получает или задает комментарий цели подписи. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Получает или задает комментарий цели подписи. |
|
|  | [isValid()](#isValid--) | Возвращает true, если эта цифровая подпись действительна и документ не был изменён. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Возвращает true, если эта цифровая подпись действительна и документ не был изменён. |
|
|  | [getSignTime()](#getSignTime--) | Получает или задает время подписи документа. |
|
|  | [setSignTime(Date value)](#setSignTime-java.util.Date-) | Получает или задает время подписи документа. |
|
|  | [getXAdESType()](#getXAdESType--) | Тип XAdES |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | Тип XAdES |
XAdESType
.
|
|  | [getThumbprint()](#getThumbprint--) | Получает отпечаток сертификата. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Переопределяет метод Equals для сравнения свойств подписи |
|
|  | [hashCode()](#hashCode--) | Переопределяет метод GetHashCode |
|
|  | [deepClone()](#deepClone--) | Создать копию экземпляра подписи штрих‑кода. |
|
|  | [loadDigitalSignatures()](#loadDigitalSignatures--) | Загрузить цифровую подпись из всех системных хранилищ сертификатов X509. |
|
|  | [loadDigitalSignatures(StoreName storeName)](#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-) | Загрузить цифровую подпись из переданного хранилища сертификатов X509. |
|
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


Инициализировать цифровую подпись с параметрами по умолчанию.


### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


Инициализировать цифровую подпись с известным SignatureId.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| signatureId | java.lang.String |  |

### DigitalSignature(KeyStore certificate) {#DigitalSignature-java.security.KeyStore-}
```
public DigitalSignature(KeyStore certificate)
```


Создать цифровую подпись с указанным сертификатом.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | сертификат | java.security.KeyStore | Сертификат X509. |
|

### DigitalSignature(X509Certificate cert, PrivateKey key) {#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
```
public DigitalSignature(X509Certificate cert, PrivateKey key)
```


Создать цифровую подпись на основе сертификата X509Certificate и PrivateKey.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | cert | java.security.cert.X509Certificate | Сертификат X509Certificate. |
|
|  | key | java.security.PrivateKey | PrivateKey сертификата. |
|

### getCertificate() {#getCertificate--}
```
public final KeyStore getCertificate()
```


Получает или задает сертификат KeyStore.


**Returns:**
java.security.KeyStore
### setCertificate(KeyStore value) {#setCertificate-java.security.KeyStore-}
```
public final void setCertificate(KeyStore value)
```


Получает или задает сертификат KeyStore.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.security.KeyStore |  |

### getX509Certificate() {#getX509Certificate--}
```
public final X509Certificate getX509Certificate()
```


Получает или задает сертификат X509.


**Returns:**
java.security.cert.X509Certificate
### setX509Certificate(X509Certificate value) {#setX509Certificate-java.security.cert.X509Certificate-}
```
public final void setX509Certificate(X509Certificate value)
```


Получает или задает сертификат X509.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.security.cert.X509Certificate |  |

### getPrivateKey() {#getPrivateKey--}
```
public final PrivateKey getPrivateKey()
```


Получает или задает PrivateKey сертификата.


**Returns:**
java.security.PrivateKey
### setPrivateKey(PrivateKey value) {#setPrivateKey-java.security.PrivateKey-}
```
public final void setPrivateKey(PrivateKey value)
```


Получает или задает PrivateKey сертификата.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.security.PrivateKey |  |

### getCertificateName() {#getCertificateName--}
```
public final String getCertificateName()
```


Получает или задает имя сертификата X509.


**Returns:**
java.lang.String
### setCertificateName(String value) {#setCertificateName-java.lang.String-}
```
public final void setCertificateName(String value)
```


Получает или задает имя сертификата X509.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Получает или задает комментарий цели подписи.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Получает или задает комментарий цели подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


Возвращает true, если эта цифровая подпись действительна и документ не был изменён.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Возвращает true, если эта цифровая подпись действительна и документ не был изменён.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


Получает или задает время подписи документа.


**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


Получает или задает время подписи документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


Тип XAdES
XAdESType
. Значение по умолчанию — None (XAdES отключён).
В данный момент тип подписи XAdES поддерживается только для документов Spreadsheet.


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


Тип XAdES
XAdESType
. Значение по умолчанию — None (XAdES отключён).
В данный момент тип подписи XAdES поддерживается только для документов Spreadsheet.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Получает отпечаток сертификата.


**Returns:**
java.lang.String
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

### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


Загрузить цифровую подпись из всех системных хранилищ сертификатов X509.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Возвращает список [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) цифровых подписей.

### loadDigitalSignatures(StoreName storeName) {#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-}
```
public static List<DigitalSignature> loadDigitalSignatures(StoreName storeName)
```


Загрузить цифровую подпись из переданного хранилища сертификатов X509.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| storeName | [StoreName](../../com.groupdocs.signature.domain.signatures/storename) |  |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Возвращает список [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) цифровых подписей.

