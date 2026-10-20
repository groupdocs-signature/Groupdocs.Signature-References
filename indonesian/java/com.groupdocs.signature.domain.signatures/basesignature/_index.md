---
title: "BaseSignature"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Menjelaskan kelas dasar untuk tanda tangan."
type: docs
weight: 11
url: /id/java/com.groupdocs.signature.domain.signatures/basesignature/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseSignature
```

Menjelaskan kelas dasar untuk tanda tangan.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSignatureType()](#getSignatureType--) | Menentukan jenis tanda tangan. |
|
|  | [getPageNumber()](#getPageNumber--) | Menentukan halaman tempat tanda tangan ditemukan. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Menentukan halaman tempat tanda tangan ditemukan. |
|
|  | [getSignatureId()](#getSignatureId--) | Pengidentifikasi tanda tangan unik untuk memodifikasi tanda tangan dalam dokumen melalui metode Update atau Delete. |
|
|  | [isSignature()](#isSignature--) | Dapatkan atau atur flag untuk menunjukkan apakah komponen ini adalah Tanda Tangan atau konten dokumen. |
|
|  | [setSignature(boolean value)](#setSignature-boolean-) | Dapatkan atau atur flag untuk menunjukkan apakah komponen ini adalah Tanda Tangan atau konten dokumen. |
|
|  | [getDeleted()](#getDeleted--) | Dapatkan atau atur flag untuk menunjukkan apakah tanda tangan ini telah dihapus dari dokumen. |
|
|  | [getCreatedOn()](#getCreatedOn--) | Dapatkan atau atur tanggal pembuatan tanda tangan. |
|
|  | [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | Dapatkan atau atur tanggal pembuatan tanda tangan. |
|
|  | [getModifiedOn()](#getModifiedOn--) | Dapatkan atau atur tanggal modifikasi tanda tangan. |
|
|  | [setModifiedOn(Date value)](#setModifiedOn-java.util.Date-) | Dapatkan atau atur tanggal modifikasi tanda tangan. |
|
|  | [getTop()](#getTop--) | Menentukan posisi atas tanda tangan. |
|
|  | [setTop(int value)](#setTop-int-) | Menentukan posisi atas tanda tangan. |
|
|  | [getLeft()](#getLeft--) | Menentukan posisi kiri tanda tangan. |
|
|  | [setLeft(int value)](#setLeft-int-) | Menentukan posisi kiri tanda tangan. |
|
|  | [getWidth()](#getWidth--) | Menentukan lebar tanda tangan. |
|
|  | [setWidth(int value)](#setWidth-int-) | Menentukan lebar tanda tangan. |
|
|  | [getHeight()](#getHeight--) | Menentukan tinggi tanda tangan. |
|
|  | [setHeight(int value)](#setHeight-int-) | Menentukan tinggi tanda tangan. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
|
|  | [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
|
| [supportMetaInfoLayer()](#supportMetaInfoLayer--) |  |
|  | [toString()](#toString--) | <br /> |

|
### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Menentukan jenis tanda tangan. Tanda tangan digital akan memiliki properti ini.


**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Menentukan halaman tempat tanda tangan ditemukan.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Menentukan halaman tempat tanda tangan ditemukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Integer |  |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Pengidentifikasi tanda tangan unik untuk memodifikasi tanda tangan dalam dokumen melalui metode Update atau Delete.
Properti ini akan diatur secara otomatis setelah metode Sign atau Search dipanggil.
Jika properti ini sebelumnya disimpan, dapat diatur secara manual untuk memanipulasi tanda tangan.


**Returns:**
java.lang.String
### isSignature() {#isSignature--}
```
public final boolean isSignature()
```


Dapatkan atau atur flag untuk menunjukkan apakah komponen ini adalah Tanda Tangan atau konten dokumen.
Properti ini digunakan dengan metode Update untuk mengatur elemen sebagai tanda tangan (true) atau elemen dokumen (false).


**Returns:**
boolean
### setSignature(boolean value) {#setSignature-boolean-}
```
public final void setSignature(boolean value)
```


Dapatkan atau atur flag untuk menunjukkan apakah komponen ini adalah Tanda Tangan atau konten dokumen.
Properti ini digunakan dengan metode Update untuk mengatur elemen sebagai tanda tangan (true) atau elemen dokumen (false).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


Dapatkan atau atur flag untuk menunjukkan apakah tanda tangan ini telah dihapus dari dokumen.
Properti ini hanya digunakan untuk catatan log riwayat dokumen guna menyimpan daftar tanda tangan yang dihapus.


**Returns:**
boolean
### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


Dapatkan atau atur tanggal pembuatan tanda tangan.


**Returns:**
java.util.Date
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


Dapatkan atau atur tanggal pembuatan tanda tangan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date |  |

### getModifiedOn() {#getModifiedOn--}
```
public final Date getModifiedOn()
```


Dapatkan atau atur tanggal modifikasi tanda tangan.


**Returns:**
java.util.Date
### setModifiedOn(Date value) {#setModifiedOn-java.util.Date-}
```
public final void setModifiedOn(Date value)
```


Dapatkan atau atur tanggal modifikasi tanda tangan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Menentukan posisi atas tanda tangan.


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Menentukan posisi atas tanda tangan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Menentukan posisi kiri tanda tangan.


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Menentukan posisi kiri tanda tangan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Menentukan lebar tanda tangan.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Menentukan lebar tanda tangan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Menentukan tinggi tanda tangan.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Menentukan tinggi tanda tangan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Menimpa metode Equals untuk membandingkan properti tanda tangan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | signature | java.lang.Object | Objek Signature untuk dibandingkan. |
|

**Returns:**
boolean - Mengembalikan true jika objek signature yang diberikan memiliki tipe yang sama dan semua propertinya sama dengan properti instance ini.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Menimpa metode GetHashCode


**Returns:**
int -
### supportMetaInfoLayer() {#supportMetaInfoLayer--}
```
public boolean supportMetaInfoLayer()
```




**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String -
