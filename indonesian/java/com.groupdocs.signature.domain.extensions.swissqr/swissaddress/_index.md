---
title: "SwissAddress"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mewakili alamat kreditur atau debitur."
type: docs
weight: 10
url: /id/java/com.groupdocs.signature.domain.extensions.swissqr/swissaddress/
---
**Inheritance:**
java.lang.Object
```
public class SwissAddress
```

Mewakili alamat kreditur atau debitur.
Anda dapat mengatur jalan, nomor rumah, kode pos, dan kota (tipe alamat terstruktur)
atau baris alamat 1 dan 2 (tipe elemen alamat gabungan).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SwissAddress()](#SwissAddress--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getName()](#getName--) | Mendapatkan atau mengatur nama, baik nama depan dan belakang orang alami atau |
nama perusahaan dari orang hukum.
|
|  | [setName(String value)](#setName-java.lang.String-) | Mendapatkan atau mengatur nama, baik nama depan dan belakang orang alami atau |
nama perusahaan dari orang hukum.
|
|  | [getAddressLine1()](#getAddressLine1--) | Mendapatkan atau mengatur baris alamat 1. |
|
|  | [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Mendapatkan atau mengatur baris alamat 1. |
|
|  | [getAddressLine2()](#getAddressLine2--) | Mendapatkan atau mengatur baris alamat 2. |
|
|  | [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Mendapatkan atau mengatur baris alamat 2. |
|
|  | [getStreet()](#getStreet--) | Mendapatkan atau mengatur jalan. |
|
|  | [setStreet(String value)](#setStreet-java.lang.String-) | Mendapatkan atau mengatur jalan. |
|
|  | [getHouseNo()](#getHouseNo--) | Mendapatkan atau mengatur nomor rumah. |
|
|  | [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Mendapatkan atau mengatur nomor rumah. |
|
|  | [getPostalCode()](#getPostalCode--) | Mendapatkan atau mengatur kode pos. |
|
|  | [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Mendapatkan atau mengatur kode pos. |
|
|  | [getTown()](#getTown--) | Mendapatkan atau mengatur kota atau kota. |
|
|  | [setTown(String value)](#setTown-java.lang.String-) | Mendapatkan atau mengatur kota atau kota. |
|
|  | [getCountryCode()](#getCountryCode--) | Mendapatkan atau mengatur kode negara ISO dua huruf. |
|
|  | [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Mendapatkan atau mengatur kode negara ISO dua huruf. |
|
### SwissAddress() {#SwissAddress--}
```
public SwissAddress()
```


### getName() {#getName--}
```
public final String getName()
```


Mendapatkan atau mengatur nama, baik nama depan dan belakang orang alami atau
nama perusahaan dari orang hukum.
Nilai: Nama.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Mendapatkan atau mengatur nama, baik nama depan dan belakang orang alami atau
nama perusahaan dari orang hukum.
Nilai: Nama.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getAddressLine1() {#getAddressLine1--}
```
public final String getAddressLine1()
```


Mendapatkan atau mengatur baris alamat 1.
Baris alamat 1 berisi nama jalan, nomor rumah atau kotak pos.
Bidang ini hanya digunakan untuk alamat elemen gabungan dan bersifat opsional.
Nilai: Baris alamat 1.


**Returns:**
java.lang.String
### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public final void setAddressLine1(String value)
```


Mendapatkan atau mengatur baris alamat 1.
Baris alamat 1 berisi nama jalan, nomor rumah atau kotak pos.
Bidang ini hanya digunakan untuk alamat elemen gabungan dan bersifat opsional.
Nilai: Baris alamat 1.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getAddressLine2() {#getAddressLine2--}
```
public final String getAddressLine2()
```


Mendapatkan atau mengatur baris alamat 2.
Baris alamat 2 berisi kode pos dan kota.
Bidang ini hanya digunakan untuk alamat elemen gabungan. Untuk tipe ini, bersifat wajib.
Nilai: Baris alamat 2.


**Returns:**
java.lang.String
### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public final void setAddressLine2(String value)
```


Mendapatkan atau mengatur baris alamat 2.
Baris alamat 2 berisi kode pos dan kota.
Bidang ini hanya digunakan untuk alamat elemen gabungan. Untuk tipe ini, bersifat wajib.
Nilai: Baris alamat 2.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getStreet() {#getStreet--}
```
public final String getStreet()
```


Mendapatkan atau mengatur jalan.
Jalan harus ditentukan tanpa nomor rumah.
Bidang ini hanya digunakan untuk alamat terstruktur dan bersifat opsional.
Nilai: Jalan.


**Returns:**
java.lang.String
### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


Mendapatkan atau mengatur jalan.
Jalan harus ditentukan tanpa nomor rumah.
Bidang ini hanya digunakan untuk alamat terstruktur dan bersifat opsional.
Nilai: Jalan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getHouseNo() {#getHouseNo--}
```
public final String getHouseNo()
```


Mendapatkan atau mengatur nomor rumah.
Bidang ini hanya digunakan untuk alamat terstruktur dan bersifat opsional.
Nilai: Nomor rumah.


**Returns:**
java.lang.String
### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public final void setHouseNo(String value)
```


Mendapatkan atau mengatur nomor rumah.
Bidang ini hanya digunakan untuk alamat terstruktur dan bersifat opsional.
Nilai: Nomor rumah.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


Mendapatkan atau mengatur kode pos.
Bidang ini hanya digunakan untuk alamat terstruktur. Untuk tipe ini, bersifat wajib.
Nilai: Kode pos.


**Returns:**
java.lang.String
### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Mendapatkan atau mengatur kode pos.
Bidang ini hanya digunakan untuk alamat terstruktur. Untuk tipe ini, bersifat wajib.
Nilai: Kode pos.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getTown() {#getTown--}
```
public final String getTown()
```


Mendapatkan atau mengatur kota atau kota.
Bidang ini hanya digunakan untuk alamat terstruktur. Untuk tipe ini, bersifat wajib.
Nilai: Kota atau kota.


**Returns:**
java.lang.String
### setTown(String value) {#setTown-java.lang.String-}
```
public final void setTown(String value)
```


Mendapatkan atau mengatur kota atau kota.
Bidang ini hanya digunakan untuk alamat terstruktur. Untuk tipe ini, bersifat wajib.
Nilai: Kota atau kota.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


Mendapatkan atau mengatur kode negara ISO dua huruf.
Kode negara bersifat wajib kecuali seluruh alamat berisi nilai null atau kosong.
Nilai: Kode negara ISO.


**Returns:**
java.lang.String
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


Mendapatkan atau mengatur kode negara ISO dua huruf.
Kode negara bersifat wajib kecuali seluruh alamat berisi nilai null atau kosong.
Nilai: Kode negara ISO.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

