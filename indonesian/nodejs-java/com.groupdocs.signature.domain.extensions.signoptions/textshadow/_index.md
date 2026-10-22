---
title: "TextShadow"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Mewakili properti bayangan teks untuk tanda tangan teks."
type: docs
weight: 13
url: /id/nodejs-java/com.groupdocs.signature.domain.extensions.signoptions/textshadow/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class TextShadow extends SignatureExtension
```

Mewakili properti bayangan teks untuk tanda tangan teks. Hasilnya dapat bervariasi tergantung pada jenis tanda tangan dan format dokumen. TextShadow direkomendasikan untuk digunakan dengan tanda tangan TextAsImage untuk semua jenis dokumen yang didukung, juga dengan TextSignature sederhana dan TextSignature sebagai watermark untuk Cells (.xslx) dan Slides (.pptx). TextSignature sederhana untuk Words (.docx) juga direkomendasikan, tetapi memiliki fungsionalitas terbatas.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextShadow()](#TextShadow--) | Membuat TextShadow dengan opsi default. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDistance()](#getDistance--) | Mendapatkan atau mengatur jarak dari teks ke bayangan. |
| [setDistance(double value)](#setDistance-double-) | Mendapatkan atau mengatur jarak dari teks ke bayangan. |
| [getAngle()](#getAngle--) | Mendapatkan atau mengatur sudut penempatan bayangan relatif terhadap teks. |
| [setAngle(double value)](#setAngle-double-) | Mendapatkan atau mengatur sudut penempatan bayangan relatif terhadap teks. |
| [getColor()](#getColor--) | Mendapatkan atau mengatur warna bayangan. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Mendapatkan atau mengatur warna bayangan. |
| [setColor(String value)](#setColor-java.lang.String-) | Mendapatkan atau mengatur warna bayangan. |
| [getTransparency()](#getTransparency--) | Mendapatkan atau mengatur transparansi bayangan. |
| [setTransparency(double value)](#setTransparency-double-) | Mendapatkan atau mengatur transparansi bayangan. |
| [getBlur()](#getBlur--) | Mendapatkan atau mengatur keburaman bayangan. |
| [setBlur(double value)](#setBlur-double-) | Mendapatkan atau mengatur keburaman bayangan. |
### TextShadow() {#TextShadow--}
```
public TextShadow()
```


Membuat TextShadow dengan opsi default.

### getDistance() {#getDistance--}
```
public final double getDistance()
```


Mendapatkan atau mengatur jarak dari teks ke bayangan. Nilai default adalah 1.

**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Mendapatkan atau mengatur jarak dari teks ke bayangan. Nilai default adalah 1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


Mendapatkan atau mengatur sudut penempatan bayangan relatif terhadap teks. Nilai default adalah 0.

**Returns:**
double
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Mendapatkan atau mengatur sudut penempatan bayangan relatif terhadap teks. Nilai default adalah 0.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Mendapatkan atau mengatur warna bayangan. Nilai default adalah Hitam.

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Mendapatkan atau mengatur warna bayangan. Nilai default adalah Hitam.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Mendapatkan atau mengatur warna bayangan. Nilai default adalah Hitam.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Mendapatkan atau mengatur transparansi bayangan. Nilai default adalah 0.

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Mendapatkan atau mengatur transparansi bayangan. Nilai default adalah 0.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### getBlur() {#getBlur--}
```
public final double getBlur()
```


Mendapatkan atau mengatur keburaman bayangan. Nilai default adalah 4.

**Returns:**
double
### setBlur(double value) {#setBlur-double-}
```
public final void setBlur(double value)
```


Mendapatkan atau mengatur keburaman bayangan. Nilai default adalah 4.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

