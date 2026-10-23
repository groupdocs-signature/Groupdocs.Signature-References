---
title: "E-posta"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "QR-Kod için E-posta formatını temsil eder."
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/email/
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
| [getAddress()](#getAddress--) | E-posta adresini al veya ayarla. |
| [setAddress(String value)](#setAddress-java.lang.String-) | E-posta adresini al veya ayarla. |
| [getSubject()](#getSubject--) | E-posta Konusunu al veya ayarla. |
| [setSubject(String value)](#setSubject-java.lang.String-) | E-posta Konusunu al veya ayarla. |
| [getBody()](#getBody--) | E-posta mesajının Gövdesini al veya ayarla. |
| [setBody(String value)](#setBody-java.lang.String-) | E-posta mesajının Gövdesini al veya ayarla. |
| [equals(Object source)](#equals-java.lang.Object-) | Email özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
| [hashCode()](#hashCode--) | GetHashCode metodunu geçersiz kılar. |
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


E-posta Konusunu al veya ayarla.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


E-posta Konusunu al veya ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getBody() {#getBody--}
```
public final String getBody()
```


E-posta mesajının Gövdesini al veya ayarla.

**Returns:**
java.lang.String
### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


E-posta mesajının Gövdesini al veya ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


Email özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kaynak | java.lang.Object | Karşılaştırılacak Email nesnesi. |

**Returns:**
boolean - Geçilen adres nesnesi aynı tipe sahipse ve tüm özellikleri bu örnek özelliklerine eşitse true döndürür.
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode metodunu geçersiz kılar.

**Returns:**
int - Email karma kodu
