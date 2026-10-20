---
title: "DigitalVBA"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mewakili tanda tangan digital untuk proyek VBA Spreadsheet."
type: docs
weight: 10
url: /id/java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

Mewakili tanda tangan digital untuk proyek VBA Spreadsheet.
Ini menyediakan kemampuan untuk menandatangani proyek VBA pada format dokumen Spreadsheet tertentu seperti Xlsm atau Xltm.
Jika beberapa ekstensi DigitalVBA ditambahkan ke DigitalSignOptions.Extensions, hanya yang pertama yang terlibat dalam penandatanganan dokumen.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | Menginisialisasi instance baru dari kelas DigitalVBA dengan file sertifikat. |
|
|  | [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | Menginisialisasi instance baru dari kelas DigitalVBA dengan aliran sertifikat. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getComments()](#getComments--) | Mendapatkan atau mengatur komentar tanda tangan. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Mendapatkan atau mengatur komentar tanda tangan. |
|
|  | [getPassword()](#getPassword--) | Mendapatkan atau mengatur kata sandi sertifikat digital. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Mendapatkan atau mengatur kata sandi sertifikat digital. |
|
|  | [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | Mendapatkan atau mengatur pengaturan penandatanganan hanya proyek VBA. |
|
|  | [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | Mendapatkan atau mengatur pengaturan penandatanganan hanya proyek VBA. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Mendapatkan jalur file sertifikat digital. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Mendapatkan aliran sertifikat digital. |
|
|  | [release()](#release--) | Metode override untuk membersihkan sumber daya setelah penandatanganan. |
|
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


Menginisialisasi instance baru dari kelas DigitalVBA dengan file sertifikat.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Jalur file sertifikat digital |
|
|  | kata sandi | java.lang.String | Kata sandi sertifikat digital |
|

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


Menginisialisasi instance baru dari kelas DigitalVBA dengan aliran sertifikat.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Aliran Sertifikat Digital |
|
|  | kata sandi | java.lang.String | Kata sandi sertifikat digital |
|

### getComments() {#getComments--}
```
public final String getComments()
```


Mendapatkan atau mengatur komentar tanda tangan.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Mendapatkan atau mengatur komentar tanda tangan.


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

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


Mendapatkan atau mengatur pengaturan penandatanganan hanya proyek VBA.
Jika disetel ke true, dokumen SpreadSheet tidak akan ditandatangani, tetapi proyek VBA akan ditandatangani.


**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


Mendapatkan atau mengatur pengaturan penandatanganan hanya proyek VBA.
Jika disetel ke true, dokumen SpreadSheet tidak akan ditandatangani, tetapi proyek VBA akan ditandatangani.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Mendapatkan jalur file sertifikat digital.
Properti ini hanya digunakan jika CertificateStream tidak ditentukan.


**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Mendapatkan aliran sertifikat digital.
Jika properti ini ditentukan, selalu akan digunakan sebagai pengganti CertificateFilePath.


**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


Metode override untuk membersihkan sumber daya setelah penandatanganan.


