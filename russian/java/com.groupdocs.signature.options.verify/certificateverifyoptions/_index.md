---
title: "CertificateVerifyOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Сохраняет параметры для проверки сертификатных документов."
type: docs
weight: 11
url: /ru/java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

Сохраняет параметры для проверки сертификатных документов.

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [CertificateVerifyOptions()](#CertificateVerifyOptions--) | Инициализирует новый экземпляр TextVerifyOptions со значениями по умолчанию. |
|
|  | [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | Инициализирует новый экземпляр CertificateVerifyOptions с объектом для проверки. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getIssuer()](#getIssuer--) | Укажите издателя сертификата, если его следует проверить. |
|
|  | [setIssuer(String value)](#setIssuer-java.lang.String-) | Укажите издателя сертификата, если его следует проверить. |
|
|  | [getSerialNumber()](#getSerialNumber--) | Укажите серийный номер сертификата, если его следует проверить. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Укажите серийный номер сертификата, если его следует проверить. |
|
|  | [getSubject()](#getSubject--) | Укажите субъект сертификата, если его следует проверить. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Укажите субъект сертификата, если его следует проверить. |
|
|  | [getThumbprint()](#getThumbprint--) | Укажите отпечаток сертификата, если его следует проверить. |
|
|  | [setThumbprint(String value)](#setThumbprint-java.lang.String-) | Укажите отпечаток сертификата, если его следует проверить. |
|
|  | [getMatchType()](#getMatchType--) | Получает или задает проверку типа совпадения текста. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Получает или задает проверку типа совпадения текста. |
|
|  | [getExpired()](#getExpired--) | Указывает, истёк ли срок действия сертификата в результате проверки. |
|
|  | [setExpired(boolean value)](#setExpired-boolean-) | Указывает, истёк ли срок действия сертификата в результате проверки. |
|
|  | [getPerformChainValidation()](#getPerformChainValidation--) | Получить или задать, должен ли процесс проверки предоставлять проверку цепочки X.509 с использованием базовой политики проверки. |
|
|  | [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | Получить или задать, должен ли процесс проверки предоставлять проверку цепочки X.509 с использованием базовой политики проверки. |
|
|  | [toString()](#toString--) | Переопределяет преобразование в строку. |
|
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


Инициализирует новый экземпляр TextVerifyOptions со значениями по умолчанию.


### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


Инициализирует новый экземпляр CertificateVerifyOptions с объектом для проверки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | subject | java.lang.String | Субъект для проверки |
|

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


Укажите издателя сертификата, если его следует проверить.


**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


Укажите издателя сертификата, если его следует проверить.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Укажите серийный номер сертификата, если его следует проверить.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Укажите серийный номер сертификата, если его следует проверить.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Укажите субъект сертификата, если его следует проверить.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Укажите субъект сертификата, если его следует проверить.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Укажите отпечаток сертификата, если его следует проверить.


**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


Укажите отпечаток сертификата, если его следует проверить.


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

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


Указывает, истёк ли срок действия сертификата в результате проверки.
Свойство только для чтения.


**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


Указывает, истёк ли срок действия сертификата в результате проверки.
Свойство только для чтения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


Получить или задать, должен ли процесс проверки предоставлять проверку цепочки X.509 с использованием базовой политики проверки.
По умолчанию это значение равно true.


**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


Получить или задать, должен ли процесс проверки предоставлять проверку цепочки X.509 с использованием базовой политики проверки.
По умолчанию это значение равно true.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Переопределяет преобразование в строку.


**Returns:**
java.lang.String -
