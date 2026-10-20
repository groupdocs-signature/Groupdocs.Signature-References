---
title: "DigitalSignOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Dijital imza seçeneklerini temsil eder."
type: docs
weight: 11
url: /tr/java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

Dijital imza seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [DigitalSignOptions()](#DigitalSignOptions--) | DigitalSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
|
|  | [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | DigitalSignOptions sınıfının yeni bir örneğini sertifika dosyasıyla başlatır. |
|
|  | [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | DigitalSignOptions sınıfının yeni bir örneğini sertifika akışıyla başlatır. |
|
|  | [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | DigitalSignOptions sınıfının yeni bir örneğini sertifika dosyası ve görüntü dosyasıyla başlatır. |
|
|  | [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | DigitalSignOptions sınıfının yeni bir örneğini sertifika dosyası ve görüntü akışıyla başlatır. |
|
|  | [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | DigitalSignOptions sınıfının yeni bir örneğini sertifika akışı ve görüntü dosyasıyla başlatır. |
|
|  | [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | DigitalSignOptions sınıfının yeni bir örneğini sertifika akışı ve görüntü akışıyla başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getReason()](#getReason--) | İmzanın nedenini alır veya ayarlar. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | İmzanın nedenini alır veya ayarlar. |
|
|  | [getContact()](#getContact--) | İmzanın iletişim bilgisini alır veya ayarlar. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | İmzanın iletişim bilgisini alır veya ayarlar. |
|
|  | [getLocation()](#getLocation--) | İmza konumunu alır veya ayarlar. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | İmza konumunu alır veya ayarlar. |
|
|  | [getPassword()](#getPassword--) | Dijital sertifikanın şifresini alır veya ayarlar. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Dijital sertifikanın şifresini alır veya ayarlar. |
|
|  | [getSignature()](#getSignature--) | Belge dijital imzasının özelliklerini alır veya ayarlar. |
|
|  | [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | Belge dijital imzasının özelliklerini alır veya ayarlar. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Dijital sertifika dosya yolunu alır veya ayarlar. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Dijital sertifika dosya GUID'sini alır veya ayarlar. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Dijital sertifika akışını alır veya ayarlar. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Dijital sertifika akışını alır veya ayarlar. |
|
|  | [getVisible()](#getVisible--) | İmzanın görünürlüğünü alır veya ayarlar. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | İmzanın görünürlüğünü alır veya ayarlar. |
|
|  | [getUseLtv()](#getUseLtv--) | LTV (Uzun Süreli Doğrulama) doğrulama bayrağını alır/ayarlar. |
|
|  | [setUseLtv(boolean value)](#setUseLtv-boolean-) | LTV (Uzun Süreli Doğrulama) doğrulama bayrağını alır/ayarlar. |
|
|  | [getAllowExpired()](#getAllowExpired--) | Geçerlilik süresi sona ermiş bir sertifika ile imzalamayı sağlayan bayrağı alır veya ayarlar. |
|
|  | [setAllowExpired(boolean value)](#setAllowExpired-boolean-) | Geçerlilik süresi sona ermiş bir sertifika ile imzalamayı sağlayan bayrağı alır veya ayarlar. |
|
|  | [getAllowNotYetValid()](#getAllowNotYetValid--) | Henüz geçerlilik süresi başlamamış bir sertifika ile imzalamayı sağlayan bayrağı alır veya ayarlar. |
|
|  | [setAllowNotYetValid(boolean value)](#setAllowNotYetValid-boolean-) | Henüz geçerlilik süresi başlamamış bir sertifika ile imzalamayı sağlayan bayrağı alır veya ayarlar. |
|
|  | [getCustomSignHash()](#getCustomSignHash--) | Özel bir hash-imzalama uygulamasını alır veya ayarlar, çağıranların kendi uygulamalarını eklemesine izin verir |
dijital imzalama mantığını (HSM, uzaktan imzalayıcı, yazılım anahtar deposu vb.).
|
|  | [setCustomSignHash(ICustomSignHash value)](#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-) | Özel bir hash-imzalama uygulamasını ayarlar, çağıranların kendi uygulamalarını eklemesine izin verir |
dijital imzalama mantığını.
|
|  | [getXAdESType()](#getXAdESType--) | XAdES türü |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | XAdES türü |
XAdESType
.
|
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
|  | [toString()](#toString--) | Dize dönüşümünü geçersiz kıl. |
|
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


DigitalSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.


### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


DigitalSignOptions sınıfının yeni bir örneğini sertifika dosyasıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Dijital sertifika dosya yolu |
|

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


DigitalSignOptions sınıfının yeni bir örneğini sertifika akışıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Dijital Sertifika akışı |
|

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


DigitalSignOptions sınıfının yeni bir örneğini sertifika dosyası ve görüntü dosyasıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Dijital sertifika dosya yolu |
|
|  | imageFilePath | java.lang.String | İmza Görünümü görüntü dosya yolu |
|

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


DigitalSignOptions sınıfının yeni bir örneğini sertifika dosyası ve görüntü akışıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Dijital sertifika dosya yolu |
|
|  | appearenceImageStream | java.io.InputStream | İmza Görünümü görüntü akışı |
|

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


DigitalSignOptions sınıfının yeni bir örneğini sertifika akışı ve görüntü dosyasıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Dijital Sertifika akışı |
|
|  | imageFilePath | java.lang.String | İmza Görünümü görüntü dosya yolu |
|

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


DigitalSignOptions sınıfının yeni bir örneğini sertifika akışı ve görüntü akışıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Dijital Sertifika akışı |
|
|  | appearenceImageStream | java.io.InputStream | İmza Görünümü görüntü akışı |
|

### getReason() {#getReason--}
```
public final String getReason()
```


İmzanın nedenini alır veya ayarlar.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


İmzanın nedenini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


İmzanın iletişim bilgisini alır veya ayarlar.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


İmzanın iletişim bilgisini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


İmza konumunu alır veya ayarlar.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


İmza konumunu alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Dijital sertifikanın şifresini alır veya ayarlar.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Dijital sertifikanın şifresini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


Belge dijital imzasının özelliklerini alır veya ayarlar.


**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


Belge dijital imzasının özelliklerini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Dijital sertifika dosya yolunu alır veya ayarlar.
Bu özellik yalnızca CertificateStream belirtilmemişse kullanılır.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


Dijital sertifika dosya GUID'sini alır veya ayarlar.
Bu özellik yalnızca CertificateStream belirtilmemişse kullanılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Dijital sertifika akışını alır veya ayarlar.
Bu özellik belirtilirse her zaman CertificateGuid yerine kullanılır.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Dijital sertifika akışını alır veya ayarlar.
Bu özellik belirtilirse her zaman CertificateGuid yerine kullanılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


İmzanın görünürlüğünü alır veya ayarlar.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


İmzanın görünürlüğünü alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


LTV (Uzun Süreli Doğrulama) doğrulama bayrağını alır/ayarlar.


**Returns:**
boolean
### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


LTV (Uzun Süreli Doğrulama) doğrulama bayrağını alır/ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getAllowExpired() {#getAllowExpired--}
```
public final boolean getAllowExpired()
```


Geçerlilik süresi sona ermiş bir sertifika ile imzalamayı sağlayan bayrağı alır veya ayarlar.
Varsayılan değer false'tur: süresi dolmuş bir sertifika ile imzalama hata verir
GroupDocsSignatureException
,
ve belge imzalanmamış.


Doğrulayıcılar, süresi dolmuş bir sertifika ile yapılmış imzayı geçersiz olarak rapor eder. Bu özelliği yalnızca ... olduğunda true olarak ayarlayın
Bu tür bir imzaya yine de ihtiyacınız varsa, örneğin eski bir sertifika ile test etmek için. Belge o zaman imzalanır ve bir
uyarı, ayarlanan günlüğe yazılır
SignatureSettings
.


Sertifika, UTC'deki mevcut zamanla karşılaştırılır, ... ile değil
DigitalSignature.SignTime
. Bayrak
verilen sertifikaya uygulanır
CertificateFilePath
,
CertificateStream
or
Signature
,
ve, bir elektronik tablo imzalandığında, ilk ... sertifikasına
DigitalVBA
uzantı. Digital
görüntü imzaları bir sertifika kullanmaz ve kontrol edilmez. Geçerlilik süresi henüz ... olmayan bir sertifika
başlamamış, ... tarafından kontrol edilir
AllowNotYetValid
.


**Returns:**
boolean
### setAllowExpired(boolean value) {#setAllowExpired-boolean-}
```
public final void setAllowExpired(boolean value)
```


Geçerlilik süresi sona ermiş bir sertifika ile imzalamayı sağlayan bayrağı alır veya ayarlar.
Varsayılan değer false'tur. Bakınız #getAllowExpired().getAllowExpired().


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getAllowNotYetValid() {#getAllowNotYetValid--}
```
public final boolean getAllowNotYetValid()
```


Henüz geçerlilik süresi başlamamış bir sertifika ile imzalamayı sağlayan bayrağı alır veya ayarlar.
Varsayılan değer false'tur: böyle bir sertifika ile imzalama bir istisna fırlatır
GroupDocsSignatureException
,
ve belge imzalanmamış.


Doğrulayıcılar, sertifikanın geçerli olmadan önce yapılmış bir imzayı geçersiz olarak rapor eder. Böyle bir sertifika
genellikle daha sonraki bir tarih için verilir veya bilgisayarın saati yanlıştır. Bu özellik true olduğunda, belge
imzalanır ve ayarlanan günlüğe bir uyarı yazılır
SignatureSettings
.


Sertifika, UTC'deki mevcut zamanla karşılaştırılır. Bayrak aynı sertifikalara uygulanır

AllowExpired
, geçerlilik süresi sona ermiş sertifikaları kontrol eder.


**Returns:**
boolean
### setAllowNotYetValid(boolean value) {#setAllowNotYetValid-boolean-}
```
public final void setAllowNotYetValid(boolean value)
```


Henüz geçerlilik süresi başlamamış bir sertifika ile imzalamayı sağlayan bayrağı alır veya ayarlar.
Varsayılan değer false'tur. Bakın #getAllowNotYetValid().getAllowNotYetValid().


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getCustomSignHash() {#getCustomSignHash--}
```
public final ICustomSignHash getCustomSignHash()
```


Özel bir hash-imzalama uygulamasını alır veya ayarlar, çağıranların kendi uygulamalarını eklemesine izin verir
dijital imzalama mantığını (HSM, uzaktan imzalayıcı, yazılım anahtar deposu vb.).


**Returns:**
[ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash)
### setCustomSignHash(ICustomSignHash value) {#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-}
```
public final void setCustomSignHash(ICustomSignHash value)
```


Özel bir hash-imzalama uygulamasını ayarlar, çağıranların kendi uygulamalarını eklemesine izin verir
dijital imzalama mantığını.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash) |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES türü
XAdESType
. Varsayılan değer None'dur (XAdES kapalı).
Şu anda XAdES imza türü yalnızca .NET Framework altında Spreadsheet belgeleri için desteklenmektedir ( .NET Standard altında değil).


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES türü
XAdESType
. Varsayılan değer None'dur (XAdES kapalı).
Şu anda XAdES imza türü yalnızca .NET Framework altında Spreadsheet belgeleri için desteklenmektedir ( .NET Standard altında değil).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSignatureLineId() {#getSignatureLineId--}
```
public final UUID getSignatureLineId()
```




**Returns:**
java.util.UUID
### setSignatureLineId(UUID value) {#setSignatureLineId-java.util.UUID-}
```
public final void setSignatureLineId(UUID value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kıl.


**Returns:**
java.lang.String -
