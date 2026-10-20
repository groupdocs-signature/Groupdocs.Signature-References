---
title: "HIBCLICSecondaryAdditionalData"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code ikincil ve ek verileri depolamak için sınıf."
type: docs
weight: 13
url: /tr/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) ikincil ve ek verileri depolamak için sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | Default ctor() |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getExpiryDateFormat()](#getExpiryDateFormat--) | Son kullanma tarihi formatını belirler. |
|
|  | [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | Son kullanma tarihi formatını belirler. |
|
|  | [getExpiryDate()](#getExpiryDate--) | Son kullanma tarihini belirler. |
|
|  | [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | Son kullanma tarihini belirler. |
|
|  | [getLotNumber()](#getLotNumber--) | Lot veya parti numarasını belirler. |
|
|  | [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Lot veya parti numarasını belirler. |
|
|  | [getSerialNumber()](#getSerialNumber--) | Seri numarasını belirler. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Seri numarasını belirler. |
|
|  | [getDateOfManufacture()](#getDateOfManufacture--) | Üretim tarihini belirler. |
|
|  | [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | Üretim tarihini belirler. |
|
|  | [getQuantity()](#getQuantity--) | Miktarı belirler, 0 ile 500 arasında tam sayı olmalıdır. |
|
|  | [setQuantity(int value)](#setQuantity-int-) | Miktarı belirler, 0 ile 500 arasında tam sayı olmalıdır. |
|
|  | [getLinkCharacter()](#getLinkCharacter--) | Çıktı dizesindeki bağlantı karakterini tanımlar. |
|
|  | [setLinkCharacter(char value)](#setLinkCharacter-char-) | Çıktı dizesindeki bağlantı karakterini tanımlar. |
|
|  | [deepClone()](#deepClone--) | Bu nesnenin bir kopyasını alır. |
|
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


Default ctor()


### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


Son kullanma tarihi formatını belirler.


**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


Son kullanma tarihi formatını belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


Son kullanma tarihini tanımlar. ExpiryDateFormat None olarak ayarlanmamışsa kullanılacaktır.


**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


Son kullanma tarihini tanımlar. ExpiryDateFormat None olarak ayarlanmamışsa kullanılacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


Lot veya parti numarasını belirler.
Lot/batch numarası, en fazla 18 sembol uzunluğunda alfanümerik bir dize olmalıdır.


**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


Lot veya parti numarasını belirler.
Lot/batch numarası, en fazla 18 sembol uzunluğunda alfanümerik bir dize olmalıdır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Seri numarasını belirler.
Seri numarası, en fazla 18 sembol uzunluğunda alfanümerik bir dize olmalıdır.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Seri numarasını belirler.
Seri numarası, en fazla 18 sembol uzunluğunda alfanümerik bir dize olmalıdır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


Üretim tarihini belirler.
Üretim tarihi, bu alanı kullanmamak için DateTime.MinValue olarak ayarlanabilir.
Varsayılan değer: DateTime.MinValue


**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


Üretim tarihini belirler.
Üretim tarihi, bu alanı kullanmamak için DateTime.MinValue olarak ayarlanabilir.
Varsayılan değer: DateTime.MinValue


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


Miktarı belirler, 0 ile 500 arasında tam sayı olmalıdır.
Miktar, bu alanı kullanmamak için -1 olarak ayarlanabilir. Varsayılan değer: -1


**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


Miktarı belirler, 0 ile 500 arasında tam sayı olmalıdır.
Miktar, bu alanı kullanmamak için -1 olarak ayarlanabilir. Varsayılan değer: -1


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLinkCharacter() {#getLinkCharacter--}
```
public final char getLinkCharacter()
```


Çıktı dizesindeki bağlantı karakterini tanımlar.


**Returns:**
char
### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public final void setLinkCharacter(char value)
```


Çıktı dizesindeki bağlantı karakterini tanımlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | char |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Bu nesnenin bir kopyasını alır.


**Returns:**
java.lang.Object
