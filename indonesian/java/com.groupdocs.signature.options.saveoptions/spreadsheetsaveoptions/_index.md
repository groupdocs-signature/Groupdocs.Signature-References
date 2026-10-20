---
title: "SpreadsheetSaveOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Opsi penyimpanan untuk Dokumen Spreadsheet."
type: docs
weight: 14
url: /id/java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

Opsi penyimpanan untuk Dokumen Spreadsheet.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Menginisialisasi instance baru dari kelas SpreadsheetSaveOptions dengan nilai default. |
|
|  | [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | Menginisialisasi instance baru dari kelas SpreadsheetSaveOptions dengan format file output yang telah ditentukan. |
|
|  | [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | Menginisialisasi instance baru dari kelas SpreadsheetSaveOptions dengan tipe output yang ditentukan dan flag timpa. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Mendapatkan atau mengatur format file dokumen yang ditandatangani. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Mendapatkan atau mengatur format file dokumen yang ditandatangani. |
|
|  | [toString()](#toString--) | Timpa konversi string. |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Menginisialisasi instance baru dari kelas SpreadsheetSaveOptions dengan nilai default.


### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


Menginisialisasi instance baru dari kelas SpreadsheetSaveOptions dengan format file output yang telah ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileFormat | int | Menentukan format file output. |
|

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Menginisialisasi instance baru dari kelas SpreadsheetSaveOptions dengan tipe output yang ditentukan dan flag timpa.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileFormat | int | Menentukan format file output. |
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


Timpa konversi string.


**Returns:**
java.lang.String -
