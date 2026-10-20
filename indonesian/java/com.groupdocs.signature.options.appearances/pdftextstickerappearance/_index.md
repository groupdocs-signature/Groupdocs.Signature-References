---
title: "PdfTextStickerAppearance"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Menggambarkan tampilan objek stiker anotasi teks PDF dan jendela pop-up stiker."
type: docs
weight: 14
url: /id/java/com.groupdocs.signature.options.appearances/pdftextstickerappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfTextStickerAppearance extends SignatureAppearance
```

Menggambarkan tampilan objek stiker anotasi teks PDF dan jendela pop-up stiker.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PdfTextStickerAppearance()](#PdfTextStickerAppearance--) | Membuat objek tampilan anotasi teks tanda tangan PDF. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getTitle()](#getTitle--) | Mendapatkan atau mengatur judul jendela pop-up. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Mendapatkan atau mengatur judul jendela pop-up. |
|
|  | [getSubject()](#getSubject--) | Mendapatkan atau mengatur subjek. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Mendapatkan atau mengatur subjek. |
|
|  | [getContents()](#getContents--) | Mendapatkan atau mengatur isi jendela pop-up. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | Mendapatkan atau mengatur isi jendela pop-up. |
|
|  | [getOpened()](#getOpened--) | Atur apakah jendela pop-up stiker akan dibuka secara default. |
|
|  | [setOpened(boolean value)](#setOpened-boolean-) | Atur apakah jendela pop-up stiker akan dibuka secara default. |
|
|  | [getIcon()](#getIcon--) | Mendapatkan atau mengatur ikon stiker. |
|
|  | [setIcon(int value)](#setIcon-int-) | Mendapatkan atau mengatur ikon stiker. |
|
|  | [getDefaultAppearance()](#getDefaultAppearance--) | Mendapatkan tampilan default untuk stiker. |
|
|  | [resetDefaultAppearance()](#resetDefaultAppearance--) | Menghapus nilai tampilan default untuk stiker. |
|
|  | [toString()](#toString--) | Timpa konversi string. |
|
### PdfTextStickerAppearance() {#PdfTextStickerAppearance--}
```
public PdfTextStickerAppearance()
```


Membuat objek tampilan anotasi teks tanda tangan PDF.


### getTitle() {#getTitle--}
```
public final String getTitle()
```


Mendapatkan atau mengatur judul jendela pop-up.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Mendapatkan atau mengatur judul jendela pop-up.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Mendapatkan atau mengatur subjek.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Mendapatkan atau mengatur subjek.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getContents() {#getContents--}
```
public final String getContents()
```


Mendapatkan atau mengatur isi jendela pop-up.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Mendapatkan atau mengatur isi jendela pop-up.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getOpened() {#getOpened--}
```
public final boolean getOpened()
```


Atur apakah jendela pop-up stiker akan dibuka secara default.


**Returns:**
boolean
### setOpened(boolean value) {#setOpened-boolean-}
```
public final void setOpened(boolean value)
```


Atur apakah jendela pop-up stiker akan dibuka secara default.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getIcon() {#getIcon--}
```
public final int getIcon()
```


Mendapatkan atau mengatur ikon stiker.


**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public final void setIcon(int value)
```


Mendapatkan atau mengatur ikon stiker.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public static PdfTextStickerAppearance getDefaultAppearance()
```


Mendapatkan tampilan default untuk stiker. Properti ini diterapkan sebagai default jika
Properti Options.SignatureAppearance tidak ditentukan.
Properti dapat diubah oleh pengguna kapan saja.


**Returns:**
[PdfTextStickerAppearance](../../com.groupdocs.signature.options.appearances/pdftextstickerappearance)
### resetDefaultAppearance() {#resetDefaultAppearance--}
```
public static void resetDefaultAppearance()
```


Menghapus nilai tampilan default untuk stiker.


### toString() {#toString--}
```
public String toString()
```


Timpa konversi string.


**Returns:**
java.lang.String -
