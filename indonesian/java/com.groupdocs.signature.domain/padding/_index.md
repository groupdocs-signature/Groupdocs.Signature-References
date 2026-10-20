---
title: "Padding"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mewakili informasi padding atau margin yang terkait dengan elemen."
type: docs
weight: 13
url: /id/java/com.groupdocs.signature.domain/padding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Padding implements Cloneable
```

Mewakili informasi padding atau margin yang terkait dengan elemen.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Padding()](#Padding--) | Menginisialisasi instance baru dari kelas Padding menggunakan nilai nol. |
|
|  | [Padding(int all)](#Padding-int-) | Menginisialisasi instance baru dari kelas Padding menggunakan ukuran padding yang diberikan untuk semua sisi. |
|
|  | [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | Menginisialisasi instance baru dari kelas Padding menggunakan ukuran padding yang diberikan. |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Empty](#Empty) | Menyediakan objek Padding tanpa padding. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getAll()](#getAll--) | Mendapatkan atau mengatur nilai padding untuk semua sisi. |
|
|  | [setAll(int value)](#setAll-int-) | Mendapatkan atau mengatur nilai padding untuk semua sisi. |
|
|  | [getLeft()](#getLeft--) | Mendapatkan atau mengatur nilai padding untuk sisi kiri. |
|
|  | [setLeft(int value)](#setLeft-int-) | Mendapatkan atau mengatur nilai padding untuk sisi kiri. |
|
|  | [getRight()](#getRight--) | Mendapatkan atau mengatur nilai padding untuk sisi kanan. |
|
|  | [setRight(int value)](#setRight-int-) | Mendapatkan atau mengatur nilai padding untuk sisi kanan. |
|
|  | [getTop()](#getTop--) | Mendapatkan atau mengatur nilai padding untuk sisi atas. |
|
|  | [setTop(int value)](#setTop-int-) | Mendapatkan atau mengatur nilai padding untuk sisi atas. |
|
|  | [getBottom()](#getBottom--) | Mendapatkan atau mengatur nilai padding untuk sisi bawah. |
|
|  | [setBottom(int value)](#setBottom-int-) | Mendapatkan atau mengatur nilai padding untuk sisi bawah. |
|
|  | [getHorizontal()](#getHorizontal--) | Mendapatkan padding gabungan untuk sisi kanan dan kiri. |
|
|  | [getVertical()](#getVertical--) | Mendapatkan padding gabungan untuk sisi atas dan bawah. |
|
|  | [deepClone()](#deepClone--) | Mendapatkan salinan objek ini. |
|
|  | [toString()](#toString--) | Menimpa konversi ke string |
|
### Padding() {#Padding--}
```
public Padding()
```


Menginisialisasi instance baru dari kelas Padding menggunakan nilai nol.


### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


Menginisialisasi instance baru dari kelas Padding menggunakan ukuran padding yang diberikan untuk semua sisi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | semua | int | Jumlah satuan ukuran yang akan digunakan untuk padding pada semua sisi. |
|

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


Menginisialisasi instance baru dari kelas Padding menggunakan ukuran padding yang diberikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | kiri | int | Ukuran padding kiri. |
|
|  | kanan | int | Ukuran padding kanan. |
|
|  | atas | int | Ukuran padding atas. |
|
|  | bawah | int | Ukuran padding bawah. |
|

### Empty {#Empty}
```
public static final Padding Empty
```


Menyediakan objek Padding tanpa padding.


### getAll() {#getAll--}
```
public final int getAll()
```


Mendapatkan atau mengatur nilai padding untuk semua sisi.
Mengubah salah satu tepi parsial seperti kiri atau atas membuat properti ini menjadi 0;


**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


Mendapatkan atau mengatur nilai padding untuk semua sisi.
Mengubah salah satu tepi parsial seperti kiri atau atas membuat properti ini menjadi 0;


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Mendapatkan atau mengatur nilai padding untuk sisi kiri.


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Mendapatkan atau mengatur nilai padding untuk sisi kiri.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


Mendapatkan atau mengatur nilai padding untuk sisi kanan.


**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Mendapatkan atau mengatur nilai padding untuk sisi kanan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Mendapatkan atau mengatur nilai padding untuk sisi atas.


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Mendapatkan atau mengatur nilai padding untuk sisi atas.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


Mendapatkan atau mengatur nilai padding untuk sisi bawah.


**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Mendapatkan atau mengatur nilai padding untuk sisi bawah.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


Mendapatkan padding gabungan untuk sisi kanan dan kiri.


**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


Mendapatkan padding gabungan untuk sisi atas dan bawah.


**Returns:**
int
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Mendapatkan salinan objek ini.


**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```


Menimpa konversi ke string


**Returns:**
java.lang.String -
