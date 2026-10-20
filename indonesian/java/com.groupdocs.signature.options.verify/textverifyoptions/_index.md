---
title: "TextVerifyOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Menyimpan opsi untuk memverifikasi tanda tangan Teks dokumen."
type: docs
weight: 14
url: /id/java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

Menyimpan opsi untuk memverifikasi tanda tangan Teks dokumen.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/)
* Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-text-signatures/)

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [TextVerifyOptions()](#TextVerifyOptions--) | Menginisialisasi instance baru dari TextVerifyOptions dengan nilai default. |
|
|  | [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | Menginisialisasi instance baru dari TextVerifyOptions dengan teks verifikasi. |
|
|  | [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | Menginisialisasi instance baru dari TextVerifyOptions dengan properti Text untuk diverifikasi dan implementasi tanda tangan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getText()](#getText--) | Tentukan Teks Tanda Tangan jika harus diverifikasi. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Tentukan Teks Tanda Tangan jika harus diverifikasi. |
|
|  | [getMatchType()](#getMatchType--) | Mendapatkan atau mengatur verifikasi Tipe Kecocokan Teks. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Mendapatkan atau mengatur verifikasi Tipe Kecocokan Teks. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Tipe Tanda Tangan yang akan diverifikasi. |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Tipe Tanda Tangan yang akan diverifikasi. |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Mendapatkan atau mengatur judul bidang formulir untuk memverifikasinya. |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Mendapatkan atau mengatur judul bidang formulir untuk memverifikasinya. |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | Mendapatkan atau mengatur tipe bidang formulir untuk memverifikasinya. |
|
|  | [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | Mendapatkan atau mengatur tipe bidang formulir untuk memverifikasinya. |
|
|  | [getSignatureID()](#getSignatureID--) | Tentukan ID Tanda Tangan Teks lebih dari nol jika harus diverifikasi. |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | Tentukan ID Tanda Tangan Teks lebih dari nol jika harus diverifikasi. |
|
|  | [toString()](#toString--) | Menimpa konversi ke string. |
|
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


Menginisialisasi instance baru dari TextVerifyOptions dengan nilai default.


### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


Menginisialisasi instance baru dari TextVerifyOptions dengan teks verifikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | teks | java.lang.String | Teks yang akan diverifikasi |
|

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


Menginisialisasi instance baru dari TextVerifyOptions dengan properti Text untuk diverifikasi dan implementasi tanda tangan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | teks | java.lang.String | Teks yang akan diverifikasi. |
|
|  | implementasi | int | Tipe Implementasi Tanda Tangan. |
|

### getText() {#getText--}
```
public final String getText()
```


Tentukan Teks Tanda Tangan jika harus diverifikasi.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Tentukan Teks Tanda Tangan jika harus diverifikasi.


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

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Tipe Tanda Tangan yang akan diverifikasi.


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Tipe Tanda Tangan yang akan diverifikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Mendapatkan atau mengatur judul bidang formulir untuk memverifikasinya.
Jika properti ini diatur, teks hanya akan ditemukan di bidang formulir teks.


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Mendapatkan atau mengatur judul bidang formulir untuk memverifikasinya.
Jika properti ini diatur, teks hanya akan ditemukan di bidang formulir teks.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


Mendapatkan atau mengatur tipe bidang formulir untuk memverifikasinya.
Jika properti ini diatur, teks hanya akan ditemukan di bidang formulir teks.


**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


Mendapatkan atau mengatur tipe bidang formulir untuk memverifikasinya.
Jika properti ini diatur, teks hanya akan ditemukan di bidang formulir teks.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Tentukan ID Tanda Tangan Teks lebih dari nol jika harus diverifikasi. Properti ini hanya didukung untuk dokumen Pdf.


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Tentukan ID Tanda Tangan Teks lebih dari nol jika harus diverifikasi. Properti ini hanya didukung untuk dokumen Pdf.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### toString() {#toString--}
```
public String toString()
```


Menimpa konversi ke string.


**Returns:**
java.lang.String -
