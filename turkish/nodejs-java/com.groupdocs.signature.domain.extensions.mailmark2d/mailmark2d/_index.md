---
title: "Mailmark2D"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Royal Mail 2D Mailmark içine gömülmüş metni kodlamak ve çözmek için sınıf."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

Royal Mail 2D Mailmark içine gömülmüş metni kodlamak ve çözmek için sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Mailmark2D()](#Mailmark2D--) | Varsayılan birincil ve ikincil veri değerleriyle Royal Mail Mailmark birleşik verisini oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getUPUCountryID()](#getUPUCountryID--) | UPU Ülke Kimliğini tanımlar.Maksimum uzunluk: 4 karakter. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | UPU Ülke Kimliğini tanımlar.Maksimum uzunluk: 4 karakter. |
| [getInformationTypeID()](#getInformationTypeID--) | Her ürün tipi için Royal Mail Mailmark barkod yükünü tanımlar. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Her ürün tipi için Royal Mail Mailmark barkod yükünü tanımlar. |
| [getVersionID()](#getVersionID--) | Her Bilgi Türü Kimliği için ilgili barkod sürümünü tanımlar. |
| [getClass_()](#getClass---) | Öğenin sınıfını tanımlar. |
| [setClass(String value)](#setClass-java.lang.String-) | Öğenin sınıfını tanımlar. |
| [getSupplyChainID()](#getSupplyChainID--) | Posta gönderiminde yer alan benzersiz müşteri grubunu tanımlar. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Posta gönderiminde yer alan benzersiz müşteri grubunu tanımlar. |
| [getItemID()](#getItemID--) | Tedarik Zinciri Kimliği içinde benzersiz öğeyi tanımlar. |
| [setItemID(int value)](#setItemID-int-) | Tedarik Zinciri Kimliği içinde benzersiz öğeyi tanımlar. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Teslimat Adresinin Posta Kodunu DPS ile içerir. İç bölgelerde Posta Kodu/DP aşağıdaki karakter sayısını içerir. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Teslimat Adresinin Posta Kodunu DPS ile içerir. İç bölgelerde Posta Kodu/DP aşağıdaki karakter sayısını içerir. |
| [getRTSFlag()](#getRTSFlag--) | İstenen Geri Gönderim hizmetinin seviyesini gösteren bayrak. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | İstenen Geri Gönderim hizmetinin seviyesini gösteren bayrak. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Geri Gönderim Posta Kodunu içerir ancak DPS yoktur. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Geri Gönderim Posta Kodunu içerir ancak DPS yoktur. |
| [getCustomerContent()](#getCustomerContent--) | Müşteri tarafından kullanılmak üzere isteğe bağlı alan. |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Müşteri tarafından kullanılmak üzere isteğe bağlı alan. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | DataMatrix barkodunun kodlama modunu. |
| [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | DataMatrix barkodunun kodlama modunu. |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark Türü, Data Matrix barkodunun boyutunu tanımlar. |
| [setDataMatrixType(int value)](#setDataMatrixType-int-) | 2D Mailmark Türü, Data Matrix barkodunun boyutunu tanımlar. |
| [deepClone()](#deepClone--) | Bu nesnenin bir kopyasını alır. |
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


Varsayılan birincil ve ikincil veri değerleriyle Royal Mail Mailmark birleşik verisini oluşturur.

### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


UPU Ülke Kimliğini tanımlar.Maksimum uzunluk: 4 karakter.

**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


UPU Ülke Kimliğini tanımlar.Maksimum uzunluk: 4 karakter.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


Her ürün tipi için Royal Mail Mailmark barkod yükünü tanımlar.

--------------------

Geçerli Değerler: "0" - Yerel Sıralı ve Sırasız "A" - Çevrimiçi Posta "B" - Faturalama "C" - Konsolidasyon

**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


Her ürün tipi için Royal Mail Mailmark barkod yükünü tanımlar.

--------------------

Geçerli Değerler: "0" - Yerel Sıralı ve Sırasız "A" - Çevrimiçi Posta "B" - Faturalama "C" - Konsolidasyon

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


Her Bilgi Türü Kimliği için ilgili barkod sürümünü tanımlar.

--------------------

Geçerli Değerler: "1" - şu anda yalnızca bu değer kullanılıyor (varsayılan) "0" ve "2" ile "9" ve "A" ile "Z" yedek, gelecekteki olası kullanım için ayrılmıştır.

**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


Öğenin sınıfını tanımlar.

--------------------

Geçerli Değerler: "1" - 1C (Perakende) "2" - 2C (Perakende) "3" - Ekonomi (Perakende) "5" - Ertelenmiş (Perakende) "8" - Premium (Ağ Erişimi) "9" - Standart (Ağ Erişimi)

**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


Öğenin sınıfını tanımlar.

--------------------

Geçerli Değerler: "1" - 1C (Perakende) "2" - 2C (Perakende) "3" - Ekonomi (Perakende) "5" - Ertelenmiş (Perakende) "8" - Premium (Ağ Erişimi) "9" - Standart (Ağ Erişimi)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


Posta gönderiminde yer alan benzersiz müşteri grubunu tanımlar. Maksimum değer: 9999999.

**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


Posta gönderiminde yer alan benzersiz müşteri grubunu tanımlar. Maksimum değer: 9999999.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


Tedarik Zinciri Kimliği içinde benzersiz öğeyi tanımlar. Her Mailmark barkodu, en az 90 gün boyunca benzersiz şekilde tanımlanabilmesi için bir kimlik taşımalıdır. Maksimum değer: 99999999.

**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


Tedarik Zinciri Kimliği içinde benzersiz öğeyi tanımlar. Her Mailmark barkodu, en az 90 gün boyunca benzersiz şekilde tanımlanabilmesi için bir kimlik taşımalıdır. Maksimum değer: 99999999.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


Teslimat Adresinin Posta Kodunu DPS ile içerir. İç bölgelerde Posta Kodu/DP aşağıdaki karakter sayılarını içerir. Bölge (1 veya 2 karakter) İlçe (1 veya 2 karakter) Sektör (1 karakter) Birim (2 karakter) DPS (2 karakter). Posta Kodu ve DPS, geçerli bir PAF® formatına uymalıdır. Maksimum uzunluk 9'dur.

**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


Teslimat Adresinin Posta Kodunu DPS ile içerir. İç bölgelerde Posta Kodu/DP aşağıdaki karakter sayılarını içerir. Bölge (1 veya 2 karakter) İlçe (1 veya 2 karakter) Sektör (1 karakter) Birim (2 karakter) DPS (2 karakter). Posta Kodu ve DPS, geçerli bir PAF® formatına uymalıdır. Maksimum uzunluk 9'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


İstenen Geri Gönderim hizmetinin seviyesini gösteren bayrak. Maksimum uzunluk 1'dir.

**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


İstenen Geri Gönderim hizmetinin seviyesini gösteren bayrak. Maksimum uzunluk 1'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


Geri Gönderim Posta Kodunu içerir ancak DPS yoktur. DPS'siz PC, bir PAF® formatına uymalıdır.

**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


Geri Gönderim Posta Kodunu içerir ancak DPS yoktur. DPS'siz PC, bir PAF® formatına uymalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


Müşteri tarafından kullanılmak üzere isteğe bağlı alan.

--------------------

Türüne göre maksimum uzunluk [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Tip 7: 6 karakter Tip 9: 45 karakter Tip 29: 25 karakter

**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


Müşteri tarafından kullanılmak üzere isteğe bağlı alan.

--------------------

Türüne göre maksimum uzunluk [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Tip 7: 6 karakter Tip 9: 45 karakter Tip 29: 25 karakter

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public final int getCustomerContentEncodeMode()
```


DataMatrix barkodunun kodlama modu. Varsayılan değer: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)

**Returns:**
int
### setCustomerContentEncodeMode(int value) {#setCustomerContentEncodeMode-int-}
```
public final void setCustomerContentEncodeMode(int value)
```


DataMatrix barkodunun kodlama modu. Varsayılan değer: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDataMatrixType() {#getDataMatrixType--}
```
public final int getDataMatrixType()
```


2D Mailmark Türü, Data Matrix barkodunun boyutunu tanımlar.

**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


2D Mailmark Türü, Data Matrix barkodunun boyutunu tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Bu nesnenin bir kopyasını alır.

**Returns:**
java.lang.Object
