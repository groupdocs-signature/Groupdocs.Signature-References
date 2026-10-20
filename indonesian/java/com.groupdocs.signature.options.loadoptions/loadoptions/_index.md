---
title: "LoadOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mengizinkan untuk menentukan opsi tambahan seperti kata sandi saat membuka dokumen untuk ditandatangani."
type: docs
weight: 10
url: /id/java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Memungkinkan untuk menentukan opsi tambahan (seperti kata sandi) saat membuka dokumen untuk ditandatangani.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Menginisialisasi sebuah instance baru dari kelas LoadOptions. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPassword()](#getPassword--) | Mendapatkan atau mengatur kata sandi untuk membuka dokumen yang dilindungi. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Mendapatkan atau mengatur kata sandi untuk membuka dokumen yang dilindungi. |
|
|  | [getLoadExternalResources()](#getLoadExternalResources--) | Mendapatkan atau mengatur opsi yang menentukan apakah sumber daya dokumen eksternal harus dimuat. |
|
|  | [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | Mendapatkan atau mengatur opsi yang menentukan apakah sumber daya dokumen eksternal harus dimuat. |
|
|  | [getPermissions()](#getPermissions--) | Izin dokumen PDF seperti pencetakan, modifikasi, dan ekstraksi data. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Setter internal, digunakan oleh proses pemuatan dokumen untuk merekam izin yang diurai dari file. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Menginisialisasi sebuah instance baru dari kelas LoadOptions.


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Mendapatkan atau mengatur kata sandi untuk membuka dokumen yang dilindungi.
Ini juga akan digunakan untuk menyimpan dokumen yang ditandatangani sebagai terlindungi.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Mendapatkan atau mengatur kata sandi untuk membuka dokumen yang dilindungi.
Ini juga akan digunakan untuk menyimpan dokumen yang ditandatangani sebagai terlindungi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


Mendapatkan atau mengatur opsi yang menentukan apakah sumber daya dokumen eksternal harus dimuat.
Opsi ini dengan nilai nonaktif (false) memungkinkan menghemat waktu pemuatan untuk dokumen dengan banyak atau tautan sumber daya eksternal yang besar.
Secara default nilai diaktifkan (true).


**Returns:**
boolean
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


Mendapatkan atau mengatur opsi yang menentukan apakah sumber daya dokumen eksternal harus dimuat.
Opsi ini dengan nilai nonaktif (false) memungkinkan menghemat waktu pemuatan untuk dokumen dengan banyak atau tautan sumber daya eksternal yang besar.
Secara default nilai diaktifkan (true).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


Izin dokumen PDF seperti pencetakan, modifikasi, dan ekstraksi data.
Hanya untuk dokumen PDF. Hanya-baca \\u2014 diisi secara otomatis saat memuat dokumen.
Nilai tersebut adalah kombinasi flag dari [Permissions](../../com.groupdocs.signature.options/permissions).


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Setter internal, digunakan oleh proses pemuatan dokumen untuk merekam izin yang diurai dari file.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Integer |  |

