---
title: "DigitalVerifyOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Menyimpan opsi untuk memverifikasi tanda tangan Digital dokumen."
type: docs
weight: 12
url: /id/java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

Menyimpan opsi untuk memverifikasi tanda tangan Digital dokumen.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](../https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/)
* Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Digital signatures in a document and additional settings](../)

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [DigitalVerifyOptions()](#DigitalVerifyOptions--) | Membuat Digital Verification Option dengan nilai default. |
|
|  | [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | Membuat Digital Verification Option dengan GUID sertifikat digital yang diberikan. |
|
|  | [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | Membuat Digital Verification Option dengan aliran sertifikat yang diberikan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Dapatkan X509Certificate2 Certificate dari Certificate Guid atau Stream. |
|
|  | [getPassword()](#getPassword--) | Kata sandi Digital Certificate jika diperlukan. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Kata sandi Digital Certificate jika diperlukan. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | File Guid dari Digital Certificate. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | File Guid dari Digital Certificate. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Aliran Digital Certificate. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Aliran Digital Certificate. |
|
|  | [getComments()](#getComments--) | Komentar Digital Signature untuk divalidasi. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Komentar Digital Signature untuk divalidasi. |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Rentang tanggal dan waktu Digital Signature untuk divalidasi. |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Rentang tanggal dan waktu Digital Signature untuk divalidasi. |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | Rentang tanggal dan waktu Digital Signature untuk divalidasi. |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Rentang tanggal dan waktu Digital Signature untuk divalidasi. |
|
|  | [getReason()](#getReason--) | Alasan Digital Signature untuk divalidasi. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Alasan Digital Signature untuk divalidasi. |
|
|  | [getContact()](#getContact--) | Kontak Signature untuk divalidasi. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | Kontak Signature untuk divalidasi. |
|
|  | [getLocation()](#getLocation--) | Lokasi Signature untuk divalidasi. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Lokasi Signature untuk divalidasi. |
|
|  | [getSubjectName()](#getSubjectName--) | Nama subjek yang dibedakan dari sertifikat untuk divalidasi. |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Nama subjek yang dibedakan dari sertifikat untuk divalidasi. |
|
|  | [getIssuerName()](#getIssuerName--) | Nama penerbit dari sertifikat untuk divalidasi. |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Nama penerbit dari sertifikat untuk divalidasi. |
|
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


Membuat Digital Verification Option dengan nilai default.


### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


Membuat Digital Verification Option dengan GUID sertifikat digital yang diberikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | certificateGuid | java.lang.String | Jalur file ke sertifikat digital. |
|

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


Membuat Digital Verification Option dengan aliran sertifikat yang diberikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Aliran sertifikat. |
|

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


Dapatkan X509Certificate2 Certificate dari Certificate Guid atau Stream.


**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Kata sandi Digital Certificate jika diperlukan.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Kata sandi Digital Certificate jika diperlukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


File Guid dari Digital Certificate.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


File Guid dari Digital Certificate.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Aliran Digital Certificate.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Aliran Digital Certificate.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Komentar Digital Signature untuk divalidasi.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Komentar Digital Signature untuk divalidasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


Rentang tanggal dan waktu Tanda Tangan Digital untuk divalidasi. Nilai yang dapat null akan diabaikan.


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


Rentang tanggal dan waktu Tanda Tangan Digital untuk divalidasi. Nilai yang dapat null akan diabaikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


Rentang tanggal dan waktu Tanda Tangan Digital untuk divalidasi. Nilai yang dapat null akan diabaikan.


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


Rentang tanggal dan waktu Tanda Tangan Digital untuk divalidasi. Nilai yang dapat null akan diabaikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Alasan Digital Signature untuk divalidasi.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Alasan Digital Signature untuk divalidasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Kontak Signature untuk divalidasi.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Kontak Signature untuk divalidasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Lokasi Signature untuk divalidasi.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Lokasi Signature untuk divalidasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Nama subjek yang dibedakan dari sertifikat untuk divalidasi. Nilai bersifat sensitif huruf.
Jika properti ini diatur, verifikasi akan memeriksa apakah nama subjek Tanda Tangan mengandung atau sama dengan nilai yang diberikan.


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Nama subjek yang dibedakan dari sertifikat untuk divalidasi. Nilai bersifat sensitif huruf.
Jika properti ini diatur, verifikasi akan memeriksa apakah nama subjek Tanda Tangan mengandung atau sama dengan nilai yang diberikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Nama penerbit sertifikat untuk divalidasi. Nilai bersifat sensitif huruf.
Jika properti ini diatur, verifikasi akan memeriksa apakah nama penerbit Tanda Tangan mengandung atau sama dengan nilai yang diberikan.


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Nama penerbit sertifikat untuk divalidasi. Nilai bersifat sensitif huruf.
Jika properti ini diatur, verifikasi akan memeriksa apakah nama penerbit Tanda Tangan mengandung atau sama dengan nilai yang diberikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

