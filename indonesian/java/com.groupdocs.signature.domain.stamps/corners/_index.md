---
title: "Corners"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mewakili sudut-sudut objek grafis persegi."
type: docs
weight: 10
url: /id/java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

Mewakili sudut-sudut objek grafis persegi.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Corners()](#Corners--) | Menginisialisasi instance baru dari kelas Corners menggunakan nilai nol. |
|
|  | [Corners(double all)](#Corners-double-) | Menginisialisasi instance baru dari kelas Corners menggunakan nilai yang diberikan untuk semua sudut. |
|
|  | [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | Menginisialisasi instance baru dari kelas Corners menggunakan nilai-nilai yang diberikan. |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Empty](#Empty) | Menyediakan objek Corners tanpa data. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getAll()](#getAll--) | Mendapatkan atau mengatur nilai untuk semua sudut. |
|
|  | [setAll(double value)](#setAll-double-) | Mendapatkan atau mengatur nilai untuk semua sudut. |
|
|  | [getTopLeft()](#getTopLeft--) | Mendapatkan atau mengatur nilai sudut kiri atas. |
|
|  | [setTopLeft(double value)](#setTopLeft-double-) | Mendapatkan atau mengatur nilai sudut kiri atas. |
|
|  | [getTopRight()](#getTopRight--) | Mendapatkan atau mengatur nilai sudut kanan atas. |
|
|  | [setTopRight(double value)](#setTopRight-double-) | Mendapatkan atau mengatur nilai sudut kanan atas. |
|
|  | [getBottomLeft()](#getBottomLeft--) | Mendapatkan atau mengatur nilai sudut kiri bawah. |
|
|  | [setBottomLeft(double value)](#setBottomLeft-double-) | Mendapatkan atau mengatur nilai sudut kiri bawah. |
|
|  | [getBottomRight()](#getBottomRight--) | Mendapatkan atau mengatur nilai sudut kanan bawah. |
|
|  | [setBottomRight(double value)](#setBottomRight-double-) | Mendapatkan atau mengatur nilai sudut kanan bawah. |
|
|  | [deepClone()](#deepClone--) | Mendapatkan salinan objek ini. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Timpa metode equals |
|
|  | [hashCode()](#hashCode--) | Menimpa pengambilan nilai kode hash unik |
|
|  | [toString()](#toString--) | Menimpa konversi ke string. |
|
### Corners() {#Corners--}
```
public Corners()
```


Menginisialisasi instance baru dari kelas Corners menggunakan nilai nol.


### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


Menginisialisasi instance baru dari kelas Corners menggunakan nilai yang diberikan untuk semua sudut.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | semua | double | Nilai yang akan digunakan untuk padding pada semua sudut. |
|

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


Menginisialisasi instance baru dari kelas Corners menggunakan nilai-nilai yang diberikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | topLeft | double | Nilai sudut kiri atas. |
|
|  | topRight | double | Nilai sudut kanan atas. |
|
|  | bottomLeft | double | Nilai sudut kiri bawah. |
|
|  | bottomRight | double | Nilai sudut kanan bawah. |
|

### Empty {#Empty}
```
public static final Corners Empty
```


Menyediakan objek Corners tanpa data.


### getAll() {#getAll--}
```
public final double getAll()
```


Mendapatkan atau mengatur nilai untuk semua sudut.
Mengubah bagian sudut mana pun seperti kanan atas membuat properti ini menjadi 0;


**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


Mendapatkan atau mengatur nilai untuk semua sudut.
Mengubah bagian sudut mana pun seperti kanan atas membuat properti ini menjadi 0;


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


Mendapatkan atau mengatur nilai sudut kiri atas.


**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


Mendapatkan atau mengatur nilai sudut kiri atas.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


Mendapatkan atau mengatur nilai sudut kanan atas.


**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


Mendapatkan atau mengatur nilai sudut kanan atas.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


Mendapatkan atau mengatur nilai sudut kiri bawah.


**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


Mendapatkan atau mengatur nilai sudut kiri bawah.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


Mendapatkan atau mengatur nilai sudut kanan bawah.


**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


Mendapatkan atau mengatur nilai sudut kanan bawah.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Mendapatkan salinan objek ini.


**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Timpa metode equals


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | obj | java.lang.Object | Instansi untuk dibandingkan. |
|

**Returns:**
boolean - Mengembalikan true jika properti objek sama.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Menimpa pengambilan nilai kode hash unik


**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


Menimpa konversi ke string.


**Returns:**
java.lang.String -
