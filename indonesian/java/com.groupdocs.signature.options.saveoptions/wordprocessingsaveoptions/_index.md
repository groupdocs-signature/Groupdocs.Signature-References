---
title: "WordProcessingSaveOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Opsi penyimpanan untuk dokumen Pengolah Kata."
type: docs
weight: 15
url: /id/java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

Opsi penyimpanan untuk dokumen Pengolah Kata.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Menginisialisasi instance baru dari kelas WordProcessingSaveOptions dengan nilai default. |
|
|  | [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | Menginisialisasi instance baru dari kelas WordProcessingSaveOptions dengan format file output yang ditentukan. |
|
|  | [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | Menginisialisasi instance baru dari kelas WordProcessingSaveOptions dengan tipe output yang ditentukan dan flag timpa. |
|
|  | [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | Menginisialisasi instance baru dari kelas WordProcessingSaveOptions dengan format file output yang ditentukan dan flag timpa. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Mendapatkan atau mengatur format file dokumen yang ditandatangani. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Mendapatkan atau mengatur format file dokumen yang ditandatangani. |
|
|  | [toString()](#toString--) | Timpa konversi string |
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Menginisialisasi instance baru dari kelas WordProcessingSaveOptions dengan nilai default.


### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


Menginisialisasi instance baru dari kelas WordProcessingSaveOptions dengan format file output yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileFormat | int | Tipe file output [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
|

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


Menginisialisasi instance baru dari kelas WordProcessingSaveOptions dengan tipe output yang ditentukan dan flag timpa.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Flag apakah akan menimpa file yang ditandatangani dengan file yang sama. |
|

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Menginisialisasi instance baru dari kelas WordProcessingSaveOptions dengan format file output yang ditentukan dan flag timpa.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileFormat | int | Tipe file output [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
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

### toString() {#toString--}
```
public String toString()
```


Timpa konversi string


**Returns:**
java.lang.String -
