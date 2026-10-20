---
title: "HIBCLICPrimaryData"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code birincil verilerini depolamak için sınıf."
type: docs
weight: 12
url: /tr/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

HIBC (Sağlık Endüstrisi Barkod Konseyi) LIC (Lisanslı Tanımlama Kodu) birincil verilerini depolamak için sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | Default ctor() |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Etiketleyici kimlik kodunun tarihini belirler. |
|
|  | [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Etiketleyici kimlik kodunun tarihini belirler. |
|
|  | [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Ürün veya katalog numarasını belirler. |
|
|  | [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Ürün veya katalog numarasını belirler. |
|
|  | [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Ölçü birimi kimliğini belirler. |
|
|  | [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Ölçü birimi kimliğini belirler. |
|
|  | [deepClone()](#deepClone--) | Bu nesnenin bir kopyasını alır. |
|
| [getCodetext()](#getCodetext--) |  |
### HIBCLICPrimaryData() {#HIBCLICPrimaryData--}
```
public HIBCLICPrimaryData()
```


Default ctor()


### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public final String getLabelerIdentificationCode()
```


Etiketleyici kimlik kodunun tarihini belirler. Etiketleyici kimlik kodu olmalıdır
4 sembollük alfanümerik bir dize olmalı, ilk karakter her zaman alfabetik olmalıdır.


**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


Etiketleyici kimlik kodunun tarihini belirler. Etiketleyici kimlik kodu olmalıdır
4 sembollük alfanümerik bir dize olmalı, ilk karakter her zaman alfabetik olmalıdır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


Ürün veya katalog numarasını belirler. Ürün veya katalog numarası alfanümerik olmalıdır
18 sembole kadar uzunlukta dize.


**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


Ürün veya katalog numarasını belirler. Ürün veya katalog numarası alfanümerik olmalıdır
18 sembole kadar uzunlukta dize.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


Ölçü birimi kimliğini belirler. Ölçü birimi kimliği 0 ile 9 arasında tam sayı olmalıdır.


**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


Ölçü birimi kimliğini belirler. Ölçü birimi kimliği 0 ile 9 arasında tam sayı olmalıdır.


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
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
