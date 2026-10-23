---
title: "EPC"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Avrupa Ödeme Konseyi Hızlı Yanıt Kodunu temsil eder."
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/epc/
---
**Inheritance:**
java.lang.Object
```
public final class EPC
```

Avrupa Ödeme Konseyi Hızlı Yanıt Kodunu temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EPC()](#EPC--) | Yeni EPC nesnesi oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getName()](#getName--) | Lehdarın adını alır veya ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Lehdarın adını alır veya ayarlar. |
| [getBIC()](#getBIC--) | Lehdarın BIC'sini (en fazla 11 karakter) alır veya ayarlar. |
| [setBIC(String value)](#setBIC-java.lang.String-) | Lehdarın BIC'sini (en fazla 11 karakter) alır veya ayarlar. |
| [getIBAN()](#getIBAN--) | Lehdarın hesabını (IBAN) alır veya ayarlar. |
| [setIBAN(String value)](#setIBAN-java.lang.String-) | Lehdarın hesabını (IBAN) alır veya ayarlar. |
| [getAmount()](#getAmount--) | Tutarı alır veya ayarlar. |
| [setAmount(double value)](#setAmount-double-) | Tutarı alır veya ayarlar. |
| [getCode()](#getCode--) | İş kodunu (en fazla 4 karakter) alır veya ayarlar. |
| [setCode(String value)](#setCode-java.lang.String-) | İş kodunu (en fazla 4 karakter) alır veya ayarlar. |
| [getReference()](#getReference--) | Ödeme referansını (azami 35 karakter) alır veya ayarlar. |
| [setReference(String value)](#setReference-java.lang.String-) | Ödeme referansını (azami 35 karakter) alır veya ayarlar. |
| [getRemittance()](#getRemittance--) | Gönderim bilgilerini (azami 140 karakter) alır veya ayarlar. |
| [setRemittance(String value)](#setRemittance-java.lang.String-) | Gönderim bilgilerini (azami 140 karakter) alır veya ayarlar. |
| [getInformation()](#getInformation--) | İpucu bilgisini alır veya ayarlar. |
| [setInformation(String value)](#setInformation-java.lang.String-) | İpucu bilgisini alır veya ayarlar. |
| [getVersion()](#getVersion--) | EPC / SEPA QR-Kodu sürüm uygulaması. |
| [setVersion(String value)](#setVersion-java.lang.String-) | EPC / SEPA QR-Kodu sürüm uygulaması. |
| [getCharset()](#getCharset--) | EPC / SEPA QR-Kodu karakter seti uygulaması. |
| [setCharset(String value)](#setCharset-java.lang.String-) | EPC / SEPA QR-Kodu karakter seti uygulaması. |
| [getIdentification()](#getIdentification--) | EPC / SEPA QR-Kodu tanımlaması. |
| [setIdentification(String value)](#setIdentification-java.lang.String-) | EPC / SEPA QR-Kodu tanımlaması. |
| [equals(Object source)](#equals-java.lang.Object-) | EPC özelliklerini karşılaştırmak için Equals yöntemini geçersiz kılar. |
| [hashCode()](#hashCode--) | GetHashCode metodunu geçersiz kılar. |
### EPC() {#EPC--}
```
public EPC()
```


Yeni EPC nesnesi oluşturur.

### getName() {#getName--}
```
public final String getName()
```


Lehdarın adını alır veya ayarlar. Azami uzunluk 70 karakterdir.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Lehdarın adını alır veya ayarlar. Azami uzunluk 70 karakterdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getBIC() {#getBIC--}
```
public final String getBIC()
```


Lehdarın BIC'sini (en fazla 11 karakter) alır veya ayarlar.

**Returns:**
java.lang.String
### setBIC(String value) {#setBIC-java.lang.String-}
```
public final void setBIC(String value)
```


Lehdarın BIC'sini (en fazla 11 karakter) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getIBAN() {#getIBAN--}
```
public final String getIBAN()
```


Lehdarın hesabını (IBAN) alır veya ayarlar. IBAN, en fazla 34 alfanümerik karakterden oluşur.

**Returns:**
java.lang.String
### setIBAN(String value) {#setIBAN-java.lang.String-}
```
public final void setIBAN(String value)
```


Lehdarın hesabını (IBAN) alır veya ayarlar. IBAN, en fazla 34 alfanümerik karakterden oluşur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getAmount() {#getAmount--}
```
public final double getAmount()
```


Tutarı alır veya ayarlar.

**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Tutarı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getCode() {#getCode--}
```
public final String getCode()
```


İş kodunu (en fazla 4 karakter) alır veya ayarlar.

**Returns:**
java.lang.String
### setCode(String value) {#setCode-java.lang.String-}
```
public final void setCode(String value)
```


İş kodunu (en fazla 4 karakter) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Ödeme referansını (azami 35 karakter) alır veya ayarlar. Bu alan ile Gönderim Bilgileri alanı birbirini dışlar.

**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Ödeme referansını (azami 35 karakter) alır veya ayarlar. Bu alan ile Gönderim Bilgileri alanı birbirini dışlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getRemittance() {#getRemittance--}
```
public final String getRemittance()
```


Gönderim bilgilerini (azami 140 karakter) alır veya ayarlar. Bu alan ile Ödeme Referansı alanı birbirini dışlar.

**Returns:**
java.lang.String
### setRemittance(String value) {#setRemittance-java.lang.String-}
```
public final void setRemittance(String value)
```


Gönderim bilgilerini (azami 140 karakter) alır veya ayarlar. Bu alan ile Ödeme Referansı alanı birbirini dışlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getInformation() {#getInformation--}
```
public final String getInformation()
```


İpucu bilgilerini alır veya ayarlar. En fazla 70 karakter.

**Returns:**
java.lang.String
### setInformation(String value) {#setInformation-java.lang.String-}
```
public final void setInformation(String value)
```


İpucu bilgilerini alır veya ayarlar. En fazla 70 karakter.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


EPC / SEPA QR-Kod sürüm uygulaması. Varsayılan olarak bu değer 002 olarak ayarlanır.

**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


EPC / SEPA QR-Kod sürüm uygulaması. Varsayılan olarak bu değer 002 olarak ayarlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final String getCharset()
```


EPC / SEPA QR-Kod karakter kümesi uygulaması. Varsayılan olarak bu değer 1 olarak ayarlanır.

**Returns:**
java.lang.String
### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


EPC / SEPA QR-Kod karakter kümesi uygulaması. Varsayılan olarak bu değer 1 olarak ayarlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getIdentification() {#getIdentification--}
```
public final String getIdentification()
```


EPC / SEPA QR-Kod tanımlaması. Varsayılan olarak bu değer SCT olarak ayarlanır.

**Returns:**
java.lang.String
### setIdentification(String value) {#setIdentification-java.lang.String-}
```
public final void setIdentification(String value)
```


EPC / SEPA QR-Kod tanımlaması. Varsayılan olarak bu değer SCT olarak ayarlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


EPC özelliklerini karşılaştırmak için Equals yöntemini geçersiz kılar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kaynak | java.lang.Object | Karşılaştırılacak EPC nesnesi. |

**Returns:**
boolean - Geçilen adres nesnesi aynı tipe sahipse ve tüm özellikleri bu örnek özelliklerine eşitse true döndürür.
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode metodunu geçersiz kılar.

**Returns:**
int - Email karma kodu
