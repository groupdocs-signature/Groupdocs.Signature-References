---
title: "CertificateVerifyOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Sertifika belgelerini doğrulamak için seçenekleri tutar."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

Sertifika belgelerini doğrulamak için seçenekleri tutar.

--------------------

 **Learn more** 

 *  
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CertificateVerifyOptions()](#CertificateVerifyOptions--) | TextVerifyOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | CertificateVerifyOptions sınıfının yeni bir örneğini doğrulanacak konu ile başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIssuer()](#getIssuer--) | Doğrulanması gerekiyorsa Sertifika Yayıncısını belirtin. |
| [setIssuer(String value)](#setIssuer-java.lang.String-) | Doğrulanması gerekiyorsa Sertifika Yayıncısını belirtin. |
| [getSerialNumber()](#getSerialNumber--) | Doğrulanması gerekiyorsa Sertifika Seri Numarasını belirtin. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Doğrulanması gerekiyorsa Sertifika Seri Numarasını belirtin. |
| [getSubject()](#getSubject--) | Doğrulanması gerekiyorsa Sertifika konusunu belirtin. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Doğrulanması gerekiyorsa Sertifika konusunu belirtin. |
| [getThumbprint()](#getThumbprint--) | Doğrulanması gerekiyorsa Sertifika Parmak İzini belirtin. |
| [setThumbprint(String value)](#setThumbprint-java.lang.String-) | Doğrulanması gerekiyorsa Sertifika Parmak İzini belirtin. |
| [getMatchType()](#getMatchType--) | Text Match Type doğrulamasını alır veya ayarlar. |
| [setMatchType(int value)](#setMatchType-int-) | Text Match Type doğrulamasını alır veya ayarlar. |
| [getExpired()](#getExpired--) | Sertifikanın süresi dolmuş olup olmadığını doğrulama sonucuna göre gösterir. |
| [setExpired(boolean value)](#setExpired-boolean-) | Sertifikanın süresi dolmuş olup olmadığını doğrulama sonucuna göre gösterir. |
| [getPerformChainValidation()](#getPerformChainValidation--) | Doğrulama sürecinin temel doğrulama politikası kullanarak X.509 zincir doğrulaması sağlaması gerektiğini alır veya ayarlar. |
| [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | Doğrulama sürecinin temel doğrulama politikası kullanarak X.509 zincir doğrulaması sağlaması gerektiğini alır veya ayarlar. |
| [toString()](#toString--) | String'e dönüşümünü geçersiz kılar. |
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


TextVerifyOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


CertificateVerifyOptions sınıfının yeni bir örneğini doğrulanacak konu ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konu | java.lang.String | Doğrulanacak konu |

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


Doğrulanması gerekiyorsa Sertifika Yayıncısını belirtin.

**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


Doğrulanması gerekiyorsa Sertifika Yayıncısını belirtin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Doğrulanması gerekiyorsa Sertifika Seri Numarasını belirtin.

**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Doğrulanması gerekiyorsa Sertifika Seri Numarasını belirtin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Doğrulanması gerekiyorsa Sertifika konusunu belirtin.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Doğrulanması gerekiyorsa Sertifika konusunu belirtin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Doğrulanması gerekiyorsa Sertifika Parmak İzini belirtin.

**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


Doğrulanması gerekiyorsa Sertifika Parmak İzini belirtin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Text Match Type doğrulamasını alır veya ayarlar.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Text Match Type doğrulamasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


Sertifikanın süresi dolmuş olup olmadığını doğrulama sonucuna göre gösterir. Özellik yalnızca okunabilir.

**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


Sertifikanın süresi dolmuş olup olmadığını doğrulama sonucuna göre gösterir. Özellik yalnızca okunabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


Doğrulama sürecinin temel doğrulama politikası kullanarak X.509 zincir doğrulaması sağlaması gerektiğini alır veya ayarlar. Varsayılan olarak bu değer doğrudur.

**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


Doğrulama sürecinin temel doğrulama politikası kullanarak X.509 zincir doğrulaması sağlaması gerektiğini alır veya ayarlar. Varsayılan olarak bu değer doğrudur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### toString() {#toString--}
```
public String toString()
```


String'e dönüşümünü geçersiz kılar.

**Returns:**
java.lang.String -
