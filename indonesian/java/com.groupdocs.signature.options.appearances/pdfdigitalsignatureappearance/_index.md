---
title: "PdfDigitalSignatureAppearance"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Menggambarkan tampilan Tanda Tangan Digital pada dokumen PDF."
type: docs
weight: 12
url: /id/java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

Menggambarkan tampilan Tanda Tangan Digital pada dokumen PDF.

<br />

*** ** * ** ***

**Learn more**

* See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures](../https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/)
* See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties](../https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/)

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | Membuat objek tampilan tanda tangan dengan nilai default. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getContactInfoLabel()](#getContactInfoLabel--) | Mendapatkan atau mengatur label info kontak. |
|
|  | [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | Mendapatkan atau mengatur label info kontak. |
|
|  | [getReasonLabel()](#getReasonLabel--) | Mendapatkan atau mengatur label alasan. |
|
|  | [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | Mendapatkan atau mengatur label alasan. |
|
|  | [getLocationLabel()](#getLocationLabel--) | Mendapatkan atau mengatur label lokasi. |
|
|  | [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | Mendapatkan atau mengatur label lokasi. |
|
|  | [getDigitalSignedLabel()](#getDigitalSignedLabel--) | Mendapatkan atau mengatur label tanda tangan digital. |
|
|  | [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | Mendapatkan atau mengatur label tanda tangan digital. |
|
|  | [getDateSignedAtLabel()](#getDateSignedAtLabel--) | Mendapatkan atau mengatur label tanggal tanda tangan. |
|
|  | [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | Mendapatkan atau mengatur label tanggal tanda tangan. |
|
|  | [getBackground()](#getBackground--) | Mengambil atau mengatur warna latar belakang tampilan tanda tangan. |
|
|  | [setBackground(Color value)](#setBackground-java.awt.Color-) | Mengambil atau mengatur warna latar belakang tampilan tanda tangan. |
|
|  | [setBackground(String value)](#setBackground-java.lang.String-) | Mengambil atau mengatur warna latar belakang tampilan tanda tangan. |
|
|  | [getFontFamilyName()](#getFontFamilyName--) | Mendapatkan atau mengatur nama keluarga Font untuk menampilkan label. |
|
|  | [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | Mendapatkan atau mengatur nama keluarga Font untuk menampilkan label. |
|
|  | [getFontSize()](#getFontSize--) | Mendapatkan atau mengatur ukuran Font untuk menampilkan label. |
|
|  | [setFontSize(double value)](#setFontSize-double-) | Mendapatkan atau mengatur ukuran Font untuk menampilkan label. |
|
|  | [getForeground()](#getForeground--) | Mengambil atau mengatur warna teks latar depan tampilan tanda tangan. |
|
|  | [setForeground(Color value)](#setForeground-java.awt.Color-) | Mengambil atau mengatur warna teks latar depan tampilan tanda tangan. |
|
|  | [setForeground(String value)](#setForeground-java.lang.String-) | Mengambil atau mengatur warna teks latar depan tampilan tanda tangan. |
|
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


Membuat objek tampilan tanda tangan dengan nilai default.


### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


Mendapatkan atau mengatur label info kontak. Nilai default: "Contact".
Jika nilai ini kosong maka tidak akan muncul label kontak pada area tanda tangan digital.


**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


Mendapatkan atau mengatur label info kontak. Nilai default: "Contact".
Jika nilai ini kosong maka tidak akan muncul label kontak pada area tanda tangan digital.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


Mendapatkan atau mengatur label alasan. Nilai default: "Reason".
Jika nilai ini kosong maka tidak akan muncul label alasan pada area tanda tangan digital.


**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


Mendapatkan atau mengatur label alasan. Nilai default: "Reason".
Jika nilai ini kosong maka tidak akan muncul label alasan pada area tanda tangan digital.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


Mendapatkan atau mengatur label lokasi. Nilai default: "Location".
Jika nilai ini kosong maka tidak akan muncul label lokasi pada area tanda tangan digital.


**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


Mendapatkan atau mengatur label lokasi. Nilai default: "Location".
Jika nilai ini kosong maka tidak akan muncul label lokasi pada area tanda tangan digital.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


Mendapatkan atau mengatur label tanda tangan digital. Nilai default: "Digitally signed by".


**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


Mendapatkan atau mengatur label tanda tangan digital. Nilai default: "Digitally signed by".


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


Mendapatkan atau mengatur label tanggal tanda tangan. Nilai default: "Date".


**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


Mendapatkan atau mengatur label tanggal tanda tangan. Nilai default: "Date".


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


Mengambil atau mengatur warna latar belakang tampilan tanda tangan.
Secara default nilai adalah SystemColors.Windows


**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


Mengambil atau mengatur warna latar belakang tampilan tanda tangan.
Secara default nilai adalah SystemColors.Windows


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


Mengambil atau mengatur warna latar belakang tampilan tanda tangan.
Secara default nilai adalah SystemColors.Windows


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


Mendapatkan atau mengatur nama keluarga Font untuk menampilkan label. Nilai default adalah "Arial".


**Returns:**
java.lang.String
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


Mendapatkan atau mengatur nama keluarga Font untuk menampilkan label. Nilai default adalah "Arial".


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


Mendapatkan atau mengatur ukuran Font untuk menampilkan label. Nilai default adalah 10.


**Returns:**
double
### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


Mendapatkan atau mengatur ukuran Font untuk menampilkan label. Nilai default adalah 10.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### getForeground() {#getForeground--}
```
public final Color getForeground()
```


Mengambil atau mengatur warna teks latar depan tampilan tanda tangan.
Secara default nilai adalah Color.FromArgb(76, 100, 255)


**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


Mengambil atau mengatur warna teks latar depan tampilan tanda tangan.
Secara default nilai adalah Color.FromArgb(76, 100, 255)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


Mengambil atau mengatur warna teks latar depan tampilan tanda tangan.
Secara default nilai adalah Color.FromArgb(76, 100, 255)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

