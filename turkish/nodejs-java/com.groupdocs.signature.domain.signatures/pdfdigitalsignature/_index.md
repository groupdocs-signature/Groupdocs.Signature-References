---
title: "PdfDigitalSignature"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Pdf Dijital imza özelliklerini içerir."
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.signature.domain.signatures/pdfdigitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
```
public class PdfDigitalSignature extends DigitalSignature
```

Pdf Dijital imza özelliklerini içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfDigitalSignature()](#PdfDigitalSignature--) | Pdf Digital Signature'ı sertifika olmadan başlatır. |
| [PdfDigitalSignature(KeyStore certificate)](#PdfDigitalSignature-java.security.KeyStore-) | Belirtilen sertifika ile Pdf Digital signature oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getContactInfo()](#getContactInfo--) | İmzalayan tarafından alıcının imzayı doğrulamak için imzalayanla iletişime geçebilmesini sağlamak amacıyla sağlanan bilgi, örn. |
| [setContactInfo(String value)](#setContactInfo-java.lang.String-) | İmzalayan tarafından alıcının imzayı doğrulamak için imzalayanla iletişime geçebilmesini sağlamak amacıyla sağlanan bilgi, örn. |
| [getLocation()](#getLocation--) | İmzanın CPU ana bilgisayar adı veya fiziksel konumu. |
| [setLocation(String value)](#setLocation-java.lang.String-) | İmzanın CPU ana bilgisayar adı veya fiziksel konumu. |
| [getReason()](#getReason--) | İmza nedeni, örneğin (I agree\u0420\u0406\u0420\u201a\u0412¦). |
| [setReason(String value)](#setReason-java.lang.String-) | İmza nedeni, örneğin (I agree\u0420\u0406\u0420\u201a\u0412¦). |
| [getType()](#getType--) | Pdf dijital imza türü. |
| [setType(int value)](#setType-int-) | Pdf dijital imza türü. |
| [getTimeStamp()](#getTimeStamp--) | Pdf dijital imza için zaman damgası. |
| [setTimeStamp(TimeStamp value)](#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) | Pdf dijital imza için zaman damgası. |
| [getShowProperties()](#getShowProperties--) | İmza özelliklerini gösterme/gizleme zorlaması. |
| [setShowProperties(boolean value)](#setShowProperties-boolean-) | İmza özelliklerini gösterme/gizleme zorlaması. |
| [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar. |
| [hashCode()](#hashCode--) | GetHashCode metodunu geçersiz kılar. |
| [deepClone()](#deepClone--) | Barcode Signature örneğini klonlar. |
### PdfDigitalSignature() {#PdfDigitalSignature--}
```
public PdfDigitalSignature()
```


Pdf Digital Signature'ı sertifika olmadan başlatır.

### PdfDigitalSignature(KeyStore certificate) {#PdfDigitalSignature-java.security.KeyStore-}
```
public PdfDigitalSignature(KeyStore certificate)
```


Belirtilen sertifika ile Pdf Digital signature oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sertifika | java.security.KeyStore | X509 sertifikası. |

### getContactInfo() {#getContactInfo--}
```
public final String getContactInfo()
```


İmzalayan tarafından alıcının imzayı doğrulamak için imzalayanla iletişime geçebilmesini sağlamak amacıyla sağlanan bilgi, ör. bir telefon numarası.

**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public final void setContactInfo(String value)
```


İmzalayan tarafından alıcının imzayı doğrulamak için imzalayanla iletişime geçebilmesini sağlamak amacıyla sağlanan bilgi, ör. bir telefon numarası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


İmzanın CPU ana bilgisayar adı veya fiziksel konumu.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


İmzanın CPU ana bilgisayar adı veya fiziksel konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getReason() {#getReason--}
```
public final String getReason()
```


İmza nedeni, örneğin (I agree\u0420\u0406\u0420\u201a\u0412¦).

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


İmza nedeni, örneğin (I agree\u0420\u0406\u0420\u201a\u0412¦).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Pdf dijital imza türü.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Pdf dijital imza türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTimeStamp() {#getTimeStamp--}
```
public final TimeStamp getTimeStamp()
```


Pdf dijital imzası için zaman damgası. Varsayılan değer null.

**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### setTimeStamp(TimeStamp value) {#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public final void setTimeStamp(TimeStamp value)
```


Pdf dijital imzası için zaman damgası. Varsayılan değer null.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### getShowProperties() {#getShowProperties--}
```
public final boolean getShowProperties()
```


İmza özelliklerinin gösterilmesini/gizlenmesini zorla. ShowProperties true olduğunda imza alanı, önceden tanımlı görünüm formatına sahiptir: Dijital olarak imzalanan \{ ContactInfo (\#getContactInfo.getContactInfo/\#setContactInfo(String).setContactInfo(String))\} Tarih: \{Date\} Sebep: \{ Reason (\#getReason.getReason/\#setReason(String).setReason(String))\} Konum: \{ Location (\#getLocation.getLocation/\#setLocation(String).setLocation(String))\} ShowProperties varsayılan olarak true.

**Returns:**
boolean
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public final void setShowProperties(boolean value)
```


İmza özelliklerinin gösterilmesini/gizlenmesini zorla. ShowProperties true olduğunda imza alanı, önceden tanımlı görünüm formatına sahiptir: Dijital olarak imzalanan \{ ContactInfo (\#getContactInfo.getContactInfo/\#setContactInfo(String).setContactInfo(String))\} Tarih: \{Date\} Sebep: \{ Reason (\#getReason.getReason/\#setReason(String).setReason(String))\} Konum: \{ Location (\#getLocation.getLocation/\#setLocation(String).setLocation(String))\} ShowProperties varsayılan olarak true.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imza | java.lang.Object | Karşılaştırılacak imza nesnesi. |

**Returns:**
boolean - Geçilen imza nesnesi aynı türe sahipse ve tüm özellikleri bu örnek özelliklerine eşitse true döndürür.
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode metodunu geçersiz kılar.

**Returns:**
int - İmza hash kodu
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Barcode Signature örneğini klonlar.

**Returns:**
java.lang.Object - Kopyalanmış Barcode Signature örneğini döndürür.
