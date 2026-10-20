---
title: "DigitalSignature"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Berisi properti Tanda Tangan Digital."
type: docs
weight: 12
url: /id/java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

Berisi properti Tanda Tangan Digital.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [DigitalSignature()](#DigitalSignature--) | Inisialisasi tanda tangan digital dengan parameter default. |
|
|  | [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | Inisialisasi tanda tangan digital dengan SignatureId yang diketahui. |
|
|  | [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | Buat tanda tangan digital dengan sertifikat yang ditentukan. |
|
|  | [DigitalSignature(X509Certificate cert, PrivateKey key)](#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Buat tanda tangan digital berdasarkan sertifikat X509Certificate dan PrivateKey. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Mendapatkan atau mengatur sertifikat KeyStore. |
|
|  | [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | Mendapatkan atau mengatur sertifikat KeyStore. |
|
|  | [getX509Certificate()](#getX509Certificate--) | Mendapatkan atau mengatur sertifikat X509. |
|
|  | [setX509Certificate(X509Certificate value)](#setX509Certificate-java.security.cert.X509Certificate-) | Mendapatkan atau mengatur sertifikat X509. |
|
|  | [getPrivateKey()](#getPrivateKey--) | Mendapatkan atau mengatur PrivateKey dari sertifikat. |
|
|  | [setPrivateKey(PrivateKey value)](#setPrivateKey-java.security.PrivateKey-) | Mendapatkan atau mengatur PrivateKey dari sertifikat. |
|
|  | [getCertificateName()](#getCertificateName--) | Mendapatkan atau mengatur nama sertifikat X509. |
|
|  | [setCertificateName(String value)](#setCertificateName-java.lang.String-) | Mendapatkan atau mengatur nama sertifikat X509. |
|
|  | [getComments()](#getComments--) | Mendapatkan atau mengatur komentar tujuan penandatanganan. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Mendapatkan atau mengatur komentar tujuan penandatanganan. |
|
|  | [isValid()](#isValid--) | Menjaga nilai true jika tanda tangan digital ini valid dan dokumen tidak diubah. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Menjaga nilai true jika tanda tangan digital ini valid dan dokumen tidak diubah. |
|
|  | [getSignTime()](#getSignTime--) | Mendapatkan atau mengatur waktu dokumen ditandatangani. |
|
|  | [setSignTime(Date value)](#setSignTime-java.util.Date-) | Mendapatkan atau mengatur waktu dokumen ditandatangani. |
|
|  | [getXAdESType()](#getXAdESType--) | tipe XAdES |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | tipe XAdES |
XAdESType
.
|
|  | [getThumbprint()](#getThumbprint--) | Mendapatkan sidik jari dari sebuah sertifikat. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
|
|  | [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
|
|  | [deepClone()](#deepClone--) | Klon instance Barcode Signature. |
|
|  | [loadDigitalSignatures()](#loadDigitalSignatures--) | Muat tanda tangan Digital dari semua Penyimpanan Sertifikat X509 sistem. |
|
|  | [loadDigitalSignatures(StoreName storeName)](#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-) | Muat tanda tangan Digital dari Penyimpanan Sertifikat X509 yang diberikan. |
|
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


Inisialisasi tanda tangan digital dengan parameter default.


### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


Inisialisasi tanda tangan digital dengan SignatureId yang diketahui.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signatureId | java.lang.String |  |

### DigitalSignature(KeyStore certificate) {#DigitalSignature-java.security.KeyStore-}
```
public DigitalSignature(KeyStore certificate)
```


Buat tanda tangan digital dengan sertifikat yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | sertifikat | java.security.KeyStore | Sertifikat X509. |
|

### DigitalSignature(X509Certificate cert, PrivateKey key) {#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
```
public DigitalSignature(X509Certificate cert, PrivateKey key)
```


Buat tanda tangan digital berdasarkan sertifikat X509Certificate dan PrivateKey.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | cert | java.security.cert.X509Certificate | sertifikat X509Certificate. |
|
|  | key | java.security.PrivateKey | PrivateKey dari sertifikat. |
|

### getCertificate() {#getCertificate--}
```
public final KeyStore getCertificate()
```


Mendapatkan atau mengatur sertifikat KeyStore.


**Returns:**
java.security.KeyStore
### setCertificate(KeyStore value) {#setCertificate-java.security.KeyStore-}
```
public final void setCertificate(KeyStore value)
```


Mendapatkan atau mengatur sertifikat KeyStore.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.security.KeyStore |  |

### getX509Certificate() {#getX509Certificate--}
```
public final X509Certificate getX509Certificate()
```


Mendapatkan atau mengatur sertifikat X509.


**Returns:**
java.security.cert.X509Certificate
### setX509Certificate(X509Certificate value) {#setX509Certificate-java.security.cert.X509Certificate-}
```
public final void setX509Certificate(X509Certificate value)
```


Mendapatkan atau mengatur sertifikat X509.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.security.cert.X509Certificate |  |

### getPrivateKey() {#getPrivateKey--}
```
public final PrivateKey getPrivateKey()
```


Mendapatkan atau mengatur PrivateKey dari sertifikat.


**Returns:**
java.security.PrivateKey
### setPrivateKey(PrivateKey value) {#setPrivateKey-java.security.PrivateKey-}
```
public final void setPrivateKey(PrivateKey value)
```


Mendapatkan atau mengatur PrivateKey dari sertifikat.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.security.PrivateKey |  |

### getCertificateName() {#getCertificateName--}
```
public final String getCertificateName()
```


Mendapatkan atau mengatur nama sertifikat X509.


**Returns:**
java.lang.String
### setCertificateName(String value) {#setCertificateName-java.lang.String-}
```
public final void setCertificateName(String value)
```


Mendapatkan atau mengatur nama sertifikat X509.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Mendapatkan atau mengatur komentar tujuan penandatanganan.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Mendapatkan atau mengatur komentar tujuan penandatanganan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


Menjaga nilai true jika tanda tangan digital ini valid dan dokumen tidak diubah.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Menjaga nilai true jika tanda tangan digital ini valid dan dokumen tidak diubah.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


Mendapatkan atau mengatur waktu dokumen ditandatangani.


**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


Mendapatkan atau mengatur waktu dokumen ditandatangani.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


tipe XAdES
XAdESType
. Nilai default adalah None (XAdES dimatikan).
Saat ini tipe tanda tangan XAdES hanya didukung untuk dokumen Spreadsheet.


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


tipe XAdES
XAdESType
. Nilai default adalah None (XAdES dimatikan).
Saat ini tipe tanda tangan XAdES hanya didukung untuk dokumen Spreadsheet.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Mendapatkan sidik jari dari sebuah sertifikat.


**Returns:**
java.lang.String
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

### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


Muat tanda tangan Digital dari semua Penyimpanan Sertifikat X509 sistem.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Mengembalikan daftar [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) Tanda Tangan Digital.

### loadDigitalSignatures(StoreName storeName) {#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-}
```
public static List<DigitalSignature> loadDigitalSignatures(StoreName storeName)
```


Muat tanda tangan Digital dari Penyimpanan Sertifikat X509 yang diberikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| storeName | [StoreName](../../com.groupdocs.signature.domain.signatures/storename) |  |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Mengembalikan daftar [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) Tanda Tangan Digital.

