---
title: "EPC"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Mewakili Kode Respon Cepat European Payments Council."
type: docs
weight: 14
url: /id/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/epc/
---
**Inheritance:**
java.lang.Object
```
public final class EPC
```

Mewakili Kode Respon Cepat European Payments Council.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [EPC()](#EPC--) | Membuat instance objek EPC baru. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getName()](#getName--) | Mendapatkan atau mengatur Nama Penerima. |
| [setName(String value)](#setName-java.lang.String-) | Mendapatkan atau mengatur Nama Penerima. |
| [getBIC()](#getBIC--) | Mendapatkan atau mengatur BIC Penerima dengan panjang hingga 11 karakter. |
| [setBIC(String value)](#setBIC-java.lang.String-) | Mendapatkan atau mengatur BIC Penerima dengan panjang hingga 11 karakter. |
| [getIBAN()](#getIBAN--) | Mendapatkan atau mengatur Rekening Penerima (IBAN). |
| [setIBAN(String value)](#setIBAN-java.lang.String-) | Mendapatkan atau mengatur Rekening Penerima (IBAN). |
| [getAmount()](#getAmount--) | Mendapatkan atau mengatur jumlah. |
| [setAmount(double value)](#setAmount-double-) | Mendapatkan atau mengatur jumlah. |
| [getCode()](#getCode--) | Mendapatkan atau mengatur Kode Bisnis hingga 4 karakter. |
| [setCode(String value)](#setCode-java.lang.String-) | Mendapatkan atau mengatur Kode Bisnis hingga 4 karakter. |
| [getReference()](#getReference--) | Mendapatkan atau mengatur Referensi Pembayaran (maksimum 35 karakter). |
| [setReference(String value)](#setReference-java.lang.String-) | Mendapatkan atau mengatur Referensi Pembayaran (maksimum 35 karakter). |
| [getRemittance()](#getRemittance--) | Mendapatkan atau mengatur Informasi Pengiriman (maksimum 140 karakter). |
| [setRemittance(String value)](#setRemittance-java.lang.String-) | Mendapatkan atau mengatur Informasi Pengiriman (maksimum 140 karakter). |
| [getInformation()](#getInformation--) | Mendapatkan atau mengatur informasi petunjuk. |
| [setInformation(String value)](#setInformation-java.lang.String-) | Mendapatkan atau mengatur informasi petunjuk. |
| [getVersion()](#getVersion--) | Implementasi versi EPC / SEPA QR-Code. |
| [setVersion(String value)](#setVersion-java.lang.String-) | Implementasi versi EPC / SEPA QR-Code. |
| [getCharset()](#getCharset--) | Implementasi set karakter EPC / SEPA QR-Code. |
| [setCharset(String value)](#setCharset-java.lang.String-) | Implementasi set karakter EPC / SEPA QR-Code. |
| [getIdentification()](#getIdentification--) | Identifikasi EPC / SEPA QR-Code. |
| [setIdentification(String value)](#setIdentification-java.lang.String-) | Identifikasi EPC / SEPA QR-Code. |
| [equals(Object source)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti EPC |
| [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
### EPC() {#EPC--}
```
public EPC()
```


Membuat instance objek EPC baru.

### getName() {#getName--}
```
public final String getName()
```


Mendapatkan atau mengatur Nama Penerima. Panjang maksimum adalah 70 karakter.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Mendapatkan atau mengatur Nama Penerima. Panjang maksimum adalah 70 karakter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getBIC() {#getBIC--}
```
public final String getBIC()
```


Mendapatkan atau mengatur BIC Penerima dengan panjang hingga 11 karakter.

**Returns:**
java.lang.String
### setBIC(String value) {#setBIC-java.lang.String-}
```
public final void setBIC(String value)
```


Mendapatkan atau mengatur BIC Penerima dengan panjang hingga 11 karakter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getIBAN() {#getIBAN--}
```
public final String getIBAN()
```


Mendapatkan atau mengatur Rekening Penerima (IBAN). IBAN terdiri dari hingga 34 karakter alfanumerik.

**Returns:**
java.lang.String
### setIBAN(String value) {#setIBAN-java.lang.String-}
```
public final void setIBAN(String value)
```


Mendapatkan atau mengatur Rekening Penerima (IBAN). IBAN terdiri dari hingga 34 karakter alfanumerik.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getAmount() {#getAmount--}
```
public final double getAmount()
```


Mendapatkan atau mengatur jumlah.

**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Mendapatkan atau mengatur jumlah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### getCode() {#getCode--}
```
public final String getCode()
```


Mendapatkan atau mengatur Kode Bisnis hingga 4 karakter.

**Returns:**
java.lang.String
### setCode(String value) {#setCode-java.lang.String-}
```
public final void setCode(String value)
```


Mendapatkan atau mengatur Kode Bisnis hingga 4 karakter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Mendapatkan atau mengatur Referensi Pembayaran (maksimum 35 karakter). Field ini dan field Informasi Pengiriman saling eksklusif.

**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Mendapatkan atau mengatur Referensi Pembayaran (maksimum 35 karakter). Field ini dan field Informasi Pengiriman saling eksklusif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getRemittance() {#getRemittance--}
```
public final String getRemittance()
```


Mendapatkan atau mengatur Informasi Pengiriman (maksimum 140 karakter). Field ini dan field Referensi Pembayaran saling eksklusif.

**Returns:**
java.lang.String
### setRemittance(String value) {#setRemittance-java.lang.String-}
```
public final void setRemittance(String value)
```


Mendapatkan atau mengatur Informasi Pengiriman (maksimum 140 karakter). Field ini dan field Referensi Pembayaran saling eksklusif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getInformation() {#getInformation--}
```
public final String getInformation()
```


Mendapatkan atau mengatur informasi petunjuk. Maksimum 70 karakter.

**Returns:**
java.lang.String
### setInformation(String value) {#setInformation-java.lang.String-}
```
public final void setInformation(String value)
```


Mendapatkan atau mengatur informasi petunjuk. Maksimum 70 karakter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


Implementasi versi EPC / SEPA QR-Code. Secara default nilai ini diatur ke 002.

**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


Implementasi versi EPC / SEPA QR-Code. Secara default nilai ini diatur ke 002.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final String getCharset()
```


Implementasi set karakter EPC / SEPA QR-Code. Secara default nilai ini diatur ke 1

**Returns:**
java.lang.String
### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


Implementasi set karakter EPC / SEPA QR-Code. Secara default nilai ini diatur ke 1

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getIdentification() {#getIdentification--}
```
public final String getIdentification()
```


Identifikasi EPC / SEPA QR-Code. Secara default nilai ini diatur ke SCT

**Returns:**
java.lang.String
### setIdentification(String value) {#setIdentification-java.lang.String-}
```
public final void setIdentification(String value)
```


Identifikasi EPC / SEPA QR-Code. Secara default nilai ini diatur ke SCT

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


Menimpa metode Equals untuk membandingkan properti EPC

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sumber | java.lang.Object | Objek EPC untuk dibandingkan. |

**Returns:**
boolean - Mengembalikan true jika objek alamat yang diberikan memiliki tipe yang sama dan semua propertinya sama dengan properti instance ini.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Menimpa metode GetHashCode

**Returns:**
int - Kode hash Email
