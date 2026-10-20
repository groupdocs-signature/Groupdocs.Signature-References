---
title: "CertificateVerifyOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Menyimpan opsi untuk memverifikasi dokumen sertifikat."
type: docs
weight: 11
url: /id/java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

Menyimpan opsi untuk memverifikasi dokumen sertifikat.

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [CertificateVerifyOptions()](#CertificateVerifyOptions--) | Menginisialisasi instance baru dari TextVerifyOptions dengan nilai default. |
|
|  | [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | Menginisialisasi instance baru dari CertificateVerifyOptions dengan subjek untuk diverifikasi. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getIssuer()](#getIssuer--) | Tentukan Penerbit Sertifikat jika harus diverifikasi. |
|
|  | [setIssuer(String value)](#setIssuer-java.lang.String-) | Tentukan Penerbit Sertifikat jika harus diverifikasi. |
|
|  | [getSerialNumber()](#getSerialNumber--) | Tentukan Nomor Seri Sertifikat jika harus diverifikasi. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Tentukan Nomor Seri Sertifikat jika harus diverifikasi. |
|
|  | [getSubject()](#getSubject--) | Tentukan subjek Sertifikat jika harus diverifikasi. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Tentukan subjek Sertifikat jika harus diverifikasi. |
|
|  | [getThumbprint()](#getThumbprint--) | Tentukan Sidik Jari Sertifikat jika harus diverifikasi. |
|
|  | [setThumbprint(String value)](#setThumbprint-java.lang.String-) | Tentukan Sidik Jari Sertifikat jika harus diverifikasi. |
|
|  | [getMatchType()](#getMatchType--) | Mendapatkan atau mengatur verifikasi Tipe Kecocokan Teks. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Mendapatkan atau mengatur verifikasi Tipe Kecocokan Teks. |
|
|  | [getExpired()](#getExpired--) | Menunjukkan apakah sertifikat telah kedaluwarsa berdasarkan hasil validasi. |
|
|  | [setExpired(boolean value)](#setExpired-boolean-) | Menunjukkan apakah sertifikat telah kedaluwarsa berdasarkan hasil validasi. |
|
|  | [getPerformChainValidation()](#getPerformChainValidation--) | Dapatkan atau atur apakah proses verifikasi harus menyediakan validasi rantai X.509 menggunakan kebijakan validasi dasar. |
|
|  | [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | Dapatkan atau atur apakah proses verifikasi harus menyediakan validasi rantai X.509 menggunakan kebijakan validasi dasar. |
|
|  | [toString()](#toString--) | Menimpa konversi ke string. |
|
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


Menginisialisasi instance baru dari TextVerifyOptions dengan nilai default.


### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


Menginisialisasi instance baru dari CertificateVerifyOptions dengan subjek untuk diverifikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | subjek | java.lang.String | Subjek yang akan diverifikasi |
|

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


Tentukan Penerbit Sertifikat jika harus diverifikasi.


**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


Tentukan Penerbit Sertifikat jika harus diverifikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Tentukan Nomor Seri Sertifikat jika harus diverifikasi.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Tentukan Nomor Seri Sertifikat jika harus diverifikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Tentukan subjek Sertifikat jika harus diverifikasi.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Tentukan subjek Sertifikat jika harus diverifikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Tentukan Sidik Jari Sertifikat jika harus diverifikasi.


**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


Tentukan Sidik Jari Sertifikat jika harus diverifikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Mendapatkan atau mengatur verifikasi Tipe Kecocokan Teks.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Mendapatkan atau mengatur verifikasi Tipe Kecocokan Teks.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


Menunjukkan apakah sertifikat telah kedaluwarsa berdasarkan hasil validasi.
Properti bersifat hanya-baca.


**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


Menunjukkan apakah sertifikat telah kedaluwarsa berdasarkan hasil validasi.
Properti bersifat hanya-baca.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


Dapatkan atau atur apakah proses verifikasi harus menyediakan validasi rantai X.509 menggunakan kebijakan validasi dasar.
Secara default nilai ini adalah true.


**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


Dapatkan atau atur apakah proses verifikasi harus menyediakan validasi rantai X.509 menggunakan kebijakan validasi dasar.
Secara default nilai ini adalah true.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Menimpa konversi ke string.


**Returns:**
java.lang.String -
