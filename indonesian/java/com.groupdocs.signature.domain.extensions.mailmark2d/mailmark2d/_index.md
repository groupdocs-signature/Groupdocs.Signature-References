---
title: "Mailmark2D"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam Royal Mail 2D Mailmark."
type: docs
weight: 10
url: /id/java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam Royal Mail 2D Mailmark.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Mailmark2D()](#Mailmark2D--) | Membuat data gabungan Royal Mail Mailmark dengan nilai data primer dan sekunder default. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getUPUCountryID()](#getUPUCountryID--) | Mengidentifikasi ID Negara UPU. Panjang maksimum: 4 karakter. |
|
|  | [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Mengidentifikasi ID Negara UPU. Panjang maksimum: 4 karakter. |
|
|  | [getInformationTypeID()](#getInformationTypeID--) | Mengidentifikasi muatan kode batang Royal Mail Mailmark untuk setiap tipe produk. |
|
|  | [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Mengidentifikasi muatan kode batang Royal Mail Mailmark untuk setiap tipe produk. |
|
|  | [getVersionID()](#getVersionID--) | Mengidentifikasi versi kode batang yang relevan untuk setiap ID Tipe Informasi. |
|
|  | [getClass_()](#getClass---) | Mengidentifikasi kelas item. |
|
|  | [setClass(String value)](#setClass-java.lang.String-) | Mengidentifikasi kelas item. |
|
|  | [getSupplyChainID()](#getSupplyChainID--) | Mengidentifikasi grup unik pelanggan yang terlibat dalam pengiriman surat. |
|
|  | [setSupplyChainID(int value)](#setSupplyChainID-int-) | Mengidentifikasi grup unik pelanggan yang terlibat dalam pengiriman surat. |
|
|  | [getItemID()](#getItemID--) | Mengidentifikasi item unik dalam ID Rantai Pasokan. |
|
|  | [setItemID(int value)](#setItemID-int-) | Mengidentifikasi item unik dalam ID Rantai Pasokan. |
|
|  | [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Berisi Kode Pos dari Alamat Pengiriman dengan DPS |
Jika di daratan, Kode Pos/DP berisi jumlah karakter berikut.
|
|  | [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Berisi Kode Pos dari Alamat Pengiriman dengan DPS |
Jika di daratan, Kode Pos/DP berisi jumlah karakter berikut.
|
|  | [getRTSFlag()](#getRTSFlag--) | Bendera yang menunjukkan tingkat layanan Return to Sender yang diminta. |
|
|  | [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Bendera yang menunjukkan tingkat layanan Return to Sender yang diminta. |
|
|  | [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Berisi Kode Pos Return to Sender tetapi tidak ada DPS. |
|
|  | [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Berisi Kode Pos Return to Sender tetapi tidak ada DPS. |
|
|  | [getCustomerContent()](#getCustomerContent--) | Ruang opsional untuk penggunaan oleh pelanggan. |
|
|  | [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Ruang opsional untuk penggunaan oleh pelanggan. |
|
|  | [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Mode enkode barcode DataMatrix. |
|
|  | [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | Mode enkode barcode DataMatrix. |
|
|  | [getDataMatrixType()](#getDataMatrixType--) | Tipe Mailmark 2D menentukan ukuran barcode Data Matrix. |
|
|  | [setDataMatrixType(int value)](#setDataMatrixType-int-) | Tipe Mailmark 2D menentukan ukuran barcode Data Matrix. |
|
|  | [deepClone()](#deepClone--) | Mendapatkan salinan objek ini. |
|
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


Membuat data gabungan Royal Mail Mailmark dengan nilai data primer dan sekunder default.


### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


Mengidentifikasi ID Negara UPU. Panjang maksimum: 4 karakter.


**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


Mengidentifikasi ID Negara UPU. Panjang maksimum: 4 karakter.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


Mengidentifikasi muatan kode batang Royal Mail Mailmark untuk setiap tipe produk.

<br />

*** ** * ** ***

Nilai Valid: "0" - Domestik Terurut dan Tidak Terurut "A" - Pos Daring "B" - Franking "C" - Konsolidasi

<br />



**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


Mengidentifikasi muatan kode batang Royal Mail Mailmark untuk setiap tipe produk.

<br />

*** ** * ** ***

Nilai Valid: "0" - Domestik Terurut dan Tidak Terurut "A" - Pos Daring "B" - Franking "C" - Konsolidasi

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


Mengidentifikasi versi kode batang yang relevan untuk setiap ID Tipe Informasi.

<br />

*** ** * ** ***

Nilai Valid: "1" - saat ini hanya nilai ini yang digunakan (default) "0" dan "2" hingga "9" serta "A" hingga "Z" cadangan disiapkan untuk penggunaan potensial di masa depan.

<br />



**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


Mengidentifikasi kelas item.

<br />

*** ** * ** ***

Nilai Valid: "1" - 1C (Ritel) "2" - 2C (Ritel) "3" - Ekonomi (Ritel) "5" - Tertunda (Ritel) "8" - Premium (Akses Jaringan) "9" - Standar (Akses Jaringan)

<br />



**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


Mengidentifikasi kelas item.

<br />

*** ** * ** ***

Nilai Valid: "1" - 1C (Ritel) "2" - 2C (Ritel) "3" - Ekonomi (Ritel) "5" - Tertunda (Ritel) "8" - Premium (Akses Jaringan) "9" - Standar (Akses Jaringan)

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


Mengidentifikasi grup unik pelanggan yang terlibat dalam pengiriman surat.
Nilai maksimum: 9999999.


**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


Mengidentifikasi grup unik pelanggan yang terlibat dalam pengiriman surat.
Nilai maksimum: 9999999.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


Mengidentifikasi item unik dalam ID Rantai Pasokan.
Setiap barcode Mailmark harus membawa ID sehingga dapat diidentifikasi secara unik setidaknya selama 90 hari.
Nilai maksimum: 99999999.


**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


Mengidentifikasi item unik dalam ID Rantai Pasokan.
Setiap barcode Mailmark harus membawa ID sehingga dapat diidentifikasi secara unik setidaknya selama 90 hari.
Nilai maksimum: 99999999.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


Berisi Kode Pos dari Alamat Pengiriman dengan DPS
Jika di daratan, Kode Pos/DP berisi jumlah karakter berikut.
Wilayah (1 atau 2 karakter)
Distrik(1 atau 2 karakter)
Sektor(1 karakter)
Unit(2 karakter)
DPS (2 karakter).
Kode Pos dan DPS harus mematuhi format PAF® yang valid. Panjang maksimum adalah 9.


**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


Berisi Kode Pos dari Alamat Pengiriman dengan DPS
Jika di daratan, Kode Pos/DP berisi jumlah karakter berikut.
Wilayah (1 atau 2 karakter)
Distrik(1 atau 2 karakter)
Sektor(1 karakter)
Unit(2 karakter)
DPS (2 karakter).
Kode Pos dan DPS harus mematuhi format PAF® yang valid. Panjang maksimum adalah 9.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


Bendera yang menunjukkan tingkat layanan Return to Sender yang diminta. Panjang maksimum adalah 1


**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


Bendera yang menunjukkan tingkat layanan Return to Sender yang diminta. Panjang maksimum adalah 1


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


Berisi Kode Pos Return to Sender tetapi tidak ada DPS.
PC (tanpa DPS) harus mematuhi format PAF®.


**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


Berisi Kode Pos Return to Sender tetapi tidak ada DPS.
PC (tanpa DPS) harus mematuhi format PAF®.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


Ruang opsional untuk penggunaan oleh pelanggan.

<br />

*** ** * ** ***

Panjang maksimum berdasarkan Tipe [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Tipe 7: 6 karakter Tipe 9: 45 karakter Tipe 29: 25 karakter

<br />



**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


Ruang opsional untuk penggunaan oleh pelanggan.

<br />

*** ** * ** ***

Panjang maksimum berdasarkan Tipe [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Tipe 7: 6 karakter Tipe 9: 45 karakter Tipe 29: 25 karakter

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public final int getCustomerContentEncodeMode()
```


Mode enkode barcode DataMatrix. Nilai default: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Returns:**
int
### setCustomerContentEncodeMode(int value) {#setCustomerContentEncodeMode-int-}
```
public final void setCustomerContentEncodeMode(int value)
```


Mode enkode barcode DataMatrix. Nilai default: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getDataMatrixType() {#getDataMatrixType--}
```
public final int getDataMatrixType()
```


Tipe Mailmark 2D menentukan ukuran barcode Data Matrix.


**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


Tipe Mailmark 2D menentukan ukuran barcode Data Matrix.


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
