---
title: "CertificateVerifyOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Sertifika belgelerini doğrulama seçeneklerini tutar."
type: docs
weight: 11
url: /tr/java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

Sertifika belgelerini doğrulama seçeneklerini tutar.

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [CertificateVerifyOptions()](#CertificateVerifyOptions--) | TextVerifyOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
|
|  | [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | Doğrulanacak konu ile CertificateVerifyOptions sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getIssuer()](#getIssuer--) | Doğrulanacaksa Sertifika Yayıncısını belirtin. |
|
|  | [setIssuer(String value)](#setIssuer-java.lang.String-) | Doğrulanacaksa Sertifika Yayıncısını belirtin. |
|
|  | [getSerialNumber()](#getSerialNumber--) | Doğrulanacaksa Sertifika Seri Numarasını belirtin. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Doğrulanacaksa Sertifika Seri Numarasını belirtin. |
|
|  | [getSubject()](#getSubject--) | Doğrulanacaksa Sertifika konusunu belirtin. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Doğrulanacaksa Sertifika konusunu belirtin. |
|
|  | [getThumbprint()](#getThumbprint--) | Doğrulanacaksa Sertifika Parmak İzini belirtin. |
|
|  | [setThumbprint(String value)](#setThumbprint-java.lang.String-) | Doğrulanacaksa Sertifika Parmak İzini belirtin. |
|
|  | [getMatchType()](#getMatchType--) | Metin Eşleşme Türü doğrulamasını alır veya ayarlar. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Metin Eşleşme Türü doğrulamasını alır veya ayarlar. |
|
|  | [getExpired()](#getExpired--) | Doğrulama sonucuna göre sertifikanın süresi dolmuş olup olmadığını gösterir. |
|
|  | [setExpired(boolean value)](#setExpired-boolean-) | Doğrulama sonucuna göre sertifikanın süresi dolmuş olup olmadığını gösterir. |
|
|  | [getPerformChainValidation()](#getPerformChainValidation--) | Doğrulama sürecinin temel doğrulama politikası kullanarak X.509 zincir doğrulaması sağlaması gerekip gerekmediğini alın veya ayarlayın. |
|
|  | [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | Doğrulama sürecinin temel doğrulama politikası kullanarak X.509 zincir doğrulaması sağlaması gerekip gerekmediğini alın veya ayarlayın. |
|
|  | [toString()](#toString--) | Stringe dönüşümü geçersiz kılar. |
|
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


TextVerifyOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.


### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


Doğrulanacak konu ile CertificateVerifyOptions sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | konu | java.lang.String | Doğrulanacak konu |
|

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


Doğrulanacaksa Sertifika Yayıncısını belirtin.


**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


Doğrulanacaksa Sertifika Yayıncısını belirtin.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Doğrulanacaksa Sertifika Seri Numarasını belirtin.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Doğrulanacaksa Sertifika Seri Numarasını belirtin.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Doğrulanacaksa Sertifika konusunu belirtin.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Doğrulanacaksa Sertifika konusunu belirtin.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Doğrulanacaksa Sertifika Parmak İzini belirtin.


**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


Doğrulanacaksa Sertifika Parmak İzini belirtin.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Metin Eşleşme Türü doğrulamasını alır veya ayarlar.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Metin Eşleşme Türü doğrulamasını alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


Doğrulama sonucuna göre sertifikanın süresi dolmuş olup olmadığını gösterir.
Özellik yalnızca okunabilir.


**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


Doğrulama sonucuna göre sertifikanın süresi dolmuş olup olmadığını gösterir.
Özellik yalnızca okunabilir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


Doğrulama sürecinin temel doğrulama politikası kullanarak X.509 zincir doğrulaması sağlaması gerekip gerekmediğini alın veya ayarlayın.
Varsayılan olarak bu değer doğrudur.


**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


Doğrulama sürecinin temel doğrulama politikası kullanarak X.509 zincir doğrulaması sağlaması gerekip gerekmediğini alın veya ayarlayın.
Varsayılan olarak bu değer doğrudur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Stringe dönüşümü geçersiz kılar.


**Returns:**
java.lang.String -
