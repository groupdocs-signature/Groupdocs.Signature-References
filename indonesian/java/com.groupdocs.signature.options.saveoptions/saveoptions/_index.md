---
title: "SaveOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Memungkinkan untuk menentukan opsi tambahan seperti kata sandi saat menyimpan dokumen untuk ditandatangani."
type: docs
weight: 13
url: /id/java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Memungkinkan menentukan opsi tambahan (seperti kata sandi) saat menyimpan dokumen untuk ditandatangani.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Menginisialisasi instance baru dari kelas SaveOptions dengan nilai default. |
|
|  | [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | Menginisialisasi instance baru dari kelas SaveOptions dengan tipe output dan flag timpa yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | Mendapatkan atau mengatur apakah akan menimpa file yang ada dengan file output baru. |
|
|  | [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | Mendapatkan atau mengatur apakah akan menimpa file yang ada dengan file output baru. |
|
|  | [getPassword()](#getPassword--) | Mendapatkan atau mengatur kata sandi untuk menyimpan dokumen yang ditandatangani dengan perlindungan kata sandi. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Mendapatkan atau mengatur kata sandi untuk menyimpan dokumen yang ditandatangani dengan perlindungan kata sandi. |
|
|  | [getUseOriginalPassword()](#getUseOriginalPassword--) | Mendapatkan atau mengatur apakah akan menggunakan kata sandi dari LoadOptions untuk menyimpan dokumen yang ditandatangani sebagai terlindungi. |
|
|  | [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | Mendapatkan atau mengatur apakah akan menggunakan kata sandi dari LoadOptions untuk menyimpan dokumen yang ditandatangani sebagai terlindungi. |
|
|  | [getAddMissingExtenstion()](#getAddMissingExtenstion--) | Mendapatkan atau mengatur flag untuk secara otomatis menambahkan ekstensi ketika tidak ada dalam jalur file output. |
Nilai default adalah false.
|
|  | [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | Mendapatkan atau mengatur flag untuk secara otomatis menambahkan ekstensi ketika tidak ada dalam jalur file output. |
Nilai default adalah false.
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Menginisialisasi instance baru dari kelas SaveOptions dengan nilai default.


### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


Menginisialisasi instance baru dari kelas SaveOptions dengan tipe output dan flag timpa yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Flag apakah akan menimpa file yang ditandatangani dengan file yang sama. |
|

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


Mendapatkan atau mengatur apakah akan menimpa file yang ada dengan file output baru.
Jika tidak, file baru akan dibuat dengan nomor sebagai akhiran.


**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


Mendapatkan atau mengatur apakah akan menimpa file yang ada dengan file output baru.
Jika tidak, file baru akan dibuat dengan nomor sebagai akhiran.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Mendapatkan atau mengatur kata sandi untuk menyimpan dokumen yang ditandatangani dengan perlindungan kata sandi.
Properti ini tidak didukung untuk dokumen Gambar.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Mendapatkan atau mengatur kata sandi untuk menyimpan dokumen yang ditandatangani dengan perlindungan kata sandi.
Properti ini tidak didukung untuk dokumen Gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


Mendapatkan atau mengatur apakah akan menggunakan kata sandi dari LoadOptions untuk menyimpan dokumen yang ditandatangani sebagai terlindungi.
Nilai default adalah true.
Properti ini tidak didukung untuk dokumen Gambar.


**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


Mendapatkan atau mengatur apakah akan menggunakan kata sandi dari LoadOptions untuk menyimpan dokumen yang ditandatangani sebagai terlindungi.
Nilai default adalah true.
Properti ini tidak didukung untuk dokumen Gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


Mendapatkan atau mengatur flag untuk secara otomatis menambahkan ekstensi ketika tidak ada dalam jalur file output.
Nilai default adalah false.


**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


Mendapatkan atau mengatur flag untuk secara otomatis menambahkan ekstensi ketika tidak ada dalam jalur file output.
Nilai default adalah false.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

