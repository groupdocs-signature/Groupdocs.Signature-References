---
title: "PdfSaveOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Opsi penyimpanan untuk dokumen PDF."
type: docs
weight: 11
url: /id/java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

Opsi penyimpanan untuk dokumen PDF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PdfSaveOptions()](#PdfSaveOptions--) | Menginisialisasi instance baru dari kelas PdfSaveOptions dengan nilai default. |
|
|  | [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | Menginisialisasi instance baru dari kelas PdfSaveOptions dengan format file keluaran yang ditentukan. |
|
|  | [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | Menginisialisasi instance baru dari kelas PdfSaveOptions dengan flag timpa. |
|
|  | [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | Menginisialisasi instance baru dari kelas PdfSaveOptions dengan format file keluaran yang ditentukan dan flag timpa. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Mendapatkan atau mengatur format file dokumen yang ditandatangani. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Mendapatkan atau mengatur format file dokumen yang ditandatangani. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | Sebuah kata sandi izin (kata sandi utama) memerlukan kata sandi untuk mengubah pengaturan izin. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Sebuah kata sandi izin (kata sandi utama) memerlukan kata sandi untuk mengubah pengaturan izin. |
|
|  | [getPermissions()](#getPermissions--) | Izin dokumen PDF seperti pencetakan, modifikasi, dan ekstraksi data. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Izin dokumen PDF seperti pencetakan, modifikasi, dan ekstraksi data. |
|
|  | [toString()](#toString--) | Timpa konversi string. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


Menginisialisasi instance baru dari kelas PdfSaveOptions dengan nilai default.


### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


Menginisialisasi instance baru dari kelas PdfSaveOptions dengan format file keluaran yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileFormat | int | Tipe file keluaran [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


Menginisialisasi instance baru dari kelas PdfSaveOptions dengan flag timpa.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Flag apakah akan menimpa file yang ditandatangani dengan file yang sama. |
|

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Menginisialisasi instance baru dari kelas PdfSaveOptions dengan format file keluaran yang ditentukan dan flag timpa.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileFormat | int | Tipe file keluaran [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|
|  | overwriteExistingFile | boolean | Flag apakah akan menimpa file yang ditandatangani dengan file yang sama. |
|

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Mendapatkan atau mengatur format file dokumen yang ditandatangani.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Mendapatkan atau mengatur format file dokumen yang ditandatangani.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Sebuah kata sandi izin (kata sandi utama) memerlukan kata sandi untuk mengubah pengaturan izin.


**Returns:**
java.lang.String
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Sebuah kata sandi izin (kata sandi utama) memerlukan kata sandi untuk mengubah pengaturan izin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


Izin dokumen PDF seperti pencetakan, modifikasi, dan ekstraksi data.


Untuk mengubah izin ini,
PermissionsPassword
harus diatur.
Nilai tersebut adalah kombinasi flag dari [Permissions](../../com.groupdocs.signature.options/permissions).
Sebuah
null
nilai berarti tidak ada izin eksplisit yang diterapkan.


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Izin dokumen PDF seperti pencetakan, modifikasi, dan ekstraksi data.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


Timpa konversi string.


**Returns:**
java.lang.String -
