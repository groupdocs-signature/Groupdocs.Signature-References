---
title: "DigitalSignOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mewakili opsi tanda tangan Digital."
type: docs
weight: 11
url: /id/java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

Mewakili opsi tanda tangan Digital.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [DigitalSignOptions()](#DigitalSignOptions--) | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan nilai default. |
|
|  | [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan file sertifikat. |
|
|  | [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan aliran sertifikat. |
|
|  | [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan file sertifikat dan file gambar. |
|
|  | [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan file sertifikat dan aliran gambar. |
|
|  | [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan aliran sertifikat dan file gambar. |
|
|  | [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan aliran sertifikat dan aliran gambar. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getReason()](#getReason--) | Mendapatkan atau mengatur alasan tanda tangan. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Mendapatkan atau mengatur alasan tanda tangan. |
|
|  | [getContact()](#getContact--) | Mendapatkan atau mengatur kontak tanda tangan. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | Mendapatkan atau mengatur kontak tanda tangan. |
|
|  | [getLocation()](#getLocation--) | Mendapatkan atau mengatur lokasi tanda tangan. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Mendapatkan atau mengatur lokasi tanda tangan. |
|
|  | [getPassword()](#getPassword--) | Mendapatkan atau mengatur kata sandi sertifikat digital. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Mendapatkan atau mengatur kata sandi sertifikat digital. |
|
|  | [getSignature()](#getSignature--) | Mendapatkan atau mengatur properti tanda tangan digital dokumen. |
|
|  | [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | Mendapatkan atau mengatur properti tanda tangan digital dokumen. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Mendapatkan atau mengatur jalur file sertifikat digital. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Mendapatkan atau mengatur GUID file sertifikat digital. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Mendapatkan atau mengatur aliran sertifikat digital. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Mendapatkan atau mengatur aliran sertifikat digital. |
|
|  | [getVisible()](#getVisible--) | Mendapatkan atau mengatur visibilitas tanda tangan. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Mendapatkan atau mengatur visibilitas tanda tangan. |
|
|  | [getUseLtv()](#getUseLtv--) | Mendapatkan/mengatur flag validasi LTV (Long Term Validation). |
|
|  | [setUseLtv(boolean value)](#setUseLtv-boolean-) | Mendapatkan/mengatur flag validasi LTV (Long Term Validation). |
|
|  | [getCustomSignHash()](#getCustomSignHash--) | Mendapatkan atau mengatur implementasi hash-signing khusus, memungkinkan pemanggil untuk menyisipkan milik mereka sendiri |
logika penandatanganan digital (HSM, penandatangan jarak jauh, penyimpanan kunci perangkat lunak, dll).
|
|  | [setCustomSignHash(ICustomSignHash value)](#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-) | Mengatur implementasi hash-signing khusus, memungkinkan pemanggil untuk menyisipkan milik mereka sendiri |
logika penandatanganan digital.
|
|  | [getXAdESType()](#getXAdESType--) | tipe XAdES |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | tipe XAdES |
XAdESType
.
|
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
|  | [toString()](#toString--) | Timpa konversi string. |
|
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


Menginisialisasi instance baru dari kelas DigitalSignOptions dengan nilai default.


### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


Menginisialisasi instance baru dari kelas DigitalSignOptions dengan file sertifikat.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Jalur file sertifikat digital |
|

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


Menginisialisasi instance baru dari kelas DigitalSignOptions dengan aliran sertifikat.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Aliran Sertifikat Digital |
|

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


Menginisialisasi instance baru dari kelas DigitalSignOptions dengan file sertifikat dan file gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Jalur file sertifikat digital |
|
|  | imageFilePath | java.lang.String | Jalur file gambar Penampilan Tanda Tangan |
|

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


Menginisialisasi instance baru dari kelas DigitalSignOptions dengan file sertifikat dan aliran gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Jalur file sertifikat digital |
|
|  | appearenceImageStream | java.io.InputStream | Aliran gambar Penampilan Tanda Tangan |
|

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


Menginisialisasi instance baru dari kelas DigitalSignOptions dengan aliran sertifikat dan file gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Aliran Sertifikat Digital |
|
|  | imageFilePath | java.lang.String | Jalur file gambar Penampilan Tanda Tangan |
|

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


Menginisialisasi instance baru dari kelas DigitalSignOptions dengan aliran sertifikat dan aliran gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Aliran Sertifikat Digital |
|
|  | appearenceImageStream | java.io.InputStream | Aliran gambar Penampilan Tanda Tangan |
|

### getReason() {#getReason--}
```
public final String getReason()
```


Mendapatkan atau mengatur alasan tanda tangan.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Mendapatkan atau mengatur alasan tanda tangan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Mendapatkan atau mengatur kontak tanda tangan.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Mendapatkan atau mengatur kontak tanda tangan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Mendapatkan atau mengatur lokasi tanda tangan.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Mendapatkan atau mengatur lokasi tanda tangan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Mendapatkan atau mengatur kata sandi sertifikat digital.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Mendapatkan atau mengatur kata sandi sertifikat digital.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


Mendapatkan atau mengatur properti tanda tangan digital dokumen.


**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


Mendapatkan atau mengatur properti tanda tangan digital dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Mendapatkan atau mengatur jalur file sertifikat digital.
Properti ini hanya digunakan jika CertificateStream tidak ditentukan.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


Mendapatkan atau mengatur GUID file sertifikat digital.
Properti ini hanya digunakan jika CertificateStream tidak ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Mendapatkan atau mengatur aliran sertifikat digital.
Jika properti ini ditentukan, selalu digunakan menggantikan CertificateGuid.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Mendapatkan atau mengatur aliran sertifikat digital.
Jika properti ini ditentukan, selalu digunakan menggantikan CertificateGuid.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Mendapatkan atau mengatur visibilitas tanda tangan.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Mendapatkan atau mengatur visibilitas tanda tangan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


Mendapatkan/mengatur flag validasi LTV (Long Term Validation).


**Returns:**
boolean
### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


Mendapatkan/mengatur flag validasi LTV (Long Term Validation).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getCustomSignHash() {#getCustomSignHash--}
```
public final ICustomSignHash getCustomSignHash()
```


Mendapatkan atau mengatur implementasi hash-signing khusus, memungkinkan pemanggil untuk menyisipkan milik mereka sendiri
logika penandatanganan digital (HSM, penandatangan jarak jauh, penyimpanan kunci perangkat lunak, dll).


**Returns:**
[ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash)
### setCustomSignHash(ICustomSignHash value) {#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-}
```
public final void setCustomSignHash(ICustomSignHash value)
```


Mengatur implementasi hash-signing khusus, memungkinkan pemanggil untuk menyisipkan milik mereka sendiri
logika penandatanganan digital.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash) |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


tipe XAdES
XAdESType
. Nilai default adalah None (XAdES dimatikan).
Saat ini tipe tanda tangan XAdES hanya didukung untuk dokumen Spreadsheet pada .NET Framework saja (tidak pada .NET Standard).


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


tipe XAdES
XAdESType
. Nilai default adalah None (XAdES dimatikan).
Saat ini tipe tanda tangan XAdES hanya didukung untuk dokumen Spreadsheet pada .NET Framework saja (tidak pada .NET Standard).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getSignatureLineId() {#getSignatureLineId--}
```
public final UUID getSignatureLineId()
```




**Returns:**
java.util.UUID
### setSignatureLineId(UUID value) {#setSignatureLineId-java.util.UUID-}
```
public final void setSignatureLineId(UUID value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


Timpa konversi string.


**Returns:**
java.lang.String -
