---
title: "HIBCLICSecondaryAdditionalData"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code ikincil ve ek verileri depolamak için sınıf."
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

HIBC (Sağlık Endüstrisi Barkod Konseyi) LIC (Lisanslı Tanımlama Kodu) ikincil ve ek verileri depolamak için sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | Varsayılan ctor() |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | Son kullanım tarihi formatını belirler. |
| [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | Son kullanım tarihi formatını belirler. |
| [getExpiryDate()](#getExpiryDate--) | Son kullanım tarihini belirler. |
| [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | Son kullanım tarihini belirler. |
| [getLotNumber()](#getLotNumber--) | Lot veya parti numarasını tanımlar. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Lot veya parti numarasını tanımlar. |
| [getSerialNumber()](#getSerialNumber--) | Seri numarasını tanımlar. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Seri numarasını tanımlar. |
| [getDateOfManufacture()](#getDateOfManufacture--) | Üretim tarihini tanımlar. |
| [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | Üretim tarihini tanımlar. |
| [getQuantity()](#getQuantity--) | Miktarı tanımlar, 0 ile 500 arasında tam sayı olmalıdır. |
| [setQuantity(int value)](#setQuantity-int-) | Miktarı tanımlar, 0 ile 500 arasında tam sayı olmalıdır. |
| [getLinkCharacter()](#getLinkCharacter--) | Çıktı dizesindeki bağlantı karakterini tanımlar. |
| [setLinkCharacter(char value)](#setLinkCharacter-char-) | Çıktı dizesindeki bağlantı karakterini tanımlar. |
| [deepClone()](#deepClone--) | Bu nesnenin bir kopyasını alır. |
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


Varsayılan ctor()

### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


Son kullanım tarihi formatını belirler.

**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


Son kullanım tarihi formatını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


Son kullanım tarihini tanımlar. ExpiryDateFormat 'None' olarak ayarlanmamışsa kullanılacaktır.

**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


Son kullanım tarihini tanımlar. ExpiryDateFormat 'None' olarak ayarlanmamışsa kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


Lot veya parti numarasını tanımlar. Lot/parti numarası en fazla 18 karakter uzunluğunda alfanümerik bir dize olmalıdır.

**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


Lot veya parti numarasını tanımlar. Lot/parti numarası en fazla 18 karakter uzunluğunda alfanümerik bir dize olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Seri numarasını tanımlar. Seri numarası en fazla 18 karakter uzunluğunda alfanümerik bir dize olmalıdır.

**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Seri numarasını tanımlar. Seri numarası en fazla 18 karakter uzunluğunda alfanümerik bir dize olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


Üretim tarihini tanımlar. Bu alanı kullanmamak için üretim tarihi DateTime.MinValue olarak ayarlanabilir. Varsayılan değer: DateTime.MinValue

**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


Üretim tarihini tanımlar. Bu alanı kullanmamak için üretim tarihi DateTime.MinValue olarak ayarlanabilir. Varsayılan değer: DateTime.MinValue

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


Miktarı tanımlar, 0 ile 500 arasında tam sayı olmalıdır. Bu alanı kullanmamak için miktar -1 olarak ayarlanabilir. Varsayılan değer: -1

**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


Miktarı tanımlar, 0 ile 500 arasında tam sayı olmalıdır. Bu alanı kullanmamak için miktar -1 olarak ayarlanabilir. Varsayılan değer: -1

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
