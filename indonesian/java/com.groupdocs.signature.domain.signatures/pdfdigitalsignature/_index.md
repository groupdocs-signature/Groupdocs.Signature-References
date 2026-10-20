---
title: "PdfDigitalSignature"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Berisi properti Tanda Tangan Digital PDF."
type: docs
weight: 15
url: /id/java/com.groupdocs.signature.domain.signatures/pdfdigitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
```
public class PdfDigitalSignature extends DigitalSignature
```

Berisi properti Tanda Tangan Digital PDF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PdfDigitalSignature()](#PdfDigitalSignature--) | Inisialisasi Pdf Digital Signature tanpa sertifikat. |
|
|  | [PdfDigitalSignature(KeyStore certificate)](#PdfDigitalSignature-java.security.KeyStore-) | Buat Pdf Digital signature dengan sertifikat yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getContactInfo()](#getContactInfo--) | Informasi yang diberikan oleh penandatangan untuk memungkinkan penerima menghubungi penandatangan |
untuk memverifikasi tanda tangan, mis.
|
|  | [setContactInfo(String value)](#setContactInfo-java.lang.String-) | Informasi yang diberikan oleh penandatangan untuk memungkinkan penerima menghubungi penandatangan |
untuk memverifikasi tanda tangan, mis.
|
|  | [getLocation()](#getLocation--) | Nama host CPU atau lokasi fisik penandatanganan. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Nama host CPU atau lokasi fisik penandatanganan. |
|
|  | [getReason()](#getReason--) | Alasan penandatanganan, seperti (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Alasan penandatanganan, seperti (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
|
|  | [getType()](#getType--) | Tipe Pdf digital signature. |
|
|  | [setType(int value)](#setType-int-) | Tipe Pdf digital signature. |
|
|  | [getTimeStamp()](#getTimeStamp--) | Stempel waktu untuk Pdf digital signature. |
|
|  | [setTimeStamp(TimeStamp value)](#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) | Stempel waktu untuk Pdf digital signature. |
|
|  | [getShowProperties()](#getShowProperties--) | Paksa untuk menampilkan/menyembunyikan properti tanda tangan. |
|
|  | [setShowProperties(boolean value)](#setShowProperties-boolean-) | Paksa untuk menampilkan/menyembunyikan properti tanda tangan. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
|
|  | [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
|
|  | [deepClone()](#deepClone--) | Klon instance Barcode Signature. |
|
### PdfDigitalSignature() {#PdfDigitalSignature--}
```
public PdfDigitalSignature()
```


Inisialisasi Pdf Digital Signature tanpa sertifikat.


### PdfDigitalSignature(KeyStore certificate) {#PdfDigitalSignature-java.security.KeyStore-}
```
public PdfDigitalSignature(KeyStore certificate)
```


Buat Pdf Digital signature dengan sertifikat yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | sertifikat | java.security.KeyStore | Sertifikat X509. |
|

### getContactInfo() {#getContactInfo--}
```
public final String getContactInfo()
```


Informasi yang diberikan oleh penandatangan untuk memungkinkan penerima menghubungi penandatangan
untuk memverifikasi tanda tangan, mis. nomor telepon.


**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public final void setContactInfo(String value)
```


Informasi yang diberikan oleh penandatangan untuk memungkinkan penerima menghubungi penandatangan
untuk memverifikasi tanda tangan, mis. nomor telepon.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Nama host CPU atau lokasi fisik penandatanganan.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Nama host CPU atau lokasi fisik penandatanganan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Alasan penandatanganan, seperti (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Alasan penandatanganan, seperti (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Tipe Pdf digital signature.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Tipe Pdf digital signature.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getTimeStamp() {#getTimeStamp--}
```
public final TimeStamp getTimeStamp()
```


Stempel waktu untuk Pdf digital signature.
Nilai default adalah null.


**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### setTimeStamp(TimeStamp value) {#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public final void setTimeStamp(TimeStamp value)
```


Stempel waktu untuk Pdf digital signature.
Nilai default adalah null.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### getShowProperties() {#getShowProperties--}
```
public final boolean getShowProperties()
```


Paksa untuk menampilkan/menyembunyikan properti tanda tangan. Jika ShowProperties bernilai true tanda tangan
field memiliki format penampilan yang telah ditentukan
Ditandatangani secara digital oleh {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} Tanggal: {Date} Alasan: {
Alasan
(#getReason.getReason/#setReason(String).setReason(String))}
Lokasi: {
Location
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties bernilai true secara default.


**Returns:**
boolean
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public final void setShowProperties(boolean value)
```


Paksa untuk menampilkan/menyembunyikan properti tanda tangan. Jika ShowProperties bernilai true tanda tangan
field memiliki format penampilan yang telah ditentukan
Ditandatangani secara digital oleh {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} Tanggal: {Date} Alasan: {
Alasan
(#getReason.getReason/#setReason(String).setReason(String))}
Lokasi: {
Location
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties bernilai true secara default.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Menimpa metode Equals untuk membandingkan properti tanda tangan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | signature | java.lang.Object | Objek Signature untuk dibandingkan. |
|

**Returns:**
boolean - Mengembalikan true jika objek signature yang diberikan memiliki tipe yang sama dan semua propertinya sama dengan properti instance ini.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Menimpa metode GetHashCode


**Returns:**
int - Kode hash Signature

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Klon instance Barcode Signature.


**Returns:**
java.lang.Object - Mengembalikan instance Barcode Signature yang dikloning.

