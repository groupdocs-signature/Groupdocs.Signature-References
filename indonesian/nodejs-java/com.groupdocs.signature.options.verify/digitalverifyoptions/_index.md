---
title: "DigitalVerifyOptions"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Menyimpan opsi untuk memverifikasi tanda tangan Digital dokumen."
type: docs
weight: 12
url: /id/nodejs-java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

Menyimpan opsi untuk memverifikasi tanda tangan Digital dokumen.

--------------------

**Learn more**

 *  Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document ][How to eVerification Digital signatures in a document]
 *  Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings


[How to eVerification Digital signatures in a document]: https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DigitalVerifyOptions()](#DigitalVerifyOptions--) | Membuat Opsi Verifikasi Digital dengan nilai default. |
| [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | Membuat Opsi Verifikasi Digital dengan GUID sertifikat digital yang diberikan. |
| [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | Membuat Opsi Verifikasi Digital dengan aliran sertifikat yang diberikan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCertificate()](#getCertificate--) | Dapatkan Sertifikat X509Certificate2 dari GUID Sertifikat atau Aliran. |
| [getPassword()](#getPassword--) | Kata sandi Sertifikat Digital jika diperlukan. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Kata sandi Sertifikat Digital jika diperlukan. |
| [getCertificateFilePath()](#getCertificateFilePath--) | GUID File Sertifikat Digital. |
| [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | GUID File Sertifikat Digital. |
| [getCertificateStream()](#getCertificateStream--) | Aliran Sertifikat Digital. |
| [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Aliran Sertifikat Digital. |
| [getComments()](#getComments--) | Komentar Tanda Tangan Digital untuk divalidasi. |
| [setComments(String value)](#setComments-java.lang.String-) | Komentar Tanda Tangan Digital untuk divalidasi. |
| [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Rentang tanggal dan waktu Tanda Tangan Digital untuk divalidasi. |
| [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Rentang tanggal dan waktu Tanda Tangan Digital untuk divalidasi. |
| [getSignDateTimeTo()](#getSignDateTimeTo--) | Rentang tanggal dan waktu Tanda Tangan Digital untuk divalidasi. |
| [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Rentang tanggal dan waktu Tanda Tangan Digital untuk divalidasi. |
| [getReason()](#getReason--) | Alasan Tanda Tangan Digital untuk divalidasi. |
| [setReason(String value)](#setReason-java.lang.String-) | Alasan Tanda Tangan Digital untuk divalidasi. |
| [getContact()](#getContact--) | Kontak Tanda Tangan untuk divalidasi. |
| [setContact(String value)](#setContact-java.lang.String-) | Kontak Tanda Tangan untuk divalidasi. |
| [getLocation()](#getLocation--) | Lokasi Tanda Tangan untuk divalidasi. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Lokasi Tanda Tangan untuk divalidasi. |
| [getSubjectName()](#getSubjectName--) | Nama subjek yang dibedakan dari sertifikat untuk divalidasi. |
| [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Nama subjek yang dibedakan dari sertifikat untuk divalidasi. |
| [getIssuerName()](#getIssuerName--) | Nama penerbit sertifikat untuk divalidasi. |
| [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Nama penerbit sertifikat untuk divalidasi. |
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


Membuat Opsi Verifikasi Digital dengan nilai default.

### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


Membuat Opsi Verifikasi Digital dengan GUID sertifikat digital yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| certificateGuid | java.lang.String | Path file ke sertifikat digital. |

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


Membuat Opsi Verifikasi Digital dengan aliran sertifikat yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Aliran sertifikat. |

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


Dapatkan Sertifikat X509Certificate2 dari GUID Sertifikat atau Aliran.

**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Kata sandi Sertifikat Digital jika diperlukan.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Kata sandi Sertifikat Digital jika diperlukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


GUID File Sertifikat Digital.

**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


GUID File Sertifikat Digital.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Aliran Sertifikat Digital.

**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Aliran Sertifikat Digital.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Komentar Tanda Tangan Digital untuk divalidasi.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Komentar Tanda Tangan Digital untuk divalidasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


Rentang tanggal dan waktu Tanda Tangan Digital untuk divalidasi. Nilai yang dapat bernilai null akan diabaikan.

**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


Rentang tanggal dan waktu Tanda Tangan Digital untuk divalidasi. Nilai yang dapat bernilai null akan diabaikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


Rentang tanggal dan waktu Tanda Tangan Digital untuk divalidasi. Nilai yang dapat bernilai null akan diabaikan.

**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


Rentang tanggal dan waktu Tanda Tangan Digital untuk divalidasi. Nilai yang dapat bernilai null akan diabaikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Alasan Tanda Tangan Digital untuk divalidasi.

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Alasan Tanda Tangan Digital untuk divalidasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Kontak Tanda Tangan untuk divalidasi.

**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Kontak Tanda Tangan untuk divalidasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Lokasi Tanda Tangan untuk divalidasi.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Lokasi Tanda Tangan untuk divalidasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Nama subjek yang dibedakan dari sertifikat untuk divalidasi. Nilai bersifat sensitif huruf. Jika properti ini diatur, verifikasi akan memeriksa apakah nama subjek Tanda Tangan mengandung atau sama dengan nilai yang diberikan.

**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Nama subjek yang dibedakan dari sertifikat untuk divalidasi. Nilai bersifat sensitif huruf. Jika properti ini diatur, verifikasi akan memeriksa apakah nama subjek Tanda Tangan mengandung atau sama dengan nilai yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Nama penerbit sertifikat untuk divalidasi. Nilai bersifat sensitif huruf. Jika properti ini diatur, verifikasi akan memeriksa apakah nama penerbit Tanda Tangan mengandung atau sama dengan nilai yang diberikan.

**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Nama penerbit sertifikat untuk divalidasi. Nilai bersifat sensitif huruf. Jika properti ini diatur, verifikasi akan memeriksa apakah nama penerbit Tanda Tangan mengandung atau sama dengan nilai yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

