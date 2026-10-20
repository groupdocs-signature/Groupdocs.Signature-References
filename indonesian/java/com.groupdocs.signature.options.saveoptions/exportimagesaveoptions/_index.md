---
title: "ExportImageSaveOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Opsi penyimpanan untuk mengekspor dokumen ke gambar."
type: docs
weight: 10
url: /id/java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

Opsi penyimpanan untuk mengekspor dokumen ke gambar.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [ExportImageSaveOptions()](#ExportImageSaveOptions--) | Menginisialisasi instance baru dari kelas ExportAsImageSaveOptions dengan nilai default. |
|
|  | [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | Menginisialisasi instance baru dari kelas ExportAsImageSaveOptions dengan format file yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Mendapatkan atau mengatur nomor halaman dokumen untuk ekspor. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Mendapatkan atau mengatur nomor halaman dokumen untuk ekspor. |
|
|  | [getExportAllPages()](#getExportAllPages--) | Flag untuk mengekspor setiap halaman. |
|
|  | [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | Flag untuk mengekspor setiap halaman. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Opsi untuk menentukan halaman yang akan ditandatangani. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Opsi untuk menentukan halaman yang akan ditandatangani. |
|
|  | [getPageColumns()](#getPageColumns--) | Mendapatkan atau mengatur jumlah kolom untuk gambar yang diekspor. |
|
|  | [setPageColumns(int value)](#setPageColumns-int-) | Mendapatkan atau mengatur jumlah kolom untuk gambar yang diekspor. |
|
|  | [getBorder()](#getBorder--) | Mendapatkan atau mengatur pengaturan batas gambar. |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Mendapatkan atau mengatur pengaturan batas gambar. |
|
|  | [getTiffMultipage()](#getTiffMultipage--) | Letakkan halaman dokumen pada frame yang berbeda dalam gambar Tiff. |
|
|  | [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | Letakkan halaman dokumen pada frame yang berbeda dalam gambar Tiff. |
|
|  | [toString()](#toString--) | Timpa konversi string. |
|
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


Menginisialisasi instance baru dari kelas ExportAsImageSaveOptions dengan nilai default.


### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


Menginisialisasi instance baru dari kelas ExportAsImageSaveOptions dengan format file yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileFormat | int | Format file gambar keluaran. |
|

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Mendapatkan atau mengatur nomor halaman dokumen untuk ekspor.
Nilai minimal adalah 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Mendapatkan atau mengatur nomor halaman dokumen untuk ekspor.
Nilai minimal adalah 1.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


Flag untuk mengekspor setiap halaman.


**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


Flag untuk mengekspor setiap halaman.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Opsi untuk menentukan halaman yang akan ditandatangani.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Opsi untuk menentukan halaman yang akan ditandatangani.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


Mendapatkan atau mengatur jumlah kolom untuk gambar yang diekspor.
Gunakan properti ini jika Anda perlu menempatkan gambar dalam satu baris.


**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


Mendapatkan atau mengatur jumlah kolom untuk gambar yang diekspor.
Gunakan properti ini jika Anda perlu menempatkan gambar dalam satu baris.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Mendapatkan atau mengatur pengaturan batas gambar. Secara default nilai ini tidak diatur.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Mendapatkan atau mengatur pengaturan batas gambar. Secara default nilai ini tidak diatur.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


Letakkan halaman dokumen pada frame yang berbeda dalam gambar Tiff.


**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


Letakkan halaman dokumen pada frame yang berbeda dalam gambar Tiff.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Timpa konversi string.


**Returns:**
java.lang.String -
