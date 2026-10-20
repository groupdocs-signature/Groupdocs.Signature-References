---
title: "KriptoParaTransferi"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Kripto para transfer alıcısını veya QR-Kod için transferi temsil eder."
type: docs
weight: 11
url: /tr/java/com.groupdocs.signature.domain.extensions.serialization/cryptocurrencytransfer/
---
**Inheritance:**
java.lang.Object
```
public class CryptoCurrencyTransfer
```

QR-Kod için kripto para transferini (alıcı veya gönderim) temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CryptoCurrencyTransfer()](#CryptoCurrencyTransfer--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getType()](#getType--) | Desteklenen kripto para türlerinden birini alır veya ayarlar. |
|
|  | [setType(int value)](#setType-int-) | Desteklenen kripto para türlerinden birini alır veya ayarlar. |
|
|  | [getAmount()](#getAmount--) | Transfer miktarını alır veya ayarlar. |
|
|  | [setAmount(BigDecimal value)](#setAmount-java.math.BigDecimal-) | Transfer miktarını alır veya ayarlar. |
|
|  | [getAddress()](#getAddress--) | Kripto para genel adresini alır veya ayarlar. |
|
|  | [setAddress(String value)](#setAddress-java.lang.String-) | Kripto para genel adresini alır veya ayarlar. |
|
|  | [getMessage()](#getMessage--) | İsteğe bağlı transfer mesajını alır veya ayarlar. |
|
|  | [setMessage(String value)](#setMessage-java.lang.String-) | İsteğe bağlı transfer mesajını alır veya ayarlar. |
|
|  | [getCustomType()](#getCustomType--) | İsteğe bağlı transfer mesajını alır veya ayarlar. |
|
|  | [setCustomType(String value)](#setCustomType-java.lang.String-) | İsteğe bağlı transfer mesajını alır veya ayarlar. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Kripto para transfer özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
|
|  | [hashCode()](#hashCode--) | GetHashCode yöntemini geçersiz kılar |
|
### CryptoCurrencyTransfer() {#CryptoCurrencyTransfer--}
```
public CryptoCurrencyTransfer()
```


### getType() {#getType--}
```
public final int getType()
```


Desteklenen kripto para türlerinden birini alır veya ayarlar.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Desteklenen kripto para türlerinden birini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getAmount() {#getAmount--}
```
public final BigDecimal getAmount()
```


Transfer miktarını alır veya ayarlar.


**Returns:**
java.math.BigDecimal
### setAmount(BigDecimal value) {#setAmount-java.math.BigDecimal-}
```
public final void setAmount(BigDecimal value)
```


Transfer miktarını alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.math.BigDecimal |  |

### getAddress() {#getAddress--}
```
public final String getAddress()
```


Kripto para genel adresini alır veya ayarlar.


**Returns:**
java.lang.String
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


Kripto para genel adresini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


İsteğe bağlı transfer mesajını alır veya ayarlar.


**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


İsteğe bağlı transfer mesajını alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getCustomType() {#getCustomType--}
```
public final String getCustomType()
```


İsteğe bağlı transfer mesajını alır veya ayarlar.


**Returns:**
java.lang.String
### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public final void setCustomType(String value)
```


İsteğe bağlı transfer mesajını alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Kripto para transfer özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Karşılaştırılacak kripto para transfer nesnesi. |
|

**Returns:**
boolean - Geçilen kripto para transfer nesnesi aynı türe sahipse ve tüm özellikleri bu örnek özelliklerine eşitse true döndürür.

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode yöntemini geçersiz kılar


**Returns:**
int - Kripto para transferi karma kodu

