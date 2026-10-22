---
title: "PdfTextAnnotationAppearance"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Menjelaskan tampilan objek anotasi teks PDF Title Subject Content."
type: docs
weight: 13
url: /id/nodejs-java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

Menjelaskan tampilan objek anotasi teks PDF (Judul, Subjek, Konten).
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | Membuat objek tampilan anotasi txt tanda tangan PDF. |
| [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | Membuat anotasi txt tanda tangan PDF dengan nilai yang ditentukan (title, subject, contents). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getContents()](#getContents--) | Mendapatkan atau mengatur konten objek anotasi. |
| [setContents(String value)](#setContents-java.lang.String-) | Mendapatkan atau mengatur konten objek anotasi. |
| [getSubject()](#getSubject--) | Mendapatkan atau mengatur Subject yang mewakili deskripsi objek. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Mendapatkan atau mengatur Subject yang mewakili deskripsi objek. |
| [getTitle()](#getTitle--) | Mendapatkan atau mengatur Judul yang akan ditampilkan di bilah judul objek anotasi. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Mendapatkan atau mengatur Judul yang akan ditampilkan di bilah judul objek anotasi. |
| [getBorder()](#getBorder--) | Mendapatkan atau mengatur pengaturan batas yang berbeda |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Mendapatkan atau mengatur pengaturan batas yang berbeda |
| [getBorderEffect()](#getBorderEffect--) | Mendapatkan atau mengatur efek batas. |
| [setBorderEffect(int value)](#setBorderEffect-int-) | Mendapatkan atau mengatur efek batas. |
| [getBorderEffectIntensity()](#getBorderEffectIntensity--) | Mendapatkan atau mengatur intensitas efek batas. |
| [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | Mendapatkan atau mengatur intensitas efek batas. |
| [getHCornerRadius()](#getHCornerRadius--) | Mendapatkan atau mengatur jari-jari sudut horizontal. |
| [setHCornerRadius(int value)](#setHCornerRadius-int-) | Mendapatkan atau mengatur jari-jari sudut horizontal. |
| [getVCornerRadius()](#getVCornerRadius--) | Mendapatkan atau mengatur jari-jari sudut vertikal. |
| [setVCornerRadius(int value)](#setVCornerRadius-int-) | Mendapatkan atau mengatur jari-jari sudut vertikal. |
| [toString()](#toString--) | Timpa konversi string. |
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


Membuat objek tampilan anotasi txt tanda tangan PDF.

### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


Membuat anotasi txt tanda tangan PDF dengan nilai yang ditentukan (title, subject, contents).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| judul | java.lang.String | Judul. |
| subjek | java.lang.String | Subjek. |
| isi | java.lang.String | Isi. |

### getContents() {#getContents--}
```
public final String getContents()
```


Mendapatkan atau mengatur konten objek anotasi.

**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Mendapatkan atau mengatur konten objek anotasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Mendapatkan atau mengatur Subject yang mewakili deskripsi objek.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Mendapatkan atau mengatur Subject yang mewakili deskripsi objek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Mendapatkan atau mengatur Judul yang akan ditampilkan di bilah judul objek anotasi.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Mendapatkan atau mengatur Judul yang akan ditampilkan di bilah judul objek anotasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Mendapatkan atau mengatur pengaturan batas yang berbeda

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Mendapatkan atau mengatur pengaturan batas yang berbeda

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


Mendapatkan atau mengatur efek batas.

**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


Mendapatkan atau mengatur efek batas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


Mendapatkan atau mengatur intensitas efek batas. Rentang nilai yang valid adalah [0..2].

**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


Mendapatkan atau mengatur intensitas efek batas. Rentang nilai yang valid adalah [0..2].

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


Mendapatkan atau mengatur jari-jari sudut horizontal.

**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


Mendapatkan atau mengatur jari-jari sudut horizontal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


Mendapatkan atau mengatur jari-jari sudut vertikal.

**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


Mendapatkan atau mengatur jari-jari sudut vertikal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### toString() {#toString--}
```
public String toString()
```


Timpa konversi string.

**Returns:**
java.lang.String -
