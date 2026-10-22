---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Opsi penyimpanan untuk dokumen Presentasi."
type: docs
weight: 12
url: /id/nodejs-java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

Opsi penyimpanan untuk dokumen Presentasi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PresentationSaveOptions()](#PresentationSaveOptions--) | Menginisialisasi instance baru dari kelas PresentationSaveOptions dengan nilai default. |
| [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | Menginisialisasi instance baru dari kelas PresentationSaveOptions dengan format file output yang ditentukan. |
| [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | Menginisialisasi instance baru dari kelas PresentationSaveOptions dengan tipe output yang ditentukan dan flag timpa. |
| [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | Menginisialisasi instance baru dari kelas PresentationSaveOptions dengan format file output yang ditentukan dan flag timpa. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Mendapatkan atau mengatur format file dokumen yang ditandatangani. |
| [setFileFormat(int value)](#setFileFormat-int-) | Mendapatkan atau mengatur format file dokumen yang ditandatangani. |
| [toString()](#toString--) | Timpa konversi string. |
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Menginisialisasi instance baru dari kelas PresentationSaveOptions dengan nilai default.

### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


Menginisialisasi instance baru dari kelas PresentationSaveOptions dengan format file output yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileFormat | int | Tipe file output [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


Menginisialisasi instance baru dari kelas PresentationSaveOptions dengan tipe output yang ditentukan dan flag timpa.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| overwriteExistingFile | boolean | Flag apakah akan menimpa file yang ditandatangani dengan file yang sama. |

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Menginisialisasi instance baru dari kelas PresentationSaveOptions dengan format file output yang ditentukan dan flag timpa.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileFormat | int | Tipe file output [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
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
