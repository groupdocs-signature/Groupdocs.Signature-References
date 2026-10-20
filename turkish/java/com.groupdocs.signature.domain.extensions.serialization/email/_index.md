---
title: "E-posta"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "QR-Kod için E-posta formatını temsil eder."
type: docs
weight: 15
url: /tr/java/com.groupdocs.signature.domain.extensions.serialization/email/
---
**Inheritance:**
java.lang.Object
```
public class Email
```

QR-Kod için E-posta formatını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Email()](#Email--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getAddress()](#getAddress--) | E-posta adresini al veya ayarla. |
|
|  | [setAddress(String value)](#setAddress-java.lang.String-) | E-posta adresini al veya ayarla. |
|
|  | [getSubject()](#getSubject--) | E-posta konusunu al veya ayarla. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | E-posta konusunu al veya ayarla. |
|
|  | [getBody()](#getBody--) | E-posta mesajının gövdesini al veya ayarla. |
|
|  | [setBody(String value)](#setBody-java.lang.String-) | E-posta mesajının gövdesini al veya ayarla. |
|
|  | [equals(Object source)](#equals-java.lang.Object-) | E-posta özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
|
|  | [hashCode()](#hashCode--) | GetHashCode yöntemini geçersiz kılar |
|
### Email() {#Email--}
```
public Email()
```


### getAddress() {#getAddress--}
```
public final String getAddress()
```


E-posta adresini al veya ayarla.


**Returns:**
java.lang.String
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


E-posta adresini al veya ayarla.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


E-posta konusunu al veya ayarla.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


E-posta konusunu al veya ayarla.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getBody() {#getBody--}
```
public final String getBody()
```


E-posta mesajının gövdesini al veya ayarla.


**Returns:**
java.lang.String
### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


E-posta mesajının gövdesini al veya ayarla.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


E-posta özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | kaynak | java.lang.Object | Karşılaştırılacak e-posta nesnesi. |
|

**Returns:**
boolean - Geçilen adres nesnesi aynı türe sahipse ve tüm özellikleri bu örnek özelliklerine eşitse true döndürür.

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode yöntemini geçersiz kılar


**Returns:**
int - E-posta karma kodu

