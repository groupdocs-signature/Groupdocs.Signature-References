---
title: "SMS"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "SMS kısa mesaj hizmeti detaylarını temsil eder."
type: docs
weight: 18
url: /tr/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/sms/
---
**Inheritance:**
java.lang.Object
```
public class SMS
```

SMS kısa mesaj hizmeti detaylarını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SMS()](#SMS--) | Varsayılan değerlerle VCard örneği oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getNumber()](#getNumber--) | SMS alıcı telefon numarasını alır veya ayarlar. |
| [setNumber(String value)](#setNumber-java.lang.String-) | SMS alıcı telefon numarasını alır veya ayarlar. |
| [getMessage()](#getMessage--) | SMS mesaj içeriğini alır veya ayarlar. |
| [setMessage(String value)](#setMessage-java.lang.String-) | SMS mesaj içeriğini alır veya ayarlar. |
| [equals(Object obj)](#equals-java.lang.Object-) | SMS özelliklerini karşılaştırmak için Equals yöntemini geçersiz kılar. |
| [hashCode()](#hashCode--) | GetHashCode metodunu geçersiz kılar. |
### SMS() {#SMS--}
```
public SMS()
```


Varsayılan değerlerle VCard örneği oluşturur.

### getNumber() {#getNumber--}
```
public final String getNumber()
```


SMS alıcı telefon numarasını alır veya ayarlar.

**Returns:**
java.lang.String
### setNumber(String value) {#setNumber-java.lang.String-}
```
public final void setNumber(String value)
```


SMS alıcı telefon numarasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


SMS mesaj içeriğini alır veya ayarlar.

**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


SMS mesaj içeriğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


SMS özelliklerini karşılaştırmak için Equals yöntemini geçersiz kılar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak SMS nesnesi. |

**Returns:**
boolean - Geçilen SMS nesnesi aynı tipe sahipse ve tüm özellikleri bu örnek özelliklerine eşitse true döndürür.
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode metodunu geçersiz kılar.

**Returns:**
int - VCard karma kodu
