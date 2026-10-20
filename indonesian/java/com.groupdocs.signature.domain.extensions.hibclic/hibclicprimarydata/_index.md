---
title: "HIBCLICPrimaryData"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Kelas untuk menyimpan data utama HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 12
url: /id/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

Kelas untuk menyimpan data primer HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | Konstruktor default() |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Mengidentifikasi tanggal kode identifikasi labeler. |
|
|  | [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Mengidentifikasi tanggal kode identifikasi labeler. |
|
|  | [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Mengidentifikasi produk atau nomor katalog. |
|
|  | [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Mengidentifikasi produk atau nomor katalog. |
|
|  | [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Mengidentifikasi ID satuan ukuran. |
|
|  | [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Mengidentifikasi ID satuan ukuran. |
|
|  | [deepClone()](#deepClone--) | Mendapatkan salinan objek ini. |
|
| [getCodetext()](#getCodetext--) |  |
### HIBCLICPrimaryData() {#HIBCLICPrimaryData--}
```
public HIBCLICPrimaryData()
```


Konstruktor default()


### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public final String getLabelerIdentificationCode()
```


Mengidentifikasi tanggal kode identifikasi pelabel. Kode identifikasi pelabel harus berupa string alfanumerik 4 simbol, dengan karakter pertama selalu berupa huruf.
menjadi string alfanumerik 4 simbol, dengan karakter pertama selalu berupa huruf.


**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


Mengidentifikasi tanggal kode identifikasi pelabel. Kode identifikasi pelabel harus berupa string alfanumerik 4 simbol, dengan karakter pertama selalu berupa huruf.
menjadi string alfanumerik 4 simbol, dengan karakter pertama selalu berupa huruf.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


Mengidentifikasi produk atau nomor katalog. Produk atau nomor katalog harus alfanumerik
string dengan panjang hingga 18 simbol.


**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


Mengidentifikasi produk atau nomor katalog. Produk atau nomor katalog harus alfanumerik
string dengan panjang hingga 18 simbol.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


Mengidentifikasi ID satuan ukuran. ID satuan ukuran harus berupa nilai integer dari 0 hingga 9.


**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


Mengidentifikasi ID satuan ukuran. ID satuan ukuran harus berupa nilai integer dari 0 hingga 9.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Mendapatkan salinan objek ini.


**Returns:**
java.lang.Object
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
