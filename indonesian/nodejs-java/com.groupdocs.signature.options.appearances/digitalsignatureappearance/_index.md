---
title: "DigitalSignatureAppearance"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Menjelaskan tampilan Garis Tanda Tangan untuk Tanda Tangan Digital."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

Menjelaskan tampilan Signature Line untuk Digital Signature. Satu Signature Line hanya dapat diterapkan untuk satu Digital Signature. Signature Line selalu berada di halaman pertama. Fitur ini mungkin berguna untuk format file .docx, .doc, .odt, dan .xlsx.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | Membuat objek Signature Line Appearance. |
| [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | Membuat Signature Line Appearance dengan nilai yang ditentukan (signer, title, email). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSigner()](#getSigner--) | Mendapatkan atau mengatur nama signer untuk signature line. |
| [setSigner(String value)](#setSigner-java.lang.String-) | Mendapatkan atau mengatur nama signer untuk signature line. |
| [getTitle()](#getTitle--) | Mendapatkan atau mengatur judul untuk signature line. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Mendapatkan atau mengatur judul untuk signature line. |
| [getEmail()](#getEmail--) | Mendapatkan atau mengatur email yang akan ditampilkan di signature line. |
| [setEmail(String value)](#setEmail-java.lang.String-) | Mendapatkan atau mengatur email yang akan ditampilkan di signature line. |
| [toString()](#toString--) | Timpa konversi string. |
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


Membuat objek Signature Line Appearance.

### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


Membuat Signature Line Appearance dengan nilai yang ditentukan (signer, title, email).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signer | java.lang.String | Nama Signer. |
| judul | java.lang.String | Judul Signature. |
| email | java.lang.String | Email Penulis. |

### getSigner() {#getSigner--}
```
public final String getSigner()
```


Mendapatkan atau mengatur nama signer untuk signature line.

**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


Mendapatkan atau mengatur nama signer untuk signature line.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Mendapatkan atau mengatur judul untuk signature line.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Mendapatkan atau mengatur judul untuk signature line.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


Mendapatkan atau mengatur email yang akan ditampilkan di signature line.

**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


Mendapatkan atau mengatur email yang akan ditampilkan di signature line.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Timpa konversi string.

**Returns:**
java.lang.String -
