---
title: "DigitalSignature"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Dijital imza özelliklerini içerir."
type: docs
weight: 12
url: /tr/java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

Dijital imza özelliklerini içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [DigitalSignature()](#DigitalSignature--) | DigitalSignature'ı varsayılan parametrelerle başlat. |
|
|  | [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | DigitalSignature'ı bilinen SignatureId ile başlat. |
|
|  | [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | Belirtilen sertifika ile DigitalSignature oluştur. |
|
|  | [DigitalSignature(X509Certificate cert, PrivateKey key)](#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | X509Certificate sertifikası ve PrivateKey temel alınarak Dijital imza oluştur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | KeyStore sertifikasını alır veya ayarlar. |
|
|  | [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | KeyStore sertifikasını alır veya ayarlar. |
|
|  | [getX509Certificate()](#getX509Certificate--) | X509 sertifikasını alır veya ayarlar. |
|
|  | [setX509Certificate(X509Certificate value)](#setX509Certificate-java.security.cert.X509Certificate-) | X509 sertifikasını alır veya ayarlar. |
|
|  | [getPrivateKey()](#getPrivateKey--) | Sertifikanın PrivateKey'ini alır veya ayarlar. |
|
|  | [setPrivateKey(PrivateKey value)](#setPrivateKey-java.security.PrivateKey-) | Sertifikanın PrivateKey'ini alır veya ayarlar. |
|
|  | [getCertificateName()](#getCertificateName--) | X509 sertifika adını alır veya ayarlar. |
|
|  | [setCertificateName(String value)](#setCertificateName-java.lang.String-) | X509 sertifika adını alır veya ayarlar. |
|
|  | [getComments()](#getComments--) | İmzalama amacı yorumunu alır veya ayarlar. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | İmzalama amacı yorumunu alır veya ayarlar. |
|
|  | [isValid()](#isValid--) | Bu dijital imza geçerli ve belge değiştirilmemişse true değerini tutar. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Bu dijital imza geçerli ve belge değiştirilmemişse true değerini tutar. |
|
|  | [getSignTime()](#getSignTime--) | Belgenin imzalandığı zamanı alır veya ayarlar. |
|
|  | [setSignTime(Date value)](#setSignTime-java.util.Date-) | Belgenin imzalandığı zamanı alır veya ayarlar. |
|
|  | [getXAdESType()](#getXAdESType--) | XAdES türü |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | XAdES türü |
XAdESType
.
|
|  | [getThumbprint()](#getThumbprint--) | Bir sertifikanın parmak izini alır. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
|
|  | [hashCode()](#hashCode--) | GetHashCode yöntemini geçersiz kılar |
|
|  | [deepClone()](#deepClone--) | Barcode Signature örneğini klonla. |
|
|  | [loadDigitalSignatures()](#loadDigitalSignatures--) | Tüm sistem X509 Sertifika Depolarından Dijital imza yükle. |
|
|  | [loadDigitalSignatures(StoreName storeName)](#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-) | Geçilen X509 Sertifika Deposundan Dijital imza yükle. |
|
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


DigitalSignature'ı varsayılan parametrelerle başlat.


### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


DigitalSignature'ı bilinen SignatureId ile başlat.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signatureId | java.lang.String |  |

### DigitalSignature(KeyStore certificate) {#DigitalSignature-java.security.KeyStore-}
```
public DigitalSignature(KeyStore certificate)
```


Belirtilen sertifika ile DigitalSignature oluştur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | sertifika | java.security.KeyStore | X509 sertifikası. |
|

### DigitalSignature(X509Certificate cert, PrivateKey key) {#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
```
public DigitalSignature(X509Certificate cert, PrivateKey key)
```


X509Certificate sertifikası ve PrivateKey temel alınarak Dijital imza oluştur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | cert | java.security.cert.X509Certificate | X509Certificate sertifikası. |
|
|  | key | java.security.PrivateKey | Sertifikanın PrivateKey'i. |
|

### getCertificate() {#getCertificate--}
```
public final KeyStore getCertificate()
```


KeyStore sertifikasını alır veya ayarlar.


**Returns:**
java.security.KeyStore
### setCertificate(KeyStore value) {#setCertificate-java.security.KeyStore-}
```
public final void setCertificate(KeyStore value)
```


KeyStore sertifikasını alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.security.KeyStore |  |

### getX509Certificate() {#getX509Certificate--}
```
public final X509Certificate getX509Certificate()
```


X509 sertifikasını alır veya ayarlar.


**Returns:**
java.security.cert.X509Certificate
### setX509Certificate(X509Certificate value) {#setX509Certificate-java.security.cert.X509Certificate-}
```
public final void setX509Certificate(X509Certificate value)
```


X509 sertifikasını alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.security.cert.X509Certificate |  |

### getPrivateKey() {#getPrivateKey--}
```
public final PrivateKey getPrivateKey()
```


Sertifikanın PrivateKey'ini alır veya ayarlar.


**Returns:**
java.security.PrivateKey
### setPrivateKey(PrivateKey value) {#setPrivateKey-java.security.PrivateKey-}
```
public final void setPrivateKey(PrivateKey value)
```


Sertifikanın PrivateKey'ini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.security.PrivateKey |  |

### getCertificateName() {#getCertificateName--}
```
public final String getCertificateName()
```


X509 sertifika adını alır veya ayarlar.


**Returns:**
java.lang.String
### setCertificateName(String value) {#setCertificateName-java.lang.String-}
```
public final void setCertificateName(String value)
```


X509 sertifika adını alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


İmzalama amacı yorumunu alır veya ayarlar.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


İmzalama amacı yorumunu alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


Bu dijital imza geçerli ve belge değiştirilmemişse true değerini tutar.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Bu dijital imza geçerli ve belge değiştirilmemişse true değerini tutar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


Belgenin imzalandığı zamanı alır veya ayarlar.


**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


Belgenin imzalandığı zamanı alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES türü
XAdESType
. Varsayılan değer None'dur (XAdES kapalı).
Şu anda XAdES imza türü yalnızca Spreadsheet belgeleri için desteklenmektedir.


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES türü
XAdESType
. Varsayılan değer None'dur (XAdES kapalı).
Şu anda XAdES imza türü yalnızca Spreadsheet belgeleri için desteklenmektedir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Bir sertifikanın parmak izini alır.


**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | imza | java.lang.Object | Karşılaştırılacak imza nesnesi. |
|

**Returns:**
boolean - Geçilen imza nesnesi aynı türe sahipse ve tüm özellikleri bu örnek özelliklerine eşitse true döndürür.

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode yöntemini geçersiz kılar


**Returns:**
int - İmza karma kodu

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Barcode Signature örneğini klonla.


**Returns:**
java.lang.Object - Kopyalanmış Barkod İmza örneğini döndürür.

### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


Tüm sistem X509 Sertifika Depolarından Dijital imza yükle.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) Dijital İmzaların listesini döndürür.

### loadDigitalSignatures(StoreName storeName) {#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-}
```
public static List<DigitalSignature> loadDigitalSignatures(StoreName storeName)
```


Geçilen X509 Sertifika Deposundan Dijital imza yükle.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| storeName | [StoreName](../../com.groupdocs.signature.domain.signatures/storename) |  |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) Dijital İmzaların listesini döndürür.

