---
title: "MetadataSignatureCollection"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Koleksi objek tanda tangan Metadata."
type: docs
weight: 13
url: /id/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class MetadataSignatureCollection implements Iterable<MetadataSignature>
```

Koleksi objek tanda tangan Metadata.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [MetadataSignatureCollection()](#MetadataSignatureCollection--) | Membuat Koleksi Metadata signature. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getCount()](#getCount--) | Mendapatkan jumlah item dalam koleksi. |
|
|  | [clear()](#clear--) | Menghapus semua item dari koleksi. |
|
|  | [contains(String name)](#contains-java.lang.String-) | Mengembalikan true jika Metadata dengan nama yang ditentukan ada dalam koleksi. |
|
|  | [indexOf(String name)](#indexOf-java.lang.String-) | Mendapatkan indeks properti berdasarkan nama. |
|
|  | [remove(String name)](#remove-java.lang.String-) | Menghapus Metadata Signature dengan nama yang ditentukan dari koleksi. |
|
|  | [removeAt(int index)](#removeAt-int-) | Menghapus Metadata Signature pada indeks yang ditentukan. |
|
|  | [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Menambahkan objek Metadata Signature ke koleksi. |
|
|  | [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | Menambahkan koleksi Metadata Signature. |
|
|  | [deepClone()](#deepClone--) | Mengkloning kelas Metadata Signature Collection dengan Item Metadata Signature. |
|
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


Membuat Koleksi Metadata signature.


### getCount() {#getCount--}
```
public final int getCount()
```


Mendapatkan jumlah item dalam koleksi.


**Returns:**
int
### clear() {#clear--}
```
public final void clear()
```


Menghapus semua item dari koleksi.


### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Mengembalikan true jika Metadata dengan nama yang ditentukan ada dalam koleksi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama properti yang tidak sensitif huruf besar/kecil. |
|

**Returns:**
boolean - True jika Metadata ada dalam koleksi; false jika tidak.

### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


Mendapatkan indeks properti berdasarkan nama.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama MetadataSignature yang tidak sensitif huruf besar/kecil. |
|

**Returns:**
int - Indeks berbasis nol. Nilai negatif jika tidak ditemukan.

### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


Menghapus Metadata Signature dengan nama yang ditentukan dari koleksi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama Metadata Signature yang tidak sensitif huruf besar/kecil. |
|

**Returns:**
boolean -
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


Menghapus Metadata Signature pada indeks yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | indeks | int | Indeks berbasis nol. |
|

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


Menambahkan objek Metadata Signature ke koleksi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Metadata signature yang akan ditambahkan ke koleksi. |

<br />

*** ** * ** ***

Melemparkan pengecualian jika nilai nama tidak unik dalam seluruh koleksi yang ada.

<br />

|

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


Menambahkan koleksi Metadata Signature.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Koleksi tanda tangan untuk ditambahkan. |

<br />

*** ** * ** ***

Melemparkan pengecualian jika nilai nama tidak unik dalam seluruh koleksi yang ada.

<br />

|

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Mengkloning kelas Metadata Signature Collection dengan Item Metadata Signature.


**Returns:**
java.lang.Object - Mengembalikan instance yang disalin dengan Item Signature yang dikloning

