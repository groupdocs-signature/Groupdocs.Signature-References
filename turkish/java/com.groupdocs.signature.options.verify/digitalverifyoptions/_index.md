---
title: "DigitalVerifyOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Belge Dijital imzasını doğrulama seçeneklerini tutar."
type: docs
weight: 12
url: /tr/java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

Belge Dijital imzasını doğrulama seçeneklerini tutar.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](../https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/)
* Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Digital signatures in a document and additional settings](../)

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [DigitalVerifyOptions()](#DigitalVerifyOptions--) | Varsayılan değerlerle Dijital Doğrulama Seçeneği oluşturur. |
|
|  | [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | Verilen dijital sertifika guid'i ile Dijital Doğrulama Seçeneği oluşturur. |
|
|  | [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | Verilen sertifika akışı ile Dijital Doğrulama Seçeneği oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Sertifika Guid'i veya Akışı'ndan X509Certificate2 Sertifikasını al. |
|
|  | [getPassword()](#getPassword--) | Gerekirse Dijital Sertifikanın parolası. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Gerekirse Dijital Sertifikanın parolası. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Dijital Sertifikanın dosya guid'i. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Dijital Sertifikanın dosya guid'i. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Dijital Sertifikanın akışı. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Dijital Sertifikanın akışı. |
|
|  | [getComments()](#getComments--) | Doğrulanacak Dijital İmzanın yorumları. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Doğrulanacak Dijital İmzanın yorumları. |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Doğrulanacak Dijital İmzanın tarih ve saat aralığı. |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Doğrulanacak Dijital İmzanın tarih ve saat aralığı. |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | Doğrulanacak Dijital İmzanın tarih ve saat aralığı. |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Doğrulanacak Dijital İmzanın tarih ve saat aralığı. |
|
|  | [getReason()](#getReason--) | Doğrulanacak Dijital İmzanın nedeni. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Doğrulanacak Dijital İmzanın nedeni. |
|
|  | [getContact()](#getContact--) | Doğrulanacak İmza iletişim bilgisi. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | Doğrulanacak İmza iletişim bilgisi. |
|
|  | [getLocation()](#getLocation--) | Doğrulanacak İmza konumu. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Doğrulanacak İmza konumu. |
|
|  | [getSubjectName()](#getSubjectName--) | Doğrulanacak sertifikanın konu ayırt edici adı. |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Doğrulanacak sertifikanın konu ayırt edici adı. |
|
|  | [getIssuerName()](#getIssuerName--) | Doğrulanacak sertifikanın veren adı. |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Doğrulanacak sertifikanın veren adı. |
|
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


Varsayılan değerlerle Dijital Doğrulama Seçeneği oluşturur.


### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


Verilen dijital sertifika guid'i ile Dijital Doğrulama Seçeneği oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | certificateGuid | java.lang.String | Dijital sertifikaya dosya yolu. |
|

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


Verilen sertifika akışı ile Dijital Doğrulama Seçeneği oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Sertifikanın akışı. |
|

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


Sertifika Guid'i veya Akışı'ndan X509Certificate2 Sertifikasını al.


**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Gerekirse Dijital Sertifikanın parolası.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Gerekirse Dijital Sertifikanın parolası.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Dijital Sertifikanın dosya guid'i.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


Dijital Sertifikanın dosya guid'i.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Dijital Sertifikanın akışı.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Dijital Sertifikanın akışı.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Doğrulanacak Dijital İmzanın yorumları.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Doğrulanacak Dijital İmzanın yorumları.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


Doğrulanacak Dijital İmzanın tarih ve saat aralığı. Null olabilen değer yok sayılacak.


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


Doğrulanacak Dijital İmzanın tarih ve saat aralığı. Null olabilen değer yok sayılacak.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


Doğrulanacak Dijital İmzanın tarih ve saat aralığı. Null olabilen değer yok sayılacak.


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


Doğrulanacak Dijital İmzanın tarih ve saat aralığı. Null olabilen değer yok sayılacak.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Doğrulanacak Dijital İmzanın nedeni.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Doğrulanacak Dijital İmzanın nedeni.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Doğrulanacak İmza iletişim bilgisi.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Doğrulanacak İmza iletişim bilgisi.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Doğrulanacak İmza konumu.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Doğrulanacak İmza konumu.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Doğrulanacak sertifikanın konu ayırt edici adı. Değer büyük/küçük harfe duyarlıdır.
Bu özellik ayarlanırsa doğrulama, İmza konu adının verilen değeri içerip içermediğini veya eşit olup olmadığını kontrol eder.


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Doğrulanacak sertifikanın konu ayırt edici adı. Değer büyük/küçük harfe duyarlıdır.
Bu özellik ayarlanırsa doğrulama, İmza konu adının verilen değeri içerip içermediğini veya eşit olup olmadığını kontrol eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Doğrulanacak sertifikanın veren adı. Değer büyük/küçük harfe duyarlıdır.
Bu özellik ayarlanırsa doğrulama, İmzanın veren adının gönderilen değeri içerip içermediğini veya eşit olup olmadığını kontrol eder.


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Doğrulanacak sertifikanın veren adı. Değer büyük/küçük harfe duyarlıdır.
Bu özellik ayarlanırsa doğrulama, İmzanın veren adının gönderilen değeri içerip içermediğini veya eşit olup olmadığını kontrol eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

