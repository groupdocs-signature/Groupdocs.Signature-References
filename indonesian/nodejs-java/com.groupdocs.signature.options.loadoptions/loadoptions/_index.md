---
title: "LoadOptions"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Memungkinkan untuk menentukan opsi tambahan seperti kata sandi saat membuka dokumen untuk ditandatangani."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.signature.options.loadoptions/loadoptions/
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
| [LoadOptions()](#LoadOptions--) | Menginisialisasi instance baru dari kelas LoadOptions. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPassword()](#getPassword--) | Mendapatkan atau mengatur kata sandi untuk membuka dokumen yang dilindungi. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Mendapatkan atau mengatur kata sandi untuk membuka dokumen yang dilindungi. |
| [getLoadExternalResources()](#getLoadExternalResources--) | Mendapatkan atau mengatur opsi yang menentukan apakah sumber daya dokumen eksternal harus dimuat. |
| [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | Mendapatkan atau mengatur opsi yang menentukan apakah sumber daya dokumen eksternal harus dimuat. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Menginisialisasi instance baru dari kelas LoadOptions.

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Mendapatkan atau mengatur kata sandi untuk membuka dokumen yang dilindungi. Kata sandi ini juga akan digunakan untuk menyimpan dokumen yang ditandatangani sebagai terlindungi.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Mendapatkan atau mengatur kata sandi untuk membuka dokumen yang dilindungi. Kata sandi ini juga akan digunakan untuk menyimpan dokumen yang ditandatangani sebagai terlindungi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


Mendapatkan atau mengatur opsi yang menentukan apakah sumber daya dokumen eksternal harus dimuat. Opsi ini dengan nilai nonaktif (false) memungkinkan menghemat waktu pemuatan untuk dokumen dengan banyak atau tautan sumber daya eksternal yang besar. Secara default nilai diaktifkan (true).

**Returns:**
boolean
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


Mendapatkan atau mengatur opsi yang menentukan apakah sumber daya dokumen eksternal harus dimuat. Opsi ini dengan nilai nonaktif (false) memungkinkan menghemat waktu pemuatan untuk dokumen dengan banyak atau tautan sumber daya eksternal yang besar. Secara default nilai diaktifkan (true).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

