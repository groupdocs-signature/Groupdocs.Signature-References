---
title: "PdfSaveOptions"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Opsi penyimpanan untuk dokumen PDF."
type: docs
weight: 11
url: /id/nodejs-java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
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
| [PdfSaveOptions()](#PdfSaveOptions--) | Menginisialisasi instance baru dari kelas PdfSaveOptions dengan nilai default. |
| [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | Menginisialisasi instance baru dari kelas PdfSaveOptions dengan format file output yang ditentukan. |
| [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | Menginisialisasi instance baru dari kelas PdfSaveOptions dengan flag timpa. |
| [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | Menginisialisasi instance baru dari kelas PdfSaveOptions dengan format file output yang ditentukan dan flag timpa. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Mendapatkan atau mengatur format file dokumen yang ditandatangani. |
| [setFileFormat(int value)](#setFileFormat-int-) | Mendapatkan atau mengatur format file dokumen yang ditandatangani. |
| [toString()](#toString--) | Timpa konversi string. |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


Menginisialisasi instance baru dari kelas PdfSaveOptions dengan nilai default.

### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


Menginisialisasi instance baru dari kelas PdfSaveOptions dengan format file output yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileFormat | int | Tipe file output [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


Menginisialisasi instance baru dari kelas PdfSaveOptions dengan flag timpa.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| overwriteExistingFile | boolean | Flag apakah akan menimpa file yang ditandatangani dengan file yang sama. |

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Menginisialisasi instance baru dari kelas PdfSaveOptions dengan format file output yang ditentukan dan flag timpa.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileFormat | int | Tipe file output [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
| overwriteExistingFile | boolean | Flag apakah akan menimpa file yang ditandatangani dengan file yang sama. |

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
